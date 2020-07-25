# A* Path Finding Algorithm Visualization

![Build Status](https://img.shields.io/github/last-commit/RaymondBello/Procedural-Geometry-Planet-Maker) ![Build Status](https://img.shields.io/github/issues-raw/RaymondBello/Procedural-Geometry-Planet-Maker) ![Build Status](https://img.shields.io/github/contributors/RaymondBello/Procedural-Geometry-Planet-Maker?color) 
![Build Status](https://img.shields.io/github/languages/top/RaymondBello/Procedural-Geometry-Planet-Maker) ![Build Status](https://img.shields.io/github/languages/count/RaymondBello/Procedural-Geometry-Planet-Maker) 
![Build Status](https://img.shields.io/github/repo-size/RaymondBello/Procedural-Geometry-Planet-Maker?color=red) 

This code is aimed at visualizing an interactive interface for the A* Path finding algorithm using PyGame. 

![a-star.gif](https://www.dropbox.com/s/qlp94lfmk3wwqs0/a-star.gif?dl=0&raw=1)


## Table of contents
* [Usage](#usage)
* [Installation](#installation)
* [Visualization Legend](#visualization-Legend)

# Usage 
  - Click to Set Origin and Destination
  - Right click boxes to make a boundary/wall
  - Left click boxes to remove boundary/wall
  - Press SPACE to begin path finding algorithm

# Installation
```
git clone https://github.com/RaymondBello/A-Star-Algorithm-Visualization.git
pip install pygame
cd A-Star-Algorithm-Visualization
python3 a-star.py
```


## Visualization Legend
* RED -> Searched Path
* WHITE -> Unsearched Path
* GREEN -> Searched Path Edge 
* PURPLE -> Short Path between Origin and Setpoint
* ORANGE -> Origin
* TURQUOISE -> Destination