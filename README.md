# Smart-Greenhouse-Simulink
# Smart Greenhouse Crop Growth Simulation (Simulink)

This repository presents a modular Simulink-based framework for simulating plant growth in an LED-lit greenhouse environment.  
The model integrates lighting, climate, irrigation, and plant physiological responses to evaluate growth dynamics and energy efficiency.

## Features
- LED lighting with photoperiod, spectrum, and Daily Light Integral (DLI)
- Dynamic thermal model with LED heat generation and ventilation losses
- Humidity and VPD-based plant response
- Soil water balance and irrigation modeling
- CO₂ enrichment
- Plant growth stages and logistic biomass accumulation
- Closed-loop PID control for LED intensity
- Energy consumption and growth efficiency analysis
- Comparative simulation of lettuce and tomato

## Model Structure
The model is organized into the following subsystems:
1. Lighting & Energy
2. Climate (Temperature, Humidity, CO₂)
3. Root Zone (Soil Water & Irrigation)
4. Plant Growth Model

## Notes
- All growth outputs are normalized indices and are intended for comparative analysis rather than direct yield prediction.
- Parameter values are chosen for realistic behavior but are not crop-calibrated.

## Example Results
- Lettuce shows faster early growth but lower final biomass.
- Tomato exhibits slower initial growth but higher long-term biomass.
- Energy efficiency varies with photoperiod and environmental control.

## Future Work
- Nutrient dynamics
- Multi-layer canopy modeling
- Calibration with experimental data


Tanmoy Acharya


## Author
[Your Name]
