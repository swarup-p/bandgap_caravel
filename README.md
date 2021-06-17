# Bandgap Reference Design

Please refer to this git repo for detailed design information[link](https://github.com/vsdip/avsdbgp_3v3_sky130_v1)

A simple bandgap topology is evaluated with a set of simulations and then implemented in open-source EDA tools.

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


