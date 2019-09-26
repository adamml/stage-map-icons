# Stage Map Icons

Tour de France stage map style icons in Scalable Vector Format for use in GIS applications

1. [Icons](#icons)
1. [Installation](#installation)
i. [QGIS 3.x](#qgis-3x)

## Icons

Icon | Name
--- | ---
![alt text](img/stage_start_thumbnail.jpg "Stage Start") | Stage Start
![alt text](img/stage_finish_thumbnail.jpg "Stage Finish") | Stage Finish
![alt text](img/kilometre_0_thumbnail.jpg "Kilometre 0") | Kilometre 0
Blah | Feed Zone
Blah | Feed Zone - Water Only
Blah | Split Time
Blah | Sprint
Blah | Climb - Hors Category
Blah | Climb - Category 1
Blah | Climb - Category 2
Blah | Climb - Category 3
Blah | Climb - Category 4
Blah | Tech Zone

## Installation

### QGIS 3.x
The correct location for user defined SVG symbols in QGIS 3.X has to be checked by opening `Settings | User Profiles | Open Active Profile Folder`.

If necessary, create an `svg` folder in this location. Then, QGIS will recognize it as the User's `svg` folder.

Copy the `Stage Map` folder from this repository to the `svg` folder.

Thanks to [@Kazuhito](https://gis.stackexchange.com/users/84455/kazuhito) on [StackOverflow](https://gis.stackexchange.com/questions/137855/importing-svg-symbols-into-qgis) for the guidance here.