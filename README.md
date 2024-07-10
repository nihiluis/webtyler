# About

Use it here: https://wareya.github.io/webtyler/

Web Autotyler is an autotile conversion tool for turning small/incomplete autotile tilesets into complete, fleshed-out ones.

It supports nine different input formats and three different output formats, and displays a preview.

![screenshot](etc/screenshot.png)

Example inputs:

![minitiles](etc/mini.png)

![4x4plus](etc/grass4x4plus.png)

Outputs:

![minitiles output](etc/miniout.png)

![4x4plus](etc/grass4x4plusout.png)

# Extra

Autotyler's "killer feature" that sets it apart from other autotile tilemap conversion tools is the ability to specify exactly where the tiles get cut up (with the "margin offset" options), so you can use tiles with tops that overhang the halfway point without issue:

![margin example](etc/marginexample.png)

![margin example output](etc/marginexampleout.png)

Also supports outputting RPG maker autotile chipsets:

![rpg maker output](etc/grassrpgmaker.png)

And GameMaker Studio 2 Auto Tile tilesets:

![gamemaker output](etc/gms.png)

(The layout is different from the template, but the order is the same, and this matches GM's documentation)

The intended bitmask for the godot output is the following:

![godot minimal bitmask](etc/out%20bitmask.png)


## Modes

The seven algorithms take these kinds of inputs, in terms of autotile bitmasks:

### basic

![bitmask](etc/2x1%20bitmask.png)

### basic_border

![bitmask](etc/2x1%20bitmask.png)

### 3x3

![bitmask](etc/3x3%20bitmask.png)

### 3x3plus

![bitmask](etc/3x3plus%20bitmask.png)

### 4x4

![bitmask](etc/4x4%20bitmask.png)

### 4x4plus

![bitmask](etc/4x4plus%20bitmask.png)

### minitiles

![bitmask](etc/5x1%20bitmask.png)