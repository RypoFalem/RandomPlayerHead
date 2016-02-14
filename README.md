# RandomPlayerHead
Spawn random (or optionally specific) player heads from your own list of heads

Heads not included! Put them in a directory named "heads" in your plugin's data folder. It should contain a list of .yml files with the following structure:

heads:
- Name: 'Name of your head'
  Id: 'UUID of your head'
  Texture: The texture string, 'SkullOwner.Properties.textures.Value from the original data tag'
- And so on and so forth.

Heads will be loaded when the plugin is enabled or you type '/rph -reload'.