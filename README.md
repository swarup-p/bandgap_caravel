# Bandgap Reference Design

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

A simple bandgap topology is evaluated with a set of simulations and then implemented in open-source EDA tools.
Please refer to this git repo for detailed information on the design (https://github.com/vsdip/avsdbgp_3v3_sky130_v1).

# Bandgap Performance Characteristics

| Parameter| Description| Min | Type | Max | Unit | Condition |
| :---:  | :-: | :-: | :-: | :---:  | :-: | :-: |
|Technology| 130 nm CMOS Process |
|RL|Load resistance at Vbgp terminal | 100|||Mohm|VDD=3.3V, T=27C|
|Vbgp|Output Reference voltage|1.197642|1.201057|1.212476|V|T=-40 to 140C, VDD=3.3V|
|Vbgp|Output Reference voltage|1.178285|1.201057|1.211677|V|VDD=2.7V to VDD=3.6V, T=27C|
|TC_vbgp|Temperature Coefficient of Vbgp||6.8717||ppm/C|T=-40 to 140C, VDD=3.3V|
|VC_vbgp|Voltage Coefficient of Vbgp||2.7802||%/V|VDD=2.7V to 3.6, T=27C|
|VDD|Supply Voltage|3.2|3.3|3.6|V|T=-40C to 140C|
|IDD|Supply Current||3.954||uA|EN=1|
|IDD|Supply Current||607.836||nA|EN=0|

#

Here are some reference links used to learn to design in open source EDA tools and about bandgap reference circuit design.

1. https://github.com/nickson-jose/vsdstdcelldesign

2. https://github.com/praharshapm/vsdmixedsignalflow

3. https://github.com/sherylcorina/avsdbgp_3v3

4. https://github.com/an3ol/General-purpose-Bandgap-Reference-avsdbgp_3v3

5. https://www.udemy.com/course/vlsi-academy-custom-layout/

# Acknowledgement

* [Kunal Ghosh - Co-founder (VSD Corp. Pvt. Ltd)](https://github.com/kunalg123)
* Tim Edwards - Senior Vice President of Analog and Design at efabless corporation
* Anmol Purty - VSD Intern
* Sheryl Serrao - VSD Intern
