# ShoeBox Spritesheet Importer

This is a plugin for [Godot Engine](https://godotengine.org) to import
a spritesheet from [ShoeBox](http://renderhjs.net/shoebox/) or SpriteSheet Packer(https://amakaseev.github.io/sprite-sheet-packer/)as multiple `AtlasTexture`s.

**Note: This is compatible only with Godot 3.0 or later.**


## Installation

Simply download it from [Godot Asset Library](https://godotengine.org/asset-library/asset/169)

Alternatively, download or clone this repository and copy the contents of the
`addons` folder to your own project's `addons` folder.

Important: Enable the plugin on the Project Settings.

## Features

* Import sprite sheets as AtlasTextures

## Usage (once the plugin is enabled)
1. Select and apply the pixi.js template in ShoeBox's Spritesheet settings then save the spritesheet.
2. Copy the 2 generated files (.png and .js or .json) to your project folder
3. Watch Godot import it automatically.

## License

[MIT License](LICENSE). Copyright (c) 2018 Andreas Loew / CodeAndWeb GmbH
