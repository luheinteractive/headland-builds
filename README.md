# Headland builds

Public build pipeline for [Headland](https://github.com/luheinteractive) (the game's source is private): it exports the
game with the Apogee Engine's editor and template from [apogeeengine/builds](https://github.com/apogeeengine/builds).

The game's project is in the Apogee Engine's XML formats (`project.xml`, `export_presets.xml`): a tag from before that needs
an `engine_release` from before it too, and `presets_from_main` takes `export_presets.xml`, so it only works for a tag
on the same side of the change as main.
