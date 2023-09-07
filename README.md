# json: a package to handle json (read and write) for OpenComputers Minecraft Mod.

TAKEN From JSON4Lua, originally written for Lua 5.1.

JSON4Lua: JSON encoding / decoding support for the Lua language.
json Module.

Author: Craig Mason-Jones
Modified by: MiguelEXE
Homepage: http://json.luaforge.net/
Version: 0.9.40
This module is released under the MIT License (MIT).

```
torch-rocks install json
```

## Usage:

This module exposes 4 functions:

```
json_string = encode(o)
-- returns the table / string / boolean / number / nil / json.null value as a JSON-encoded string.

o = decode(json_string)
-- returns a Lua object populated with the data encoded in the JSON string json_string.

save(json_file, o)
-- saves the table / string / boolean / number / nil / json.null value as a JSON-encoded file.

o = load(json_file)
-- returns a Lua object populated with the data encoded in the JSON file.
```
