Dataset Description
All the data files used in this research are provided inside the Data.zip archive.

Input Files:
Each input file is named in the format: Input_#_3col.csv
These files contain 3 columns, each corresponding to a structural parameter of the device:
1. Silver thickness (in nanometers, nm)
2. OrmoCore thickness (in nanometers, nm)
3. Grating period (in nanometers, nm)


Output Files:
Each output file is named in the format: output_#.csv
These files contain the reflection spectra as 2D matrices with:
401 rows representing wavelengths ranging from 400 nm to 800 nm, with a 1 nm step.
91 columns representing incident angles (θ) ranging from 0° to 90°, with a 1° step.

Each entry in the matrix represents the reflection value (between 0 and 1) for a specific combination of wavelength and incident angle, corresponding to the structural parameters provided in the input file.

![output file example](https://github.com/ShahrzadDG/Inverse-Design-of-Hybrid-Waveguide-Grating/blob/main/Data_samples/output_example.PNG?raw=true)



