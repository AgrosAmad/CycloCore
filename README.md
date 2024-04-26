# CycloCore

CycloCore is an open source implementation of turbulent heat and water continuity in the atmosphere. These commands can be integrated into an existing (one-moment) fluid solver.


It is a core implementation of the paper Cyclogenesis: Simulating Hurricanes and Tornadoes (refer to our [project page](http://computationalsciences.org/publications/amador-herrera-2024-cyclogenesis.html) for more details). This code base contains the following parts:

- Setup of atmospheric parameters
- Parametrization of background dry atmosphere
- Buoyancy and temperature of vapor and cloud matter in the atmosphere
- Turbulent interaction of dust and wind fields
- Prognosis equations for tropical cyclones (in cylindrical coordinates)

BibTex Citation
----------------------
@article{AmadorHerrera:2024:Cyclogenesis,
  author    = {Jorge~Alejandro Amador~Herrera and Jonathan Klein and Daoming Liu and Wojtek Pa{\l}ubicki and S\"oren Pirk and Dominik L.~Michels},
  title     = {Cyclogenesis: Simulating Hurricanes and Tornadoes},
  journal   = {ACM Transaction on Graphics},
  year      = {2024},
  month     = {7},
  volume    = {43},
  number    = {4},
  articleno = {71},
  doi       = {https://doi.org/10.1145/3658149},
  publisher = {ACM},
  address   = {New York, NY, USA}
}
