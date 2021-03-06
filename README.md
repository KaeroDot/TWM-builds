![TracePQM](./imgz/logo_final_male_v1.png)

# TWM - TracePQM Wattmeter (builds)

TWM is developed in scope of [EMPIR](https://msu.euramet.org/calls.html) project [TracePQM](http://tracepqm.cmi.cz/).

TWM is a transparent, metrology grade measurement system for traceable measurement of the Power and Power Quality (PQ) parameters. However, it is not restricted to power and PQ area only. It is designed to allow recording of the voltage and current waveforms using various digitizers and processing the measured waveforms using ANY algorithm. It is composed of two main components:
- User interface and instrument control in [LabVIEW](http://www.ni.com/labview/),
- [GNU Octave](https://www.gnu.org/software/octave/) or [Matlab](https://uk.mathworks.com/products/matlab.html) calculation scripts for data processing.

This git contains only builds of the TWM tool, which can be found at another git: [smaslan/TWM](https://github.com/smaslan/TWM) 


## Downloads

Select version built only with required digitizers support to prevent installing of unnecessary instrument drivers:

- [V1.5.0.0 (built with: 3458A, NI5922, Soundcard), 2019.01.24 (ZIP file)](./builds/TWM-1.5.0.0-full.zip)
- [V1.5.0.0 (built with: 3458A, Soundcard), 2019.01.24 (ZIP file)](./builds/TWM-1.5.0.0-visa.zip)
- [V1.3.0.0 (built with: 3458A, NI5922, Soundcard), 2018.08.23 (ZIP file)](./builds/TWM-1.3.0.0-full.zip)



## License
The TWM is distributed under [MIT license](./LICENSE.txt). Note the algorithms in the QWTB toolbox may have different licenses. 
  
  