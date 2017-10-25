## FPG11-70 - An Emulation of the PDP11/70 System on an FPGA

The purpose of this project is to create a PDP11-70 emulation on an FPGA to run an untouched (as much as possible) version of RSX11-M. I want to stay true to the hardware architecture as much as possible.

The bulk of the information required to understand this project will be documented in the [Wiki](https://github.com/13mtfb/FPG11-70/wiki).

## Installation

The project was developed using Quartus II 64-Bit Version 13.0.1 (Service Pack 1 Installed). The project can be opened from Quartus using the FPG11-70.qpf file. Alternatively, the following instructions can be followed to setup a new project.

1. File -> New... -> New Quartus II Project
2. The working directory for this project is:
/home/everest/Documents/FPGA/FPG11-70/FPG11-70/src/KB11-C
3. The name of the project is:
FPG11-70
4. Import all Verilog (.v) files from the /src/ directories
5. Family & Device Settings:
Family: Cyclone II
Package: EP2C20F484C7
6. EDA Tool Settings
Design Entry/Synthesis: None
Simulation: ModelSim-Altera
Formal Verification: None
7. Click Next -> Finish

## Usage

To be added!!

## Contributing

Create an issue to contribute to the project.

## License

This project is uses information released by Digital Equipment Corporation and was found at http://bitsavers.trailing-edge.com/pdf/dec/pdp11/1170/.

