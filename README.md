## Monaco SUMO Traffic (MoST) Scenario

Contacts: Lara CODECA [codeca@eurecom.fr], A-Team [a-team@eurecom.fr]
This project is licensed under the terms of the GPLv3 license.

MoST Scenario is meant to be used with SUMO (Simulator of Urban MObility) and it has been tested with [SUMO 0.32.0](https://github.com/DLR-TS/sumo/tree/v0_32_0).
Please refer to the [SUMO wiki](http://sumo.dlr.de/wiki/Simulation_of_Urban_MObility_-_Wiki) for further information on the simulator itself.

#### How to cite it: [BibTeX](https://github.com/lcodeca/MoSTScenario/blob/master/misc/cite.bib)
L. Codeca, J. Härri,
*"Towards Multimodal Mobility Simulation of C-ITS: The Monaco SUMO Traffic Scenario"*
VNC 2017, IEEE Vehicular Networking Conference
November 27-29, 2017, Torino, Italy. 

#### How To:
MoST Scenario can be lunched directly with its configuration file.
* `sumo -c most.sumocfg` or `run.sh` from the _scenario_ folder.

Additional mobility can be generated using 
* `buildall.sh` from the _generation_ folder.

#### Files:
* `scenario` is the ready-to-use scenario
* `generation` contains the files required to generate various traffic demands
* `misc` contains the raw OSM-like file, and other configuration files.

Note: the configuration files contained in `misc/typemap` are a slightly modified version of a subset of the SUMO files availavle at https://github.com/DLR-TS/sumo/tree/master/data/typemap.
