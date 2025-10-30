# 🫀 PAAT to EPSPAP Calculator

A web-based calculator for estimating peak systolic pulmonary artery pressure (EPSPAP) from pulmonary artery acceleration time (PAAT) measured by Doppler echocardiography.

**🔗 Live Demo:** [https://parameterz.github.io/PAAT-Thing/](https://parameterz.github.io/PAAT-Thing/)

## Why This Matters

Conventional echocardiographic estimation of pulmonary artery pressure relies on tricuspid regurgitation (TR) velocity. However:
- **25% of patients** have insufficient TR for pressure estimation
- **PAAT is measurable in 99.6%** of patients

This calculator provides a validated alternative method for estimating pulmonary artery pressure when TR is absent or inadequate.

## Features

✅ Simple, single-input interface  
✅ Validated formula from peer-reviewed research  
✅ Automatic range validation (study range: 43-186 msec)  
✅ Mobile-responsive design  
✅ No installation required - pure HTML/JavaScript  

## Usage

1. Obtain PAAT measurement from pulsed-wave Doppler of the main pulmonary artery
2. Enter the PAAT value (in milliseconds)
3. Click "Calculate EPSPAP"
4. Review the estimated peak systolic pulmonary artery pressure

## The Science

**Formula:**  
```
log₁₀(EPSPAP) = -0.004(PAAT) + 2.1
```

**Validation:**
- Strong inverse correlation with TR-derived EPSPAP (r = -0.95)
- Excellent interobserver variability (r = 0.97)
- Validated in 371 patients across wide pressure range (19-102 mm Hg)

## Reference

Yared K, Noseworthy P, Weyman AE, McCabe E, Picard MH, Baggish AL. **Pulmonary Artery Acceleration Time Provides an Accurate Estimate of Systolic Pulmonary Arterial Pressure during Transthoracic Echocardiography.** *J Am Soc Echocardiogr.* 2011;24:687-92.

[https://doi.org/10.1016/j.echo.2011.03.008](https://doi.org/10.1016/j.echo.2011.03.008)

## Disclaimer

⚠️ **For educational purposes only.** This calculator should not be used as the sole basis for clinical decisions. Always correlate with clinical context and other diagnostic findings.

## Technical Details

- Pure HTML5/CSS3/JavaScript
- No dependencies or frameworks
- Works offline once loaded
- Compatible with all modern browsers

## License

MIT License - feel free to use, modify, and distribute.

---

**Questions or suggestions?** Open an issue or submit a pull request!
