# ExoClient files

Files the ExoClient launcher downloads when a player clicks Play.

| File | What it is |
|---|---|
| `distribution.json` | Tells the launcher which Minecraft, Forge and mods to install. Created with `tools/make-distribution.js` in the launcher project. |
| `mods/exoclient-1.0.0.jar` | The ExoClient mod. |
| `news.xml` | The news shown in the launcher. Add a new `<item>` at the top to post news. |
| `capes.json` | Players who get the ExoClient cape. Add `"<minecraft-uuid>": "exo"` entries. |
| `icon.png` | Icon shown in the launcher's server list. |
