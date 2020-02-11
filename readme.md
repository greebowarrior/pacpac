# Cookie-pocalypse

This is Pac-Man from a parallel universe.

![CookiePocalypse Title](https://raw.github.com/greebowarrior/pacpac/master/pacpac/img/Cookie-pocalypse-logo.png)

This version of the game is adapted from the original code written by [Tyler Neylon](https://github.com/tylerneylon/pacpac).

The game mechanics have been altered significantly:

- The dots are now cookies
- The ghosts can't kill you
- You can eat the ghosts at any time, if you can catch them
- The ghosts eat the cookies
- The game ends when all the cookies have been eaten

This version was developed as a client activation for dmexco 2019 as a fun way of illustrating the "death of the cookie" in ad-tech.

--

You need the [löve](http://love2d.org) game engine to play. The current code is written for löve
v11.2

The original code was written by  in under 24 hours as a challenge.

## How to install and run

1. Download and install [löve](http://love2d.org). (Current code has been tested with löve v11.3)
2. Clone this repo, or download and unzip the [latest zipfile](https://github.com/greebowarrior/pacpac/archive/master.zip).
3. In a terminal, run `./make_lovefile.sh`
4. Double-click the file `pacpac.love`.
   Alternatively, in OS X and Ubuntu, type `love pacpac.love` from the command line - which assumes the `love` executable is in your path.

## Level Editing

I've set up the game so that you can make your own levels without having to know how to program.
Just edit `level1.txt` or any other `levelN.txt` file to change that level. The file format is
explained within those files, and this format is designed to be human-friendly and flexible.

If you're running PacPac using `pacpac.love`, then you need to run
`make_love_file.sh` before the level changes will show up in the game. This
shell script is meant to be run from the command line by cd'ing into your pacpac
directory (the one containing `make_love_file.sh`) and typing the command
`./make_love_file.sh`.


## Credits

This game uses the font 8bitoperator created by
[GrandChaos9000](http://grandchaos9000.deviantart.com/)
(aka Jayvee D. Enaguas) and is distributed under the
[CC-BY-SA](http://creativecommons.org/licenses/by-sa/2.0/) license.

Thanks to [jonfk](https://github.com/jonfk) for upgrading the code
for löve v0.9.2.
