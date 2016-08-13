###Welcome
This repository contains kite flight models useful for both measuring wind speed (anemometry) with kites and characterizing kite flights at different wind speeds to make predictions about kites. It also contains a catalog of tools for making the necessary measurements to do both of these things. 

Specific kite anemometer projects using Kite Wind Speed Meter elements are: 

* [The TALA]()
* hopefully more! [please contribute to this project](CONTRIBUTE.md)

Kite lift prediction tools using Kite Wind Speed Meter elements:

* none yet! [please add your project](CONTRIBUTE.md)

###Elements of a kite anemometer
A kite anemometer consists of a kite and means of interpretting information about the kite's flight to determine the wind speed.  
Measurements of altitude, angle, and the strength of the kite's pull, often in tandem with ground measurements of temperature and pressure are used interpretted through a kite-specific version of the kite wind speed meter flight model. The elements of this measurement and modeling system are:

#####hardware
* Kites
* Kite lines of known length 
* Tension gauges for line tension
* Orienteering devices for wind direction
* Thermometers for ground temperature
* Clinometers for the angle of the kite and the angle of the kite line

#####models and calibrations
* A means of creating kite specific versions of the kite wind speed meter flight model so the kite can be used in anemometry calculations.
* Means of calculating the kite's altitude from the kite's angle, kite line's angle, and the length of line released, adjusted for the sag of the kite line in relation to the kite, and the kite specific flight model
* A Means of calculating the wind speed from the line tension temperature, pressure, altitude of the kite, and kite-specific flight model.

###About this project
The Kite Wind Speed Meter is a project of [Public Lab](www.publiclab.org) to [collect ongoing research into kite flight models and measurement tools for anemometry](www.publiclab.org/tag/kite-anemometer) licensed under [CERN OHL 1.2](http://www.ohwr.org/attachments/2388/cern_ohl_v_1_2.txt).

To read more about using kite anemometers and find resources and sources used in this repository, visit the [Public Lab Wiki](publiclab.org/wiki/kite-anemometers). To learn more about contibuting, please read our [contribution guidelines](CONTRIBUTE.md)
