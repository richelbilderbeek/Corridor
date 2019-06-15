# Corridor

Branch|[![Travis CI logo](pics/TravisCI.png)](https://travis-ci.org)
---|---
`master`|[![Build Status](https://travis-ci.org/richelbilderbeek/Corridor.svg?branch=master)](https://travis-ci.org/richelbilderbeek/Corridor)

Corridor using SDL that compiles under Qt Creator

The game is developed by Or Dvory, `gnudles@nana.co.il`.

All I, @richelbilderbeek did, was:
 * get it to compile in Qt Creator
 * add Travis CI support

## Installation

```
required development packages of:
	*SDL_ttf
	*SDL_image
	*SDL
build command:
$ sh build.sh
```

## Build

```
g++ ucorridor.cpp -o corridor -lSDL -lSDL_ttf -lSDL_image
```
