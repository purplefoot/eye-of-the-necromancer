Eye of the Necromancer
======================
*Eye of the Necromancer* is an old school adventure game in the dungeon crawl mode.
It was written in 1985 (when I was 14/15) on a ZX Spectrum using Gilsoft's Quill adventure writing
system, but in style it is heavily influenced by the Cambridge Phoenix mainframe games,
ports of which (notably *Philosopher's Quest* and *Castle of Riddles*, derived from
*Brand X* on Phoenix) were available for the BBC Micro.

This project ports the game, mostly unchanged, except for the most egregious errors and
lapses of taste, to the Inform 6 language, by Graham Nelson.

Building the game
-----------------
I have been using the newer Inform 7 development environment, so the project folder
is organised appropriately. To build a working version:

1. Clone the project
2. Rename the `Eye of the Necromancer.inform` folder to something else
3. Use Inform 7 to create a new `Eye of the Necromancer.inform` project in the same location
4. Copy the story file (`renamed_project.inform/Source/main.inf`) to the newly created project: `Eye of the Necromancer.inform/Source/main.inf`
5. Copy `uuid.txt` from the renamed project folder to the newly created one.
6. Delete the renamed folder

Alternatively, you can simply compile the `main.inf` file with a standalone Inform 6 compiler.

Original game
-------------
The materials folder contains snapshots of the original Spectrum version. There are
3 parts and a saved game is required to move between them. They should work correctly
with most emulator packages. There are also text files containing Quill database dumps
of each part.

License
-------
The game is licensed under the Creative Commons Attribution - Non-Commercial - Share-Alike 2.0 license.
See the `LICENSE` file for more details.