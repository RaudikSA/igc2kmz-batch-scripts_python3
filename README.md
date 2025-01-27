# igc2kmz batch converting scripts

## About

Scripts for an [igc2kmz project](https://github.com/twpayne/igc2kmz) to convert all *.igc files in dir to *.kmz

It adds coloring for lift/sink, calculate thermals, altitude points et.c. so it's very handy to analyze tracks in google earth afterwards.

Fork from [Dmitry-Borodin's igc2kmz batch converter](https://github.com/Dmitry-Borodin/igc2kmz-batch-scripts) to port from py2 to py3.

## Installation
* Install Python 3.*
* Download this repo 'git clone --recurse-submodules https://github.com/RaudikSA/igc2kmz-batch-scripts_python3.git'
* For Windows update path in the scripts if needed:
- igc2kmz.reg -update path to the igc2kmz.bat file and add to registry
- igc2kmz.bat - update path to igc2kmz project and python (downloaded above)


## Usage

[contributions are welcome, expecially in this part]

1)Create subfolders for each group member
2)Put tracks and color.txt (optional) files inside.
3)Run the script

Happy flights review on Google Earth.
