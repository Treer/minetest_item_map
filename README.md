Copy mtrecipe.lua to builtin/games

Add:

  dofile(gamepath .. "mtrecipe.lua")

to the end of builtin/games/init.lua

Run Minetest

This should create a `itemsgraph.json` file in the world directory. Copy the content of `itemsgraph.json` to elements in code.js in the cryptoscape initialiser.

License: LGPL 3.
