## MonoGame.Aseprite Samples

In this repository you can find the following sample projects to show the [MonoGame.Aseprite](https://github.com/aristurtledev/monogame-aseprite) library in use.

Full documentation on [MonoGame.Aseprite](https://github.com/aristurtledev/monogame-aseprite) can be found at the website https://monogameaseprite.net

## Custom Processing Example

[link to example ](./source/CustomProcessingExample/)

This example demonstrates how you can utilize the [MonoGame.Aseprite](https://github.com/aristurtledev/monogame-aseprite) library to perform preprocessing of your Aseprite file to prepare assets for your game when not using the MGCB Editor. This example uses a console application to preprocess the content, but is meant to demonstrate how youc an use it in whatever custom processing workflow you might have. As long as you can reference the [MonoGame.Aseprite](https://github.com/aristurtledev/monogame-aseprite) library to make the calls, you can preprocess the content.

## Content Pipeline Example

[link to example](./source/ContentPipelineExample/)

This example demonstrates how to use the MGCB Editor to import the Aseprite file. This also show the use of a `nuget.config` file to make the NuGet packages download to a local folder within the project so that the reference added to the MGCB Editor doesn't break if the project directory ever changes.

## Processor Examples

In the [/source/ProcessorExamples/](./source/ProcessorExamples/) directory you can find multiple projects that demonstrate how to use the built-in processors to process the Aseprite file as one of the built-in content types.

### Animated Tilemap Processor Example

The [/source/ProcessorExamples/AnimatedTilemapProcess](./source/ProcessorExamples/AnimatedTilemapProcessor/) example demonstrates how to use the [AnimatedTilemapProcessor](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Content/Processors/AnimatedTilemapProcessor/) to process the Aseprite file as an [AnimatedTilemap](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Tilemaps/AnimatedTilemap/).

> ❕Animated Tilemaps are only available for Aseprite files created with Aseprite version >= 1.3-beta21

### Sprite Processor Example

The [/source/ProcessorExamples/SpriteProcessor](./source/ProcessorExamples/SpriteProcessor/) example demonstrates how to use the [SpriteProcessor](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Content/Processors/SpriteProcessor/) to process a single frame from the Aseprite file as a [Sprite](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Sprites/Sprite/).

### SpriteSheet Processor Example

The [/source/ProcessorExamples/SpriteSheetProcessor](./source/ProcessorExamples/SpriteSheetProcessor/) example demonstrates how to use the [SpriteSheetProcessor](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Content/Processors/SpriteSheetProcessor/) to process the Aseprite file as a [SpriteSheet](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Sprites/SpriteSheet/), which can then be used to create [AnimatedSprite](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Sprites/AnimatedSprite/) instances based on the Tags from your Aseprite file.

### TextureAtlas Processor Example

The [/source/ProcessorExamples/TextureAtlasProcessor](./source/ProcessorExamples/TextureAtlasProcessor/) example demonstrates how to use the [TextureAtlasProcessor](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Content/Processors/TextureAtlasProcessor/) to process the Aseprite file as a [TextureAtlas](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Sprites/TextureAtlas/), which can then be used to create [Sprite](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Sprites/SPrite/) instances.

### Tilemap Processor Example

The [/source/ProcessorExamples/TilemapProcessor](./source/ProcessorExamples/TilemapProcessor/) example demonstrates how to use the [TilemapProcessor](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Content/Processors/TilemapProcessor/) to process a single frame from the Aseprite file as a [Tilemap](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Tilemaps/Tilemap/).

> ❕Tilemaps are only available for Aseprite files created with Aseprite version >= 1.3-beta21

### Tilemap Processor Example

The [/source/ProcessorExamples/TilesetProcessor](./source/ProcessorExamples/TilesetProcessor/) example demonstrates how to use the [TilesetProcessor](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Content/Processors/TilesetProcessor/) to process a tileset the Aseprite file as a [Tileset](https://monogameaseprite.net/docs/api/MonoGame.Aseprite/Tilemaps/Tileset/).

> ❕Tilesets are only available for Aseprite files created with Aseprite version >= 1.3-beta21
