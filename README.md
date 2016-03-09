# Example Python package

The project folder (the one containing `play_game.py` and this `README`
file) is not a Python package. Inside of the project folder, we have a
`game` folder. Since `game` contains a file named `__init__.py`, it is
a Python package. If you are in the project folder and you run
`play_game.py`, you'll see that Python is able to find the `game`
package and import functions from the `rooms` and `players` modules
successfully.

If `play_game.py` Was inside the `games` folder this wouldn't work
because Python doesn't take kindly to running standalone scripts
that are part of a package.

To use this pattern on your own - put all of your library code inside
the package(s) you want to use and add them as subdirectories of the
project. Leave the script you actually run to play the game in the
project folder itself.

-Chuck
