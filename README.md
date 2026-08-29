<div align="center"><a href="https://haxe.org/"><img src="images/haxe-logo.png" width="500"></a></div>

# Awesome Haxe Game Development with stars

A curated list of game development resources for **[Haxe 4](https://haxe.org/)**, a high level strictly typed programming language which is used to produce cross-platform native code.

Feel free to update it.

## Contents

* [Game engines](#game-engines)
* [Low-level Engine](#low-level-engine)
* [Physics](#physics)
* [Architecture](#architecture)
* [Networking](#networking)
* [Serialization and storage](#serialization-and-storage)
* [Games](#games)
* [Miscellaneous](#miscellaneous)
* [Articles](#articles)
* [Other haxe lists](#other-haxe-lists)

## Game engines

Those are Haxe 4 compatible game engines

* [Heaps](https://github.com/HeapsIO/heaps) ⭐ 3,498 | 🐛 183 | 🌐 Haxe | 📅 2026-08-27 - High Performance Game Framework (`Web`, `Mobile`, `Desktop`, `Consoles`).
* [Armory (Kha)](https://github.com/armory3d/armory) ⭐ 3,318 | 🐛 396 | 🌐 C++ | 📅 2026-07-16 - An open-source 3D game engine with full Blender integration (`Web`, `Mobile`, `Desktop`, `Consoles`).
* [HaxeFlixel (OpenFL)](https://github.com/HaxeFlixel/flixel) ⭐ 2,196 | 🐛 303 | 🌐 Haxe | 📅 2026-08-23 - Free, cross-platform 2D game engine powered by OpenFL (`Web`, `Mobile`, `Desktop`, `Consoles`).
* [OpenFL](https://github.com/openfl/openfl) ⭐ 2,152 | 🐛 338 | 🌐 Haxe | 📅 2026-08-24 - Interactive game and app development library (`Web`, `Mobile`, `Desktop`, `Consoles`).
* [unreal.hx](https://github.com/proletariatgames/unreal.hx) ⭐ 429 | 🐛 46 | 🌐 Haxe | 📅 2023-01-10 - Haxe Integration for Unreal (`Web`, `Mobile`, `Desktop`, `Consoles`).
* [ceramic](https://github.com/ceramic-engine/ceramic) ⭐ 353 | 🐛 30 | 🌐 Haxe | 📅 2026-08-29 - Cross-platform 2D framework (`Web`, `Mobile`, `Desktop`, `Unity`).
* [Starling](https://github.com/openfl/starling) ⭐ 268 | 🐛 17 | 🌐 Haxe | 📅 2026-07-21 - The "Cross-Platform Game Engine", a popular Stage3D framework (`Web`, `Mobile`, `Desktop`).
* [HxGodot (Godot 4.0)](https://github.com/HxGodot/hxgodot) ⚠️ Archived - A Haxe GDExtension for Godot 4 (`Web`, `Mobile`, `Desktop`, `Consoles`).
* [hxdefold](https://github.com/hxdefold/hxdefold) ⭐ 233 | 🐛 9 | 🌐 Haxe | 📅 2025-11-17 - Haxe/Lua externs for Defold game engine (`Web`, `Mobile`, `Desktop`).
* [Away3D](https://github.com/openfl/away3d) ⭐ 228 | 🐛 28 | 🌐 Haxe | 📅 2026-07-27 - An open source, real-time 3D engine for OpenFL (`Web`, `Mobile`, `Desktop`).
* [Stencyl (OpenFL)](https://github.com/Stencyl/stencyl-engine) ⭐ 215 | 🐛 6 | 🌐 Haxe | 📅 2026-08-04 - Create Flash, HTML5, iOS, Android, and desktop games with no code (`Mobile`, `Desktop`).
* [Haxegon (OpenFL)](https://github.com/haxegon/haxegon) ⭐ 197 | 🐛 78 | 🌐 Haxe | 📅 2022-10-12 - A programming library for beginners. Powered by OpenFL and Starling (`Web`, `Mobile`, `Desktop`, `Consoles`).

## Low-level Engine

* [Kha](https://github.com/Kode/Kha) ⭐ 1,632 | 🐛 145 | 🌐 C | 📅 2026-08-10 - Ultra-portable, high performance, open source multimedia framework (`Web`, `Mobile`, `Desktop`, `Consoles`).
* [Lime](https://github.com/openfl/lime) ⭐ 847 | 🐛 213 | 🌐 JavaScript | 📅 2026-08-28 - A flexible, lightweight layer for Haxe cross-platform developers (`Web`, `Mobile`, `Desktop`).
* [NME](https://github.com/haxenme/nme) ⭐ 496 | 🐛 44 | 🌐 C | 📅 2026-08-08 - A cross-platform native backend (`Web`, `Mobile`, `Desktop`).
* [linc\_glfw](https://github.com/Sunjammer/linc_glfw) ⭐ 17 | 🐛 0 | 🌐 C | 📅 2019-09-16 - Desktop - GLFW binding (multi-platform library for OpenGL, OpenGL ES and Vulkan) *(Desktop)*.
* [3DSHaxe](https://github.com/Krismowo/3DSHaxe) - Make 3ds homebrew! (`3DS`).

## Physics

* [echo](https://github.com/AustinEast/echo/) ⭐ 153 | 🐛 8 | 🌐 Haxe | 📅 2026-05-12 - Simple Physics Library.
* [haxebullet](https://github.com/armory3d/haxebullet) ⚠️ Archived - Bullet 3D Physics.
* [nape-haxe4](https://github.com/HaxeFlixel/nape-haxe4) ⭐ 52 | 🐛 0 | 🌐 Haxe | 📅 2020-06-30 - Physics Engine (the original Haxe3 version of nape can be found [here](https://github.com/deltaluca/nape) ⭐ 554 | 🐛 16 | 🌐 Haxe | 📅 2018-09-09).

## Architecture

```
IoC == Inversion of Control  
EC == Entity Component  
ECS == Entity-Component-System
FSM == Finite State Machine
MVC == Model View Controller
```

* [awe6](https://github.com/hypersurge/awe6) ⭐ 80 | 🐛 1 | 🌐 Haxe | 📅 2024-10-30 - `IoC`, `EC` - The inverted game framework, is a development tool focused on Future Proofing.
* [ecx](https://github.com/eliasku/ecx) ⚠️ Archived - `ECS` - An Entity Component System framework.
* [OSIS](https://github.com/Dvergar/OSIS) ⭐ 46 | 🐛 1 | 🌐 Haxe | 📅 2019-11-17 - `ECS` - Entity Component System architecture with networking support.
* [hexMachina](https://github.com/DoclerLabs/hexCore) ⭐ 6 | 🐛 1 | 🌐 Haxe | 📅 2024-05-03 - `MVC` - A powerful multi-modular MVC framework.

## Networking

* [hxWebSockets](https://github.com/ianharrigan/hxWebSockets) ⭐ 94 | 🐛 14 | 🌐 Haxe | 📅 2025-05-11 - Websockets for all platforms.
* [colyseus-hx](https://github.com/colyseus/colyseus-hx) ⭐ 90 | 🐛 2 | 🌐 Haxe | 📅 2026-08-28 - Multiplayer Game Client.
* [Anette](https://github.com/Dvergar/Anette) ⭐ 36 | 🐛 3 | 🌐 Haxe | 📅 2019-11-18 - Simple network library (no UDP).
* [haxe-simple-peer (js)](https://github.com/melonin/haxe-simple-peer) ⭐ 4 | 🐛 0 | 🌐 Haxe | 📅 2019-01-31 - Haxe externs for simple-peer.
* Built-in - Heaps, OpenFL (HaxeFlixel & co), Kha (Armory).

## Serialization and storage

* [CastleDB](https://github.com/ncannasse/castle) ⭐ 607 | 🐛 58 | 🌐 Haxe | 📅 2026-08-27 - A structured static database easing collaboration.
* [hxbit](https://github.com/ncannasse/hxbit) ⭐ 166 | 🐛 11 | 🌐 Haxe | 📅 2026-08-26 - A binary serialization and network synchronization library.
* [Bits](https://github.com/RealyUniqueName/Bits) ⭐ 23 | 🐛 0 | 🌐 Haxe | 📅 2019-02-28 - Binary bit flags with unlimited amount of bits.
* [PODStream](https://github.com/Dvergar/PODStream) ⭐ 21 | 🐛 0 | 🌐 Haxe | 📅 2019-11-01 - Plain Old Data serializer.

<!--lint disable awesome-list-item-->

## Games

* [Darksburg](https://store.steampowered.com/app/939100/Darksburg/) - Heaps - `Desktop`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/darksburg.jpg)
* [Dead Cells](https://dead-cells.com/) - Heaps - `Desktop`, `Consoles`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/dead-cells.jpg)
* [Defender's Quest](http://www.defendersquest.com/) - HaxeFlixel (OpenFL) - `Desktop`, `Consoles`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/defenders-quest.jpg)
* [Defender's Quest 2](https://store.steampowered.com/app/252190/Defenders_Quest_2_Mists_of_Ruin/) - HaxeFlixel (OpenFL) - `Desktop`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/defenders-quest-2.jpg)
* [Dicey Dungeons](http://diceydungeons.com/) - Haxegon (OpenFL) - `Desktop`, `Consoles`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/dicey-dungeons.jpg)
* [Evoland](http://evoland.shirogames.com/) - Heaps - `Desktop`, `Mobile`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/evoland.jpg)
* [Northgard](http://northgard.net/) - Heaps - `Desktop`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/northgard.jpg)
* [Papers, Please](http://papersplea.se/) - OpenFL - `Desktop`, `iOS`, `PsVita`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/papers-please.jpg)
* [Pocket Kingdom](https://store.steampowered.com/app/462620/Pocket_Kingdom/) - HaxePunk (OpenFL)- `Desktop`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/pocket-kingdom.jpg)
* [rymdkapsel](https://rymdkapsel.com/) - OpenFL - `Desktop`, `Mobile`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/rymdkapsel.jpg)
* [Spellbreak](https://playspellbreak.com/) - unreal.hx -  `PC`, `PS`, `Xbox`, `Switch`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/spellbreak.jpg)
* [The Westport Independent](http://www.doublezeroonezero.com/westport.html) - Luxe - `Desktop`, `Mobile`.
  * ![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/main/images/westport-independent.jpg)

<!--lint enable-->

More showcase :

* [Kha showcase](https://github.com/Kode/Kha/wiki/Games-Built-With-Kha) ⭐ 1,632 | 🐛 145 | 🌐 C | 📅 2026-08-10
* [Flambe showcase](https://github.com/aduros/flambe/wiki/Showcase) ⭐ 752 | 🐛 119 | 🌐 Haxe | 📅 2021-04-16
* [OpenFL showcase](https://www.openfl.org/showcase)
* [HaxeFlixel showcase](https://haxeflixel.com/showcase/)
* [itch.io showcase](https://itch.io/games/made-with-haxe)
* [HaxePunk showcase](https://haxepunk.com/games/)

## Miscellaneous

### 3rd party API

* [SteamWrap](https://github.com/larsiusprime/SteamWrap) ⭐ 113 | 🐛 16 | 🌐 Haxe | 📅 2023-09-20 - Native extension for the SteamAPI.
* [hxgamejolt-api](https://github.com/MAJigsaw77/hxgamejolt-api) ⭐ 24 | 🐛 0 | 🌐 Haxe | 📅 2026-06-26 - Haxe bindings for GameJolt API.
* [newgrounds](https://lib.haxe.org/p/newgrounds) - Newgrounds API.

### AI

[goap](https://gitlab.com/haath/goap) - Goal-oriented action planner for AI.

### Animation

* [spine-hx](https://github.com/jeremyfa/spine-hx) ⭐ 61 | 🐛 13 | 🌐 Haxe | 📅 2024-01-30 - Spine runtime automatically converted from the official Java/libgdx runtime.
* [heaps-aseprite](https://github.com/AustinEast/heaps-aseprite) ⭐ 36 | 🐛 2 | 🌐 Haxe | 📅 2024-01-26 - Load and render sprites and animations in Aseprite format.
* [flxgif](https://github.com/MAJigsaw77/flxgif) ⭐ 27 | 🐛 0 | 🌐 Haxe | 📅 2025-04-12 - Yagp's Gif Player for HaxeFlixel.
* [ase](https://github.com/miriti/ase) ⭐ 23 | 🐛 1 | 🌐 Haxe | 📅 2025-07-17 - File format reader/writer for .ase/.aseprite without external dependencies.
* [Heaps-Spine](https://github.com/Beeblerox/Heaps-Spine) ⭐ 20 | 🐛 3 | 🌐 Haxe | 📅 2019-03-20 - Spine player for heaps.
* [openfl-aseprite](https://github.com/miriti/openfl-aseprite) ⭐ 19 | 🐛 0 | 🌐 Haxe | 📅 2021-06-14 - Load and render sprites and animations in Aseprite format.
* [openfl-spine](https://github.com/rainyt/openfl-spine) ⭐ 18 | 🐛 2 | 🌐 Haxe | 📅 2026-02-09 - Render Spine animation in the OpenFL engine, rendering processing can be achieved throughSprite and Tilemap.
* HaxeFlixel - Spine parser.

### Audio

* [sfxr-hx](https://github.com/jobf/sfxr-hx) ⭐ 5 | 🐛 0 | 🌐 Haxe | 📅 2023-05-12 - Pure haxe implementation of Sfxr.

### Color manipulation

* [nxColor](https://github.com/oscarcs/nxColor) ⭐ 39 | 🐛 0 | 🌐 Haxe | 📅 2017-05-24 - Color manipulation library.

### Collision

* [differ](https://github.com/snowkit/differ) ⭐ 166 | 🐛 2 | 🌐 Haxe | 📅 2020-05-08 - A separation axis theorem collision library.

### Computer Vision

* [Vision](https://github.com/ShaharMS/Vision) ⭐ 35 | 🐛 6 | 🌐 Haxe | 📅 2026-06-06 - Cross platform computer vision library.

### Data structures

* [polygonal-ds](https://github.com/polygonal/ds) ⭐ 349 | 🐛 17 | 🌐 Haxe | 📅 2023-01-22 - Data structures for games.

### Dialogues

* [hxyarn](https://github.com/cxsquared/hxyarn) ⭐ 6 | 🐛 1 | 🌐 Haxe | 📅 2026-07-06 - Parser and runner for Yarn dialogue files.

### Editor

* [flixel-studio](https://github.com/Dovyski/flixel-studio) ⭐ 111 | 🐛 9 | 🌐 Haxe | 📅 2023-01-02 - In-game editor for HaxeFlixel.

### Helpers

* [deepnightLibs](https://github.com/deepnight/deepnightLibs) ⭐ 272 | 🐛 4 | 🌐 Haxe | 📅 2026-08-11 - General gamedev purpose libs.

### Localization

* [firetongue](https://github.com/larsiusprime/firetongue) ⭐ 149 | 🐛 12 | 🌐 Haxe | 📅 2024-01-11 - A translation/localization framework.

### Map parser

* [LEd](https://github.com/deepnight/led-haxe-api) ⭐ 103 | 🐛 16 | 🌐 Haxe | 📅 2026-04-23 - 2D level editor with a typed compile time loader.
* [PyxelEdit Map Importer](https://github.com/Dvergar/PyxelEdit-Map-Importer) ⭐ 34 | 🐛 1 | 🌐 Haxe | 📅 2019-11-17 - Parser for maps generated by the editor PyxelEdit.
* [TiledHX](https://github.com/yanrishatum/tiledhx) ⭐ 13 | 🐛 1 | 🌐 Haxe | 📅 2024-06-24 - A comprehensive modern Tiled parser.
* Heaps - Built-in parser for Tiled.
* HaxeFlixel - Parser for Tiled & Ogmo.

### Math helpers

* [hxmath](https://github.com/tbrosman/hxmath) ⭐ 92 | 🐛 10 | 🌐 Haxe | 📅 2023-02-10 - A game-oriented math library.
* [haxe-glm](https://github.com/hamaluik/haxe-glm) ⭐ 48 | 🐛 1 | 🌐 Haxe | 📅 2017-11-07 - A toolset for using 2, 3, and 4 dimensional vectors and matrices, as well as quaternions.
* [hx-vector2d](https://github.com/markknol/hx-vector2d) ⭐ 13 | 🐛 0 | 🌐 Haxe | 📅 2019-12-13 - Worlds most complete Vector2d / Point class. With operator overloading.

### Modding

* [polymod](https://github.com/larsiusprime/polymod) ⭐ 210 | 🐛 49 | 🌐 Haxe | 📅 2026-08-28 - An atomic modding framework for games/apps.

### Particles

* [Sparkler](https://github.com/RudenkoArts/sparkler) ⭐ 18 | 🐛 2 | 🌐 Haxe | 📅 2025-04-27 - Modular Particle System.

### Monetization

* [extension-iap](https://github.com/charmdev/extension-iap) ⭐ 9 | 🐛 0 | 🌐 Haxe | 📅 2025-07-28 - Provides an access to in-app purchases (iOS) and in-app billing (Android) for OpenFL projects using a common API. Fork of [this](https://github.com/HaxeExtension/extension-iap) ⭐ 71 | 🐛 6 | 🌐 Haxe | 📅 2026-03-26.

### Pathfinding

* [pathfinder](https://github.com/hypersurge/pathfinder) ⭐ 29 | 🐛 0 | 🌐 Haxe | 📅 2016-08-15 - Easy A\* pathfinding algorithm.
* [astar](https://gitlab.com/haath/astar) - Versatile framework-agnostic A-star solver Library.

### Procedural generation

* [Dungeon builder](https://github.com/julsam/dungeon-builder) ⭐ 66 | 🐛 0 | 🌐 Haxe | 📅 2014-04-10 - A set of dungeon generation algorithm (works w/ hx4 w/ minor changes).

### Shaders

* [HGSL](https://github.com/saharan/HGSL) ⭐ 156 | 🐛 4 | 🌐 Haxe | 📅 2023-11-19 - Haxe to GL Shading Language.
* [parasol](https://github.com/47rooks/parasol) ⭐ 23 | 🐛 0 | 🌐 Haxe | 📅 2023-11-28 - HaxeFlixel library of shaders.

### Sprite

* [haxe-aseprite](https://github.com/PongoEngine/haxe-aseprite) ⭐ 24 | 🐛 0 | 🌐 Haxe | 📅 2019-10-07 - Parser for .ase and .aseprite files.

### Texture Packer

* [hxpk](https://github.com/bendmorris/hxpk) ⭐ 46 | 🐛 1 | 🌐 Haxe | 📅 2019-01-30 - Port of the libGDX Texture Packer.

### Tweening

* [actuate](https://github.com/jgranick/actuate) ⭐ 162 | 🐛 38 | 🌐 Haxe | 📅 2026-03-17 - A flexible, fast "tween" library.
* [TweenX/TweenXCore](https://github.com/shohei909/tweenx) ⭐ 94 | 🐛 8 | 🌐 JavaScript | 📅 2023-12-31 - Tween library.
* [YATL](https://github.com/Yanrishatum/yatl) ⭐ 16 | 🐛 0 | 🌐 Haxe | 📅 2019-01-19 - Yet Another (Haxe) Tweening Library.

### UI

* [flixel-ui](https://github.com/HaxeFlixel/flixel-ui) ⭐ 196 | 🐛 55 | 🌐 Haxe | 📅 2026-07-14 - GUI library for HaxeFlixel.
* [domkit](https://github.com/ncannasse/domkit) ⭐ 94 | 🐛 13 | 🌐 Haxe | 📅 2026-06-02 - CSS Components based strictly typed UI framework.
* [HaxeUI](http://haxeui.org/) - UI library with multiple framework backends (HTML5, Kha, OpenFL, PixiJS, WxWidgets, and a number of others as works in progress).
* [Feathers UI](https://feathersui.com/) - Cross-platform graphical user interface components for creative frontend projects.

### Video

* [hxCodec](https://github.com/polybiusproxy/hxCodec) ⭐ 113 | 🐛 8 | 🌐 C | 📅 2024-05-11 - Adds native video playback on HaxeFlixel and OpenFL.

## Articles

* [Flash is dead, long live OpenFL!](http://gamasutra.com/blogs/LarsDoucet/20140318/213407/Flash_is_dead_long_live_OpenFL.php)
* [Flash is gone, what now?](https://www.linkedin.com/pulse/flash-gone-what-now-matan-uberstein/)
* [How I wrote my own 3D game engine and shipped a game with it in 20 months](https://kircode.com/post/how-i-wrote-my-own-3d-game-engine-and-shipped-a-game-with-it-in-20-months)
* [Building 42 games within a year — Insane game development](https://medium.com/@mknol/building-42-games-within-a-year-insane-game-development-5340d506068f)
* [Porting to console via Unity](https://do-games.com/blog/the-adventure-pals-console-tech-part1)

## Other haxe lists

* [awesome snowkit](https://github.com/anissen/awesome-snowkit) ⭐ 117 | 🐛 0 | 📅 2021-04-09
* [awesome haxe](https://github.com/nadako/awesome-haxe) ⚠️ Archived
* [awesome haxe js](https://github.com/MatthijsKamstra/awesome-haxe-js) ⭐ 30 | 🐛 0 | 📅 2018-02-23

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
