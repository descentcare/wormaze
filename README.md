#**WORMAZE**

A game written entirely in bash, no additional dependencies required (only bash version 4 and above)

It's a TUI clone of https://erayzesen.itch.io/worm

##usage

```
$ ./wormaze lvlfile
```

for example:

```
$ ./wormaze lvl/1
```

hjkl or awsd to move, q to quit

##lvlfile format

Every line is coordinates for an object in "line;column" format(y;x).

* First line is for player
* Second is for exit
* Every other line is for a wall

I will be adding levels in the future

##TODO

- usage message
- resize map on terminal resize
- input multiple levels at once
- bot to test new levels
- level generator

Feel free to contribute your levels and changes! Have fun!
