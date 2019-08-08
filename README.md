# Collective Autonomous Vehicles

Main Authors:
- [Antonio Bucchiarone](mailto:bucchiarone@fbk.eu)
- [Annalisa Congiu](mailto:annalisa.congiu@studenti.unitn.it)


The focus of this project is to realize a framework to model, simulate and analyze dynamic and self-organized mobility systems through Multi-Agent Systems (MAS), in which heterogeneous ensembles/groups (composed by AV and travellers) are created and managed. The aim is to provide a solution able to handle the effects of multi-hop travels, in other words those in which passengers would commute from one car to another to reach farther destinations, thus introducing cooperative behaviours among AVs. Such behaviour could also help when some AVs have to face unexpected situations, such as breakdowns or heavy traffic and congestion, while having passengers on board, in order to alleviate the inconvenience that such problems imply for travelling time of travellers and quality of service.

This repository contains a GAMA platform project for the simulation of a system of ridesharing with autonomous vehicles (AV). There are scripts for a centralised and a decentralised version of control.

For a complete understanding we suggest to consult the documents, containing all the implemented algorithms, available at the following link: https://github.com/antbucc/CAV/blob/master/ACS_Algorithms.pdf

## Installation

The IDE used for the development was GAMA 1.7.
You can find a guide for the installation [here](https://github.com/gama-platform/gama/wiki/Installation).

## Usage

In each directory you can find the following:
 * includes: original GIS data and after parsing.
 * models: scripts to create a map that can be used in the system from raw GIS data,
    scripts for the centralised and the decentralised simulations.

## References
* 



## License
[MIT](https://choosealicense.com/licenses/mit/)
