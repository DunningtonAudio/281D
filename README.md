# 281D
A quad function generator project

The 281D Quad Function Generator is designed to replicate the functionality of the Buchla 281 module using modern construction techniques and readily available parts. It is primarily based on the original circuit designed by Don Buchla, with the following additions/alterations:

* Improved input and mode selection circuitry – no requirement to “kick” the generators when selecting self cycle mode.
* All outputs are buffered, protecting the integrator core and passive end pulse generation from the effects of loading when stacked to multiple inputs.
* End pulse outputs are designed to allow stacking of multiple outputs to a single input without affecting cycling of individual generators, allowing the creation of complex/non-repeating/polyrhythmic pulse sequences. Unlike other solutions that simply add a diode in series with the output, the 281D end pulse outputs can drive a floating input low.
 
There are several build options to adjust the function of the module to a particular users requirements.

The repository contains:

* KiCad project files.
* Schematic and build/calibration notes as PDF files.
* Bill of Materials in ODS format.
* Interactive webpage for matching BOM items to PCB locations.
