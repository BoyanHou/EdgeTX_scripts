# These are custom lua scripts to be used with EdgeTX

## Compatible with EdgeTX 2.9 and later 
### Scripts
- intCrf.lua: upon called, set internal module to crossfire
- intOff.lua: upon called, set internal module to OFF (you may want to do this to save battery, e.g. when the radio is used for simulator)
### Notes
- thanks @alteman who fixed the lua C implementation of `luaModelSetModule()` [in this commit](https://github.com/EdgeTX/edgetx/pull/3699) -- this enables using lua script to set internal/external module
