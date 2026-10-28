# LLC Resonant Converter Design Calculator

An interactive, browser-based tool for designing LLC resonant converters using a 
first-harmonic approximation (FHA) model. No installation required — runs entirely 
in the browser.

## Features
- Real-time gain curve visualization
- Operating-point markers across input-voltage and load range
- Colour-coded zero-voltage switching (ZVS) indicators
- Two-dimensional feasibility map for half-bridge and full-bridge topologies
- Validated against published reference designs (tank values and ZVS boundaries 
  agree to within 0.2%)

## Usage
Open `index.html` in any modern web browser. No server or installation needed.

## Background
LLC resonant converters are widely used in power supplies for their high efficiency, 
soft switching, and low electromagnetic interference. However, the resonant-tank 
components are tightly coupled, and zero-voltage switching (ZVS) must be verified 
across the full input-voltage and load range — making manual design difficult. 
This tool implements a first-harmonic approximation (FHA) model to let users 
explore the design space interactively.

## Validation
This tool has been validated against two published reference LLC converter designs, 
matching their resonant-tank component values and ZVS boundaries to within 0.2%.


## MATLAB GUI and Simulink Models

In addition to the browser-based calculator, this project includes a MATLAB graphical user interface (GUI) for LLC resonant converter design and dedicated Simulink models for both half-bridge and full-bridge LLC converter topologies.

### Features
- **MATLAB GUI Calculator:** Calculate and explore LLC resonant-tank design parameters through an interactive graphical interface.
- **Half-Bridge LLC Converter:** Simulink model for simulation and analysis of the half-bridge topology.
- **Full-Bridge LLC Converter:** Simulink model for simulation and analysis of the full-bridge topology.
- **Design and Simulation:** Use the GUI for converter design calculations and the Simulink models for time-domain simulation and verification.

### Compatibility
- **MATLAB/Simulink Version:** R2024a (MATLAB 2024a).
- The Simulink models were created using MATLAB/Simulink R2024a. Compatibility with earlier releases is not guaranteed.
- For the best experience, open the GUI and Simulink models in MATLAB/Simulink R2024a or a compatible newer release.

### Usage
1. Download or clone this repository.
2. Open MATLAB R2024a or a compatible newer version.
3. Open the MATLAB GUI application and enter the desired converter design specifications.
4. Open the corresponding half-bridge or full-bridge Simulink model to simulate the converter.

**Note:** MATLAB and Simulink are required to use the MATLAB GUI and simulation models. The browser-based calculator remains available independently and requires only a modern web browser.


## Citation
If you use this tool in your research, please cite:
## Citation
If you use this tool in your research, please cite:

M. Diab, "An Interactive Web-Based LLC Resonant Converter Design and Verification 
Tool," in *Proc. 36th Int. Conf. Comput. Theory Appl. (ICCTA)*, Alexandria, Egypt, 
Dec. 2026.

@inproceedings{diab2026llc,
  author    = {Diab, Mai},
  title     = {An Interactive Web-Based LLC Resonant Converter Design and Verification Tool},
  booktitle = {Proc. 36th Int. Conf. Comput. Theory Appl. (ICCTA)},
  address   = {Alexandria, Egypt},
  month     = dec,
  year      = {2026},
}

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file 
for details.
