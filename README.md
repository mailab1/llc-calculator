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
