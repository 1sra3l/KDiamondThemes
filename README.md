# KDiamond Themes

This is literally what you think it is, if you think that these are themes for KDiamond!
If you dont know KDiamond, [check it out](https://games.kde.org/game.php?game=kdiamond)

Thanks to (BartM)[https://openclipart.org/artist/BartM] making some nice Tux art on (openclipart)[https://openclipart.org]!  One less thing to draw :D

### Preview images

![Alt text](rubix.png?raw=true "Rubix Cubix")

![Alt text](blocks.png?raw=true "Blocks")

![Alt text](blocks_circles.png?raw=true "Blocks and Circles")

![Alt text](tux_tiles.png?raw=true "Tux Tiles")

![Alt text](cute_bubbles.png?raw=true "Cute Bubbles")

![Alt text](flat_bubbles.png?raw=true "Flat Bubbles")

## TO INSTALL

Open your favorite file system navigation tool and copy/clone these files into `~/.local/share/kdiamond/themes/`
Then open up KDiamond and check them out!


# Contributing

No things that are offensive, or distasteful.  A.K.A. I get to say no if it does not meet my guidelines for generally safe content for kids!


## How to make a theme!

You will need 3 files for a theme:


```
<name>.svgz
<name>.desktop
<name>.png
```


The desktop file format:


```ini
VersionFormat=1
Name=
Description=
FileName=<name>.svgz
Author=
AuthorEmail=
Preview=<name>.png

# number of frames in the "remove" animation
RemoveAnimFrames=
# this theme has a border to display around the board
HasBorder=
# how many percent of each dimension of the board background contain the border graphics (0.05 means: the upper 5%, the lower 5%, the left 5%, and the right 5% of the board background are the border)
BorderPercentage=
```

The main thing to remember about the svgz file is to NAME YOUR GROUPS CORRECTLY
In object properties (find through right click menu in `inkscape`) make sure you have these names!!!



```
# Jewels
kdiamond-black
kdiamond-green
kdiamond-blue
kdiamond-yellow
kdiamond-red
kdiamond-orange
kdiamond-white

# Background
kdiamond-background

# Border
kdiamond-border

# Selection cursor
kdiamond-selection
```


