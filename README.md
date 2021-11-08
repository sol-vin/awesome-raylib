# Awesome raylib

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated list of awesome stuff for [raylib](https://raylib.com), Simple and easy-to-use library to enjoy videogames programming.

## List

- [Gists](#gists)
- [Homebrew Ports](#homebrew-ports)
- [Libraries and Frameworks](#libraries-and-frameworks)
- [Softwares](#softwares)
- [Bindings](https://github.com/raysan5/raylib/blob/master/BINDINGS.md)
- [Deprecated/Removed/Unknown bindings](#deprecatedremovedunknown-bindings)
- [Libraries bindings/ports](#libraries-bindingsports)
- [Platforms supported by raylib](https://github.com/raysan5/raylib#building-raylib-on-multiple-platforms)
- [Tutorials](#tutorials)
- [Community Examples](#community-examples)
- [Templates](#templates)
- [Articles](#articles)
- [Videos](#videos)
- [What raylib uses?](https://github.com/raysan5/raylib/wiki/raylib-dependencies)
- [Promo Images](#promo-images)
- [Logos](#logos)
- [Stickers](#stickers)
- [Resources and Links](#resources-and-links)

### Gists

| Name                                                                                                                   | Description                                                                                                |
|------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| [ohmree/sort.c](https://gist.github.com/ohmree/dac78b36b736a71dc9a423d10b9509cc)                                       | C Sorting example that uses raylib.                                                                        |
| [satinxs/bleed.c](https://gist.github.com/satinxs/e55461da74ba378a09d813cb6767ffae)                                    | Bleed bug when drawing rectangles with raylib.                                                             |
| [masterex1000/agui.h](https://gist.github.com/masterex1000/92c861eeef03e761d0addc6edc0b741f)                           | Small UI helper library intended to be used with raylib.                                                   |
| [SamyBencherif/rpmd.c](https://gist.github.com/SamyBencherif/00412fa24b411c07ad57176e64793fb5)                         | Pixelated 2D lighting with shadows in raylib, software accelerated.                                        |
| [Goodguyr/client_GUI.c](https://gist.github.com/Goodguyr/284a262dc95ab0a35b498115c1cb3d41)                             | raylib example of networking, Drawing circles for each player.                                             |
| [JeffM2501/pan.c](https://gist.github.com/JeffM2501/3c7da5c2b7e078e254d673f91489c78f)                                  | raylib example of mouse drag panning for 2D camera.                                                        |
| [Demizdor/noisepl.c](https://gist.github.com/Demizdor/e916ba765336c389af4ecd2c557a6be6)                                | Noise Planets example made with raylib.                                                                    |
| [Pikachuxxxx/RayCollisions.c](https://gist.github.com/Pikachuxxxx/0dda4b70bf71b794b08923df34961844)                    | Function to Detect Collisions Between a Ray and a Rectangle and Dynamic Rectangle and a Rectangle.         |
| [mattj1/raylib_dpi_hack.c](https://gist.github.com/mattj1/606a94527badb6ffa7d22245c9b745b1)                            | Function to get window DPI.                                                                                |
| [Rabios/DrawTexturePro3D.c](https://gist.github.com/Rabios/ccbb08d7ff4f41af19d53bf02d803815)                           | Draw 2D texture with raylib in 3D space!                                                                   |
| [TheLumaio/raynames.h](https://gist.github.com/TheLumaio/403caefa3bd1eae3b8e265e79d6508ad)                             | Header that provides lowercase name aliases for types and functions of raylib, raymath, easings, And rnet. |
| [AregevDev/raylibvectors.c](https://gist.github.com/AregevDev/737d14ce64be059ed2b6d0d973361985)                        | raylib example for 2D Vectors.                                                                             |
| [EdwardDowling/maze.c](https://gist.github.com/EdwardDowling/01a872cca79e1404bbc2)                                     | Maze generation and raycasting example.                                                                    |
| [pluckyporcupine/core_2d_camera_c-mera.lisp](https://gist.github.com/pluckyporcupine/bbaa93b00e020c53faf27e5bde087374) | raylib core_2d_camera example ported to [C-Mera](https://github.com/kiselgra/c-mera)!                      |
| [JeffM2501/core_split_screen.c](https://gist.github.com/JeffM2501/85e3c3fa4c5296227ab91dd7d2dec471)                    | Simple splitscreen implemntation for raylib.                                                               |
| [JeffM2501/models_mesh_generation.c](https://gist.github.com/JeffM2501/18964218591e5aa302f17f0ae5a45b77)               | Example shows that Mesh generation of quad with UV repeats in raylib.                                      |
| [JeffM2501/imgui_docking_exmaple.cpp](https://gist.github.com/JeffM2501/4c3a7e8a85302f743f8bd9dc1aae00ae)              | Example of how to do editor style docking in ImGui for raylib.                                             |
| [JeffM2501/varfps.c](https://gist.github.com/JeffM2501/588d8b632d1bf49c7f010dde0a9dcbee)                               | raylib test showing how frame based motion can be problematic.                                             |
| [JeffM2501/raylib worldspace panning with rotation](https://gist.github.com/JeffM2501/703728379eb6e9d51d33201d1a1fe05d)| raylib example of worldspace panning with rotation.                                                        |
| [JeffM2501/raylib worldspace panning](https://gist.github.com/JeffM2501/edb5b8bbfd5a1744d4f97865ad4be989)              | raylib example of worldspace panning without rotation.                                                     |
| [JeffM2501/Model merge for raylib](https://gist.github.com/JeffM2501/08d20cdd931456ad0e52905401cc34af)                 | Example of model merge made with raylib.                                                                   |
| [JeffM2501/raylib resize fullscreen example](https://gist.github.com/JeffM2501/00cf5653f41337d8c9e8db40deb25656)       | raylib resize fullscreen example.                                                                          |
| [JeffM2501/orbitcamera.cpp](https://gist.github.com/JeffM2501/000787070aef421a00c02ae4cf799ea1)                        | Example of orbit camera made for raylib!                                                                   |
| [JeffM2501/RLAssets.cpp](https://gist.github.com/JeffM2501/bd1092ce0eaedd26fe3ca60e1743ce40)                           | Basic platform independent asset folder management for raylib.                                             |
| [JeffM2501/Basic Shot Animation raylib](https://gist.github.com/JeffM2501/a6eb14d734f88a065a73adb729eed1f7)            | Basic animation made with raylib.                                                                          |
| [JeffM2501/Basic entity game](https://gist.github.com/JeffM2501/a5987d2f4575e871f561197232ba0f60)                      | Entity example made with raylib.                                                                           |
| [JeffM2501/DrawTextureProZ](https://gist.github.com/JeffM2501/1c4c9c8048cbb19d11c9807518196b69)                        | Modified version of `DrawTexturePro` that adds Z Dimension/Depth!                                          |
| [JeffM2501/raylib fullscreen toggle example](https://gist.github.com/JeffM2501/6e4630a0e34c0c7dddf066f7192e342d)       | raylib fullscreen toggle example made with raylib.                                                         |

### Homebrew Ports

| Name                                                                                                                   | Description                                                                                                                                |
|------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| [orbisdev-orbisGl2](https://github.com/orbisdev/orbisdev-orbisGl2)                                                     | raylib port for PS4 that intended to be used as modern graphics backend, Examples are [here!](https://github.com/orbisdev/orbisGl2samples) |
| [psp2dev/raylib4Vita](https://github.com/psp2dev/raylib4Vita)                                                          | raylib port for PlayStation Vita.                                                                                                          |
| [Gota7/3ds-raylib](https://github.com/Gota7/3ds-raylib)                                                                | raylib port for Nintendo 3DS.                                                                                                              |

### Libraries and Frameworks

| Name                                                                                  | Description                                                                                                                                |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| [raysan5/raylib](https://github.com/raysan5/raylib)                                   | Simple and easy-to-use library to enjoy videogames programming.                                                                            |
| [SasLuca/rayfork](https://github.com/SasLuca/rayfork)                                 | Single header and source, cross-platform, allocator-aware, C99 game libraries.                                                             |
| [Rabios/rayport](https://github.com/Rabios/rayport)                                   | Awesome C99, Header-Only, rayfork wrapper for raylib!                                                                                      |
| [Rabios/rayutils](https://github.com/Rabios/rayutils)                                 | Single-Header library that extends raylib with some awesome functionality!                                                                 |
| [raysan5/raygui](https://github.com/raysan5/raygui)                                   | Simple and easy-to-use immediate-mode GUI library.                                                                                         |
| [victorfisac/Physac](https://github.com/victorfisac/Physac)                           | 2D physics header-only library for videogames developed in C using raylib library.                                                         |
| [raysan5/rpng](https://github.com/raysan5/rpng)                                       | Simple and easy-to-use library to manage png chunks.                                                                                       |
| [raysan5/rres](https://github.com/raysan5/rres)                                       | Simple and easy-to-use file-format to package resources.                                                                                   |
| [raysan5/raudio](https://github.com/raysan5/raudio)                                   | Simple and easy-to-use audio library based on miniaudio.                                                                                   |
| [firststef/ECSlib](https://github.com/firststef/ECSlib)                               | Library with ECS classes in C++ using raylib.                                                                                              |
| [osom8979/tbag](https://github.com/osom8979/tbag)                                     | Third party extension utility project.                                                                                                     |
| [oswjk/imgui-impl-raylib](https://github.com/oswjk/imgui-impl-raylib)                 | raylib backend for Dear ImGui.                                                                                                             |
| [haydenhigg/Libre](https://github.com/haydenhigg/Libre)                               | Crystal graphics library that is built on raylib.                                                                                          |
| [nezvers/GameSystemsInC](https://github.com/nezvers/GameSystemsInC)                   | TileMap & Sprite systems for raylib.                                                                                                       |
| [robloach/raylib-asprite](https://github.com/RobLoach/raylib-aseprite)                | Load [Aseprite](https://www.aseprite.org) files for animated sprites in raylib.                                                            |
| [raylib-nuklear](https://github.com/RobLoach/raylib-nuklear)                          | Nuklear immediate mode GUI for raylib.                                                                                                     |
| [zworld-apps/zgui](https://github.com/zworld-apps/zgui)                               | GUI system based on Constraints for raylib, Written in Go.                                                                                 |
| [Slixe/visual-go](https://github.com/Slixe/visual-go)                                 | Go Framework to create simple application using raylib & Flex.                                                                             |
| [basp1/rlyeh](https://github.com/basp1/rlyeh)                                         | Simple and easy-to-use GUI API library for raylib-go, Written in Go.                                                                       |
| [smthnspcl/raycons](https://github.com/smthnspcl/raycons)                             | Icons drawn by raylib, Written in C++.                                                                                                     |
| [smthnspcl/raygauge](https://github.com/smthnspcl/raygauge)                           | Simple gauges to display values with raylib, Written in C++.                                                                               |
| [dbriemann/libpartikel](https://github.com/dbriemann/libpartikel)                     | Simple particle system library made with and for raylib. Works as header only library.                                                     |
| [WEREMSOFT/spine-raylib-runtimes](https://github.com/WEREMSOFT/spine-raylib-runtimes) | raylib implementation of the C spine runtimes.                                                                                             |
| [WEREMSOFT/stl-loader-for-raylib](https://github.com/WEREMSOFT/stl-loader-for-raylib) | STL loader for raylib, Allows to load 3dPrinter file types into raylib.                                                                    |
| [TheLumaio/Raylib-GBuffers](https://github.com/TheLumaio/Raylib-GBuffers)             | GBuffer implementation for raylib.                                                                                                         |
| [tofuengine/tofu](https://github.com/tofuengine/tofu)                                 | Lightweight 2D framework with a lo-fi vibe, for fast game prototyping. Uses OpenGL through GLFW3. Scripted in Lua.                         |
| [Ferrohound/RaylibEX](https://github.com/Ferrohound/RaylibEX)                         | raylib Extra incorporates more basic functionality to raylib while keeping the hands-on aspect!                                            |
| [JusticeShultz/MathX](https://github.com/JusticeShultz/MathX)                         | Detailed custom math library programmed in C++ by Justice Shultz that includes demos that uses raylib.                                     |
| [LilySweetCat/RaylibCs-UI](https://github.com/LilySweetCat/RaylibCs-UI)               | Just a simple UI using raylib (Can be used as library), Written in C#.                                                                     |
| [QuantScientist/TorchRayLib](https://github.com/QuantScientist/TorchRayLib)           | CMake based integration of the raylib library with the Libtorch C++ Deep Learning Library.                                                 |
| [raylib-tmx](https://github.com/RobLoach/raylib-tmx)                                  | Load and draw [Tiled](https://www.mapeditor.org/) `.tmx` tile maps through the [TMX C Loader](https://github.com/baylej/tmx).              |
| [nbdy/ruicf](https://github.com/nbdy/ruicf)                                           | C++ raylib UI controls framework.                                                                                                          |
| [JeffM2501/RLGameGui](https://github.com/JeffM2501/RLGameGui)                         | Resolution independent GUI for raylib, Written in C++!                                                                                     |
| [jackcarey/raylib-extensions](https://github.com/jackcarey/raylib-extensions)         | Modifications/Additions to [raysan5/raylib](https://github.com/raysan5/raylib) and [raysan5/raygui](https://github.com/raysan5/raygui).    |
| [coolcoy12/RayLibUtils](https://github.com/coolcoy12/RayLibUtils)                     | Useful UI and effects for raylib for C++!                                                                                                  |
| [moonsteal/raylib-barebones](https://github.com/moonsteal/raylib-barebones)           | Stripped down version of raylib with Meson.                                                                                                |
| [Doy-lee/RaylibSIMD](https://github.com/Doy-lee/RaylibSIMD)                           | SIMD Implementation of raylib's API.                                                                                                       |
| [8bitPandaPlugins/RTAudioGameLib](https://github.com/8bitPandaPlugins/RTAudioGameLib) | C++ Game API built on raylib and RTaudio for latency critical implimentations.                                                             |
| [zzador/RayLib-Utilities](https://github.com/zzador/RayLib-Utilities)                 | Some utility & helper functions for raylib and raygui.                                                                                     |
| [jozanza/libraygun](https://github.com/jozanza/libraygun)                             | Utils for raylib.                                                                                                                          |
| [JeffM2501/raylibExtras](https://github.com/JeffM2501/raylibExtras)                   | C++ Utilities and common code for use with raylib.                                                                                         |
| [Ushio/raylibImGui](https://github.com/Ushio/raylibImGui)                             | C++ Dear ImGui integration for raylib.                                                                                                     |
| [nicholasimon/displayfx_raylib](https://github.com/nicholasimon/displayfx_raylib)     | Few effects to use on top of your game screen, scanlines, noise lines and pixel noise, written in Go.                                      |
| [JacobLondon/rlgutils](https://github.com/JacobLondon/rlgutils)                       | Golang utilities for raylib.                                                                                                               |
| [thyliverman/PaperSDL](https://github.com/thyliverman/PaperSDL)                       | Small software library, designed to make using raylib-cs simpler and more concise, Written in C#.                                          |
| [hbiblia/gtk-raylib](https://github.com/hbiblia/gtk-raylib)                           | GTK integration with raylib.                                                                                                               |
| [QuantScientist/ncnnRay](https://github.com/QuantScientist/ncnnRay)                   | CMake-based raylib and the very popular Tencent ncnn Deep Learning library integration, Depends on the Vulkan SDK.                         |
| [impzero/gastar](https://github.com/impzero/gastar)                                   | Algorithm implemented in Go visualized using raylib.                                                                                       |
| [RobLoach/raylib-physfs](https://github.com/RobLoach/raylib-physfs)                   | Provides integration with the virtual file system [PhysicsFS](https://www.icculus.org/physfs)                                              |
| [thyliverman/Paper](https://github.com/thyliverman/Paper)                             | C++ rewrite of PaperSDL, dedicated to making raylib just a little easier to work with.                                                     |
| [AliElSaleh/Animator-For-Raylib](https://github.com/AliElSaleh/Animator-For-Raylib)   | C/C++ Animator lib.                                                                                                                        |
| [LilySweetCat/RaylibCs-UI](https://github.com/LilySweetCat/RaylibCs-UI)               | Just a simple UI using raylib, Written in C#.                                                                                              |
| [JeffM2501/TestFrame](https://github.com/JeffM2501/TestFrame)                         | Test framework that uses raylib and ImGui together to help test and develop concept and uses C++ classes for windows and views.            |
| [c-krit/ferox](https://github.com/c-krit/ferox)                                       | A simple 2D rigid body physics engine written in C.                                                                                          |
| [ProfJski/RaylibOpOverloads](https://github.com/ProfJski/RaylibOpOverloads)           | C++ Operator Overloads for raylib.                                                                                                         |
| [electronstudio/rlzero](https://github.com/electronstudio/rlzero)                     | Simplified API for raylib to enable beginners to create 3D games, Inspired by Pygame Zero.                                                 | 
| [haxeui/haxeui-raylib](https://github.com/haxeui/haxeui-raylib)                       | raylib backend for HaxeUI.                                                                                                                 |
| [Not-Nik/rlobj](https://github.com/Not-Nik/rlobj)                                     | drop-in replacement for raylib's obj loader.                                                                                               |

### Softwares

| Name                                                                                                  | Description                                                                                                                                                          |
|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [gtrxAC/gxarch](https://github.com/gtrxAC/gxarch)                                                     | Simple fantasy computer architecture that uses raylib and NodeJS!                                                                                                    |
| [adct-the-experimenter/3d-audio-producer](https://github.com/adct-the-experimenter/3d-audio-producer) | Fork of the [adct-the-experimenter/binaural-audio-editor](https://github.com/adct-the-experimenter/binaural-audio-editor) that uses replaced with raygui and raylib. |
| [Lockna/chip8](https://github.com/Lockna/chip8)                                                       | Very basic CHIP-8 emulator that uses raylib for rendering.                                                                                                           |
| [skylersaleh/SkyBoy](https://github.com/skylersaleh/SkyBoy)                                           | Game Boy and Game Boy Color Emulator powered by raylib!                                                                                                              |
| [sparkskapil/2D-CAD-Raylib](https://github.com/sparkskapil/2D-CAD-Raylib)                             | 2D CAD viewer for raylib.                                                                                                                                            |
| [sorykkk/raygui_calculator](https://github.com/sorykkk/raygui_calculator)                             | Demonstrates simple and functional calculator gui written with raygui based on raylib library.                                                                       |
| [MarcMDE/FunWithEasings](https://github.com/MarcMDE/FunWithEasings)                                   | Small and simple Easings visualizing tool developed in C with raylib and C easings.                                                                                  |
| [Mudzii/SharedBuff](https://github.com/Mudzii/SharedBuff)                                             | Level editor using a shared buffer between an Maya API and raylib engine.                                                                                            |
| [raysan5/rFXGen](https://github.com/raysan5/rfxgen)                                                   | Simple and easy-to-use fx sounds generator.                                                                                                                          |
| [victorfisac/rPBR](https://github.com/victorfisac/rPBR)                                               | 3D model viewer with PBR pipeline written using OpenGL with usage of raylib in pure C.                                                                               |
| [RobLoach/raylib-libretro](https://github.com/RobLoach/raylib-libretro)                               | libretro frontend using raylib.                                                                                                                                      |
| [victorfisac/FNode](https://github.com/victorfisac/FNode)                                             | Tool based in nodes to build GLSL shaders without any programming knowledge written in C using OpenGL and GLFW.                                                      |
| [MaximeHouis/RayTracer](https://github.com/MaximeHouis/RayTracer)                                     | Ray Tracer in C++ using raylib.                                                                                                                                      |
| [fedqx/GeldaEngine](https://github.com/fedqx/GeldaEngine)                                             | C raylib game engine.                                                                                                                                                |
| [xdrie/rengfx](https://github.com/xdrie/rengfx)                                                       | Lightweight, expressive, extensible 2D/3D game engine, Written in D.                                                                                                 |
| [Rabios/raytaiko](https://github.com/Rabios/raytaiko)                                                 | Simple and moddable Taiko no Tatsujin engine written in Lua using raylib using TSnake41's LuaJIT bindings.                                                           |
| [Rabios/raylua/tree/master/zerobrane](https://github.com/Rabios/raylua/tree/master/zerobrane)         | ZeroBrane Studio autocompletion for raylib Lua bindings.                                                                                                             |
| [nurakmaljalil91/cbit-raylib](https://github.com/nurakmaljalil91/cbit-raylib)                         | C++ Game Engine built on top of raylib.                                                                                                                              |
| [CarterPatterson/PhysicsEngine](https://github.com/CarterPatterson/PhysicsEngine)                     | Simple physics engine built in raylib for AIE CS 2019, Written in C++!                                                                                               |
| [JhnBrunelle/Beam2D-Engine](https://github.com/JhnBrunelle/Beam2D-Engine)                             | C++ ECS game engine based on raylib and OpenGL.                                                                                                                      |
| [Guevara-chan/Midday-Commander](https://github.com/Guevara-chan/Midday-Commander)                     | •Retrofuturistic file manager•, Written in Nim.                                                                                                                      |
| [hfabre/ttme](https://github.com/hfabre/ttme)                                                         | Tiny tile map editor, Written in Go.                                                                                                                                 |
| [ProfJski/ArtColor](https://github.com/ProfJski/ArtColors)                                            | Sort of color mixing tools built with raylib.                                                                                                                        |
| [Demizdor/experimental-raygui-editor](https://github.com/Demizdor/experimental-raygui-editor)         | Experimental GUI editor for raygui.                                                                                                                                  |
| [rfaile313/Raylib-Buildfiles](https://github.com/rfaile313/Raylib-Buildfiles)                         | Simple Makefile that incorporates raylib on OS: Windows && Platform: Desktop.                                                                                        |
| [redsled84/music-player](https://github.com/redsled84/music-player)                                   | Linked list music player using raylib.                                                                                                                               |
| [ArnautDaniel/riley-duper](https://github.com/ArnautDaniel/riley-duper)                               | Application for sorting images based on related "types" of items in the pictures.                                                                                    |
| [WEREMSOFT/c99-raylib-vide-player](https://github.com/WEREMSOFT/c99-raylib-vide-player)               | Videoplayer using raylib. Play unsuported video format by the browser in the broswer.                                                                                |
| [TheLumaio/baslike-editor](https://github.com/TheLumaio/baslike-editor)                               | Editor for baslike written in raylib.                                                                                                                                |
| [pkeckler/PACKER](https://github.com/pkeckler/PACKER)                                                 | raylib asset packer.                                                                                                                                                 |
| [ComLarsic/Chip8-raylib](https://github.com/ComLarsic/Chip8-raylib)                                   | CHIP8 emulator written in C# using raylib.                                                                                                                           |
| [LesFarrell/Chip8](https://github.com/LesFarrell/Chip8)                                               | CHIP8 Emulator/Interpreter using written using C and the raylib library.                                                                                             |
| [ralsina/cobra-py](https://github.com/ralsina/cobra-py)                                               | 80s-style Python environment.                                                                                                                                        |
| [athreef/Alien-raylib](https://github.com/athreef/Alien-raylib)                                       | Alien distribution for raylib video game engine.                                                                                                                     |
| [JusticeShultz/cpp-raylib-tilemap](https://github.com/JusticeShultz/cpp-raylib-tilemap)               | Source code for a runtime tile map tool in the C++ raylib library.                                                                                                   |
| [MasterPlan by SolarLune](https://solarlune.itch.io/masterplan)                                       | easy-to-use graphical free-flow project management tool and idea board.                                                                                              |
| [Cute Exporter by Clay Murray](https://powerc9000.itch.io/cute-asset-pipeline)                        | The best PSD layers to PNG texture atlas exporter.                                                                                                                   |
| [MySprite by TonyButDead](https://tonybutdead.itch.io/mysprite)                                       | Free pixel art tool created in the Go programming language with raylib.                                                                                              |
| [SeijiEmery's level editor](https://seijiemery.itch.io/agj-level-editor-in-a-weekend)                 | Quick experiment in building a small game/nice-ish level editor/platformer from scratch with raylib over a weekend.                                                  |
| [rTexPacker by raylib technologies](https://raylibtech.itch.io/rtexpacker)                            | Simple and easy-to-use textures packer and font atlas generator.                                                                                                     |
| [rTexViewer by raylib technologies](https://raylibtech.itch.io/rtexviewer)                            | Simple and easy-to-use textures viewer and pixel formats converter.                                                                                                  |
| [rIconPacker by raylib technologies](https://raylibtech.itch.io/riconpacker)                          | Simple and easy-to-use icons packer.                                                                                                                                 |
| [rGuiStyler by raylib technologies](https://raylibtech.itch.io/rguistyler)                            | Simple and easy-to-use raygui styles editor.                                                                                                                         |
| [rGuiLayout by raylib technologies](https://raylibtech.itch.io/rguilayout)                            | Simple and easy-to-use raygui layouts editor.                                                                                                                        |
| [rGuiIcons by raylib technologies](https://raylibtech.itch.io/rguiicons)                              | Simple and easy-to-use raygui icons editor.                                                                                                                          |
| [obaodelana/graphingcalculator](https://github.com/obaodelana/graphingcalculator)                     | Graphing Calculator made with raylib using C.                                                                                                                        |
| [krsn53/win-3d-maze](https://github.com/krsn53/win-3d-maze)                                           | Windows 3D Maze Screensaver in C++ with raylib.                                                                                                                      |
| [MadeleinNyblom/LevelEditor-MayaPlugin](https://github.com/MadeleinNyblom/LevelEditor-MayaPlugin)     | Level editor that sends information from Maya to raylib using a circular buffer.                                                                                     |
| [kenhyokun/khkFramework-raylib](https://github.com/kenhyokun/khkFramework-raylib)                     | Experimental C/C++ 2D game framework with raylib.                                                                                                                    |
| [HurricaneInteractive/abyss_engine](https://github.com/HurricaneInteractive/abyss_engine)             | Very simple game engine written in Rust and built on top of raylib-rs.                                                                                               |
| [HurricaneInteractive/abyss_editor](https://github.com/HurricaneInteractive/abyss_editor)             | Editor used for the abyss engine and built using Gatsby and Tauri.                                                                                                   |
| [CorentinLeGuen/RayGame](https://github.com/CorentinLeGuen/RayGame)                                   | Map creator with raylib library written in Python 3.                                                                                                                 |
| [reidevries/CopyCat](https://github.com/reidevries/CopyCat)                                           | C++ 17 Game engine based on raylib and EnTT libraries, end goal of creating a tactical RPG.                                                                          |
| [pery77/peryEngine](https://github.com/pery77/peryEngine)                                             | C/C++ Retro game engine based on raylib.                                                                                                                             |
| [kuripa/Rayengine](https://github.com/kuripa/Rayengine)                                               | C++ Small game engine thats based on raylib.                                                                                                                         |
| [Italian-Coders-Group/Ungine](https://github.com/Italian-Coders-Group/Ungine)                         | Source-like rayLib-based game engine for C++.                                                                                                                        |
| [senior-sigan/chat_from_scratch](https://github.com/senior-sigan/chat_from_scratch)                   | Code from the series of my streams where I work on creating Chat application absolutely from scratch, Written in C++.                                                |
| [bayganik/mmGame-Engine-Raylib-ECS](https://github.com/bayganik/mmGame-Engine-Raylib-ECS)             | C# Game engine using Raylib-CS and Entitas lite as an ECS.                                                                                                           |
| [xero1/ray-quake](https://github.com/xero1/ray-quake)                                                 | .NET Core Quake source port built using raylib.                                                                                                                      |
| [practicing01/raylibeditor](https://github.com/practicing01/raylibeditor)                             | Editor made with raylib.                                                                                                                                             |
| [pkeckler/PACKER](https://github.com/pkeckler/PACKER)                                                 | raylib asset packer.                                                                                                                                                 |
| [parmaja/tyro](https://github.com/parmaja/tyro)                                                       | Simple graphical environment for kids and newbies, using raylib as small game engine to draw, Written in Pascal.                                                     |
| [Fakaaa/Raylibculator](https://github.com/Fakaaa/Raylibculator)                                       | Calculator made with raylib.                                                                                                                                         |
| [Elkantor/raylib_package](https://github.com/Elkantor/raylib_package)                                 | BSCXX module for raylib C library.                                                                                                                                   |
| [RafaelOliveira/clay](https://github.com/RafaelOliveira/clay)                                         | 2D game engine for raylib in C++.                                                                                                                                    |
| [sparkskapil/Quill](https://github.com/sparkskapil/Quill)                                             | 2D CAD Application using raylib and C++.                                                                                                                             |
| [jmorel33/RayLib-Keyboard-keycode-tester](https://github.com/jmorel33/RayLib-Keyboard-keycode-tester) | Keyboard tester made with raylib.                                                                                                                                    |
| [kugo12/sponGB](https://github.com/kugo12/sponGB)                                                     | Gameboy emulator written using Rust and raylib.                                                                                                                      |
| [Veradictus/Kaetram-Raylib](https://github.com/Veradictus/Kaetram-Raylib)                             | C++ Conversion of the Kaetram client to raylib to improve performance and gameplay.                                                                                  |
| [trikko/BlobEditor](https://github.com/trikko/BlobEditor)                                             | Simple raylib and Dlang project.                                                                                                                                     |
| [Andre-LA/nprof](https://github.com/Andre-LA/nprof)                                                   | Very basic profiler for raylib-nelua, Written in Nelua.                                                                                                              |
| [RhettVX/forgelight-raylib](https://github.com/RhettVX/forgelight-raylib)                             | Experimental set of tools for exploring ForgeLight engine game files using raylib and raygui.                                                                        |
| [gergondet/mc_rtc-raylib](https://github.com/gergondet/mc_rtc-raylib)                                 | Simple mc_rtc GUI client using raylib.                                                                                                                               |
| [KonPet/Red-Shell](https://github.com/KonPet/Red-Shell)                                               | Level Editor for the Mario vs Luigi Python clone made in C++ using raylib.                                                                                           |
| [JonSnowbd/XPROEngine](https://github.com/JonSnowbd/XPROEngine)                                       | build-inside C game engine that utilizes raylib/Flecs/Binn to create incredibly fast games with C/Lua.                                                               |
| [gilzoide/gargula](https://github.com/gilzoide/gargula)                                               | Game engine based on nested structs and compile-time tree traversals powered by raylib and D compatible with better C.                                               |
| [randevlper/rayoflight](https://github.com/randevlper/rayoflight)                                     | 2D Engine implementing Box2D and raylib.                                                                                                                             |
| [notsnail/v2](https://github.com/notsnail/v2)                                                         | Framework for games built with raylib.                                                                                                                               |
| [erikerlandson/ray-ubi](https://github.com/erikerlandson/ray-ubi)                                     | Minimalist raylib distributed computing container image, based on Red Hat UBI.                                                                                       |
| [Demizdor/particle_editor](https://github.com/Demizdor/particle_editor)                               | Experimental particle editor!                                                                                                                                        |
| [gtrxAC/rlwm](https://github.com/gtrxAC/rlwm)                                                         | Fake operating system/window manager.                                                                                                                                |
| [HellRok/Taylor](https://github.com/HellRok/Taylor)                                                   | Simple game engine built using raylib and MRuby.                                                                                                                     |
| [MallocStudio/Sketch_Game_Engine](https://github.com/MallocStudio/Sketch_Game_Engine)                 | Simple game engine built on top of raylib that intended as personal hobby project.                                                                                   |
| [LilianHollard/game_engine-raylib](https://github.com/LilianHollard/game_engine-raylib)               | Tiny game engine written in C with raylib.                                                                                                                           |
| [TheDarkBug/simple_raycasting](https://github.com/TheDarkBug/simple_raycasting)                       | Simple raycasting "engine" written in C with raylib for graphics.                                                                                                    |
| [LunaRyuko/LunarViewer](https://github.com/LunaRyuko/LunarViewer)                                     | Model viewer for Quake 1 and Hexen 2.                                                                                                                                |
| [myuce/mapviewer](https://github.com/myuce/mapviewer)                                                 | Very primitive map viewer for the Quake map format.                                                                                                                  |

### Deprecated/Removed/Unknown bindings

| Name                                                                                  | Description                                                               |
|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| [CreedVI/Raylib-J](https://github.com/CreedVI/Raylib-J)                               | Rewrite of raylib for Java using LWJGL3.                                  |               
| [DevJac/rust_raylib_bindings](https://github.com/DevJac/rust_raylib_bindings)         | Another rust bindings for raylib.                                         |
| [SliverLIVE/Raylib-for-GLBasic](https://github.com/SliverLIVE/Raylib-for-GLBasic)     | WIP raylib port/bindings for [GLBasic](https://www.glbasic.com).          |
| [dtcristo/raylib-rust](https://github.com/dtcristo/raylib-rust)                       | Rust bindings for raylib, Removed from bindings list after dev's request. |
| [mmalecot/rayquaza](https://github.com/mmalecot/rayquaza)                             | Idiomatic Rust wrapper for raylib.                                        |
| [glasyalabolas/fb-raylib](https://github.com/glasyalabolas/fb-raylib)                 | Port of raylib 3.5 headers and examples for FreeBasic.                    |
| [haxeui/raylib-haxe](https://github.com/haxeui/raylib-haxe)                           | raylib extern bindings for Haxe!                                          |
| [shiryel/rayex](https://github.com/shiryel/rayex)                                     | raylib bindings for Elixir!                                               |


> NOTE: You won't find these bindings in [BINDINGS.md](https://github.com/raysan5/raylib/blob/master/BINDINGS.md)!

### Libraries bindings/ports

| Name                                                                                  | Description                                                                 |
|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------|
| [Dacode45/rayfork-rs](https://github.com/Dacode45/rayfork-rs)                         | Port of rayfork to Rust.                                                    |
| [EMoore13/Animator-For-Raylib-CS](https://github.com/EMoore13/Animator-For-Raylib-CS) | C# Modified version of AliElSaleh's Animator-For-Raylib that uses raylib-cs |

### Community Examples

| Name                                                                                                                      | Description                                                                                                                                |
|---------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| [ProfJski/WaveEquationDemo](https://github.com/ProfJski/WaveEquationDemo)                                                 | intuitive approach to introducing the Schrodinger wave equation using a classical particle.                                                |
| [antwxne/IndieStudio](https://github.com/antwxne/IndieStudio)                                                             | Epitech 2nd year end year 3D graphical project in C++.                                                                                     |
| [Armapillow/bezier](https://github.com/Armapillow/bezier)                                                                 | Visualisation for Bézier curve using raylib.                                                                                               |
| [ChrisDill/raylib-instancing](https://github.com/ChrisDill/raylib-instancing)                                             | Instanced rendering examples using raylib.                                                                                                 |
| [AcademyOfInteractiveEntertainment/AIEYear1Samples](https://github.com/AcademyOfInteractiveEntertainment/AIEYear1Samples) | Sample and tutorial code for AIE's Diploma of Digital and Interactive Games.                                                               |
| [GoldenThumbs/raylibShadowmap](https://github.com/GoldenThumbs/raylibShadowmap)                                           | Shadowmapping with raylib!                                                                                                                 |
| [Lightnet/raylibvscodeexample](https://github.com/Lightnet/raylibvscodeexample)                                           | VSCode project sample for raylib.                                                                                                          |
| [jpike/RayWorld3D](https://github.com/jpike/RayWorld3D)                                                                   | Playing around with raylib's 3D stuff.                                                                                                     |
| [AliElSaleh/Cosmic-Hell](https://github.com/AliElSaleh/Cosmic-Hell)                                                       | AIE Holiday Coding Challenge. A Bullet-Hell game that implements flocking in C/C++ using raylib.                                           |
| [Skaruts/Game-of-Life-in-Multiple-Languages](https://github.com/Skaruts/Game-of-Life-in-Multiple-Languages)               | Game of Life implemented in multiple languages and has version for raylib.                                                                 |
| [I3uckwheat/CHUCK](https://github.com/I3uckwheat/CHUCK)                                                                   | Allows tiled maps to be used with raylib with little trouble.                                                                              |
| [machinbrol/2d-physics-engine-test](https://github.com/machinbrol/2d-physics-engine-test)                                 | 2D-physics-engine test with Go port of raylib.                                                                                             |
| [sepisoad/super-janet-typist](https://github.com/sepisoad/super-janet-typist)                                             | Short typing game made with Janet Lisp.                                                                                                    |
| [Ryan1729/nim-raylib-forever-raylib-audio-bug](https://github.com/Ryan1729/nim-raylib-forever-raylib-audio-bug)           | Example shows audio bug in raylib-forever Nim bindings.                                                                                    |
| [kebbbnnn/ray-lib-example](https://github.com/kebbbnnn/ray-lib-example)                                                   | raylib example for MacOS.                                                                                                                  |
| [Dacode45/raylib-physics-example](https://github.com/Dacode45/raylib-physics-example)                                     | Rust example of physics specs and raylib all coming together.                                                                              |
| [aaronrcox/EmscriptenHelloRaylib](https://github.com/aaronrcox/EmscriptenHelloRaylib)                                     | Emscripten (Web) Starter repo for raylib projects. Web builds are automaticly triggered via Github actions and Deployed to Github Pages.   |
| [chbdev/raylib-3rdPersonCameraWallDetection](https://github.com/chbdev/raylib-3rdPersonCameraWallDetection)               | Third person camera wall detection example.                                                                                                |
| [gabriellm1/ThreadLab](https://github.com/gabriellm1/ThreadLab)                                                           | Multi-thread copy and paste program with graphic interface for raylib.                                                                     |
| [jacmoe/permadi-port](https://github.com/jacmoe/permadi-port)                                                             | Permadi's Raycaster code ported to C++ and raylib.                                                                                         |
| [MitchellRB/BinaryTree](https://github.com/MitchellRB/BinaryTree)                                                         | Visual representation of a binary tree in raylib.                                                                                          |
| [xav1t0/Clock](https://github.com/xav1t0/Clock)                                                                           | Clock Made With raylib in C.                                                                                                               |
| [JRAM0012/rMandelbrotset](https://github.com/JRAM0012/rMandelbrotset)                                                     | Mandelbrot set visualizer made in raylib.                                                                                                  |
| [danimartin82/opencv_raylib](https://github.com/danimartin82/opencv_raylib)                                               | Tests for mixing OpenCV (4.2.0) with raylib (3.0).                                                                                         |
| [Lisoph/RaylibTest](https://github.com/Lisoph/RaylibTest)                                                                 | Examples of messing up with raylib.                                                                                                        |
| [ianpan870102/raylib-practices](https://github.com/ianpan870102/raylib-practices)                                         | Some personal practices with raylib and raylib-cpp in C++.                                                                                 |
| [zmontross/cellular_automata](https://github.com/zmontross/cellular_automata)                                             | First foray into using raylib as an excuse to practice C programming. No planning, and lots of spaghetti code.                             |
| [Elkantor/simulation](https://github.com/Elkantor/simulation)                                                             | Flow simulation.                                                                                                                           |
| [albertnadal/Wolf3DClone](https://github.com/albertnadal/Wolf3DClone)                                                     | Implementation of the "Wolfenstein 3D"(1992) game engine from scratch using vanilla C and raylib.                                          |
| [kawa-yoiko/ccleste-raylib](https://github.com/kawa-yoiko/ccleste-raylib)                                                 | Adaptation of ccleste to raylib with software rendering.                                                                                   |
| [EdSwordsmith/LearningRaylib](https://github.com/EdSwordsmith/LearningRaylib)                                             | Small projects made with raylib.                                                                                                           |
| [nikki93/raylib-bench-go](https://github.com/nikki93/raylib-bench-go)                                                     | Benchmark written in Go.                                                                                                                   |
| [rurush47/ca-particle-system](https://github.com/rurush47/ca-particle-system)                                             | Particle system for university project written in C++ using raylib.                                                                        |
| [ProfJski/RayLib-Examples](https://github.com/ProfJski/RayLib-Examples)                                                   | Some fun math or physics demos made easy with raylib and written in C++.                                                                   |
| [orbisdev/orbisGl2samples](https://github.com/orbisdev/orbisGl2samples)                                                   | orbisGl2 raylib samples for liborbis (For PlayStation 4).                                                                                  |
| [Delvix000/RaylibErosionStandalone](https://github.com/Delvix000/RaylibErosionStandalone)                                 | Graphics demo with that features a procedural tropical island and some cool stuff!                                                         |
| [Pakz001/Raylib-Examples](https://github.com/Pakz001/Raylib-Examples)                                                     | Collection of raylib code examples - For learning the C language with 2D and 3D games.                                                     |
| [ChrisDill/Raylib-cs-Examples](https://github.com/ChrisDill/Raylib-cs-Examples)                                           | C# examples for raylib-cs.                                                                                                                 |
| [SasLuca/rayfork-tests](https://github.com/SasLuca/rayfork-tests)                                                         | Collection of examples written in rayfork that also serve as tests.                                                                        |
| [dtcristo/cray-examples](https://github.com/dtcristo/cray-examples)                                                       | raylib examples ported to Crystal.                                                                                                         |
| [raysan5/raylib-games](https://github.com/raysan5/raylib-games)                                                           | raysan5's collection of games made with raylib.                                                                                            |
| [Rabios/rayfork-games](https://github.com/Rabios/rayfork-games)                                                           | Full port of raylib sample games to rayfork!                                                                                               |
| [WEREMSOFT/c99-raylib-car-physics](https://github.com/WEREMSOFT/c99-raylib-car-physics)                                   | Car physiscs made with raylib.                                                                                                             |
| [WEREMSOFT/c99-raylib-shadowmap](https://github.com/WEREMSOFT/c99-raylib-shadowmap)                                       | Shadowmap implementation in raylib.                                                                                                        |
| [rillk500/Dlang-Game-Dev](https://github.com/rillk500/Dlang-Game-Dev)                                                     | Games created with D programming language.                                                                                                 |
| [rillk500/Learn-Dlang-game-dev](https://github.com/rillk500/Learn-Dlang-game-dev)                                         | Learn D programming language by creating games!                                                                                            |
| [BitPuffin/zig-raylib-experiments](https://github.com/BitPuffin/zig-raylib-experiments)                                   | Some classic game implementations in Zig using raylib.                                                                                     |
| [MetlHedd/raylib-rs-examples](https://github.com/MetlHedd/raylib-rs-examples)                                             | Collection of raylib examples written in Rust using raylib-rs.                                                                             |
| [DaNiKhan-GbR/Dnkvw-Raylib-Example](https://github.com/DaNiKhan-GbR/Dnkvw-Raylib-Example)                                 | Virtual window raylib 3D Example.                                                                                                          |
| [Demizdor/rlexp](https://github.com/Demizdor/rlexp)                                                                       | Experiments using the raylib library.                                                                                                      |
| [fr3fou/tic-tac-toe-ai](https://github.com/fr3fou/tic-tac-toe-ai)                                                         | Tic-Tac-Toe implementation and AI, using Raylib for the GUI and Minimax + Alpha-Beta pruning for the AI.                                   |
| [petuzk/raylib-line-triangulator](https://github.com/petuzk/raylib-line-triangulator)                                     | Line triangulation algorithm for raylib.                                                                                                   |
| [rillk500/clang-game-dev](https://github.com/rillk500/clang-game-dev)                                                     | Games created with C programming language.                                                                                                 |
| [ThePituLegend/SmurfInvaders](https://github.com/ThePituLegend/SmurfInvaders)                                             | Technical Demo as an explorative project of raylib. Random game based on Space Invaders and alike.                                         |
| [riadafridishibly/recursive-sudoku-viz](https://github.com/riadafridishibly/recursive-sudoku-viz)                         | Recursive sudoku solver visualizer in raylib, Written in C++.                                                                              |
| [amazingchow/through-the-maze](https://github.com/amazingchow/through-the-maze)                                           | Through the maze based on raylib + genetic algorithm.                                                                                      |
| [GheorgheMorari/RaylibCSGraphs](https://github.com/GheorgheMorari/RaylibCSGraphs)                                         | Practical implementation of Linear Transfromation, Written in C#.                                                                          |
| [Sepheus/critter_comforts](https://github.com/Sepheus/critter_comforts)                                                   | Source code of hit first game from legendary studio Vat O'Coffee. Coded for the V&A Operas & Bridges GameJam, Written in D.                |
| [DavinderMaverick/VoronoiDiagram](https://github.com/DavinderMaverick/VoronoiDiagram)                                     | Voronoi Diagrams using Fortune's Algo, Written in C++.                                                                                     |
| [apahl/corosim](https://github.com/apahl/corosim)                                                                         | Simple infection simulator, written in Swift using raylib.                                                                                 |
| [baylej/tmx/tree/master/examples/raylib](https://github.com/baylej/tmx/tree/master/examples/raylib)                       | Example of C tmx map loader that uses raylib.                                                                                              |
| [albertnadal/MandelbrotGoLang](https://github.com/albertnadal/MandelbrotGoLang)                                           | Distributed computing Mandelbrot implementation using Golang, gRPC and raylib.                                                             |
| [OnACoffeeBreak/raylib_tiled_import_with_tmx](https://github.com/OnACoffeeBreak/raylib_tiled_import_with_tmx)             | Example of how to use raylib to import and display a Tiled map editor file.                                                                |
| [MrOneTwo/Raylib-shaders](https://github.com/MrOneTwo/Raylib-shaders)                                                     | Having fun with shaders.                                                                                                                   |
| [anatagawa/Demo-Paradox](https://github.com/anatagawa/Demo-Paradox)                                                       | Demo with raylib.                                                                                                                          |
| [anatagawa/Demo-Interpole](https://github.com/anatagawa/Demo-Interpole)                                                   | Demo with raylib.                                                                                                                          |
| [anatagawa/Demo-Awesome](https://github.com/anatagawa/Demo-Awesome)                                                       | Demo with raylib.                                                                                                                          |
| [nathhB/nbnet/tree/master/examples/raylib](https://github.com/nathhB/nbnet/tree/master/examples/raylib)                   | raylib example for nbnet, single-header C network library to implement client-server network code for games.                               |
| [edomin/Raygui_Helloworld](https://github.com/edomin/Raygui_Helloworld)                                                   | Example of using raygui library with tigr graphics library.                                                                                |
| [JohnLins/SphereDensity](https://github.com/JohnLins/SphereDensity)                                                       | Example of 3D rendered sphere increasing in "density" by increasing the rings and slices.                                                  |
| [badlydrawnrod/evaluate-raylib](https://github.com/badlydrawnrod/evaluate-raylib)                                         | Few short and cross-platform raylib demos. Known to work on Windows, Raspberry Pi 400 (desktop + native), Web (emscripten).                |
| [c-krit/kraber](https://github.com/c-krit/kraber)                                                                         | Cool ideas and experiments with raylib, Written in C.                                                                                      |
| [ArnautDaniel/riley-duper](https://github.com/ArnautDaniel/riley-duper)                                                   | Iterative melancholy written in Factor.                                                                                                    |
| [jmorel33/RayLib-Video-Modes](https://github.com/jmorel33/RayLib-Video-Modes)                                             | Example of getting list of monitor's video modes from GLFW3 with raylib!                                                                   | 
| [TheCatOverlord/Raylib-Joystick](https://github.com/TheCatOverlord/Raylib-Joystick)                                       | Example implementing Joystick input for raylib using `<linux/joystick.h>` Linux module.                                                    |
| [tomxmm0/dvd_screensaver](https://github.com/tomxmm0/dvd_screensaver)                                                     | DVD Screensaver made with raylib.                                                                                                          |
| [Razikus/raylib-qrcode](https://github.com/Razikus/raylib-qrcode)                                                         | QR Code generator for raylib using [nayuki/QR-Code-generator](https://github.com/nayuki/QR-Code-generator) lib.                            |
| [zvoskars/keyListener](https://github.com/zvoskars/keyListener)                                                           | Program that follows key inputs using C++ and raylib for Trackmania.                                                                       |
| [senior-sigan/simple_games](https://github.com/senior-sigan/simple_games)                                                 | Games created during live-streams by Ilya Siganov.                                                                                         |
| [ValiantInteractive/FPS-engine-raylib](https://github.com/ValiantInteractive/FPS-engine-raylib)                           | FPS game engine and simple First Person Shooter created with raylib using the C language.                                                  |
| [PixelPhobicGames/Chrome-Dino-game-ripoff-](https://github.com/PixelPhobicGames/Chrome-Dino-game-ripoff-)                 | Chrome Dinosaur game written in C using raylib.                                                                                            |       
| [MrOneTwo/Raylib-shaders](https://github.com/MrOneTwo/Raylib-shaders)                                                     | C++ Example(s) for having fun with shaders.                                                                                                |
| [nas-programmer/raylib_projects](https://github.com/nas-programmer/raylib_projects)                                       | Things made with raylib and C++.                                                                                                           |
| [NevilleJS/spirograph](https://github.com/NevilleJS/spirograph)                                                           | Spirograph made in C++ using raylib.                                                                                                       |
| [someone-existing/Worley-noise-raylib](https://github.com/someone-existing/Worley-noise-raylib)                           | Extremely slow and buggy implementation of Worley noise done in raylib and C++.                                                            |
| [Rledrin/PathFinding](https://github.com/Rledrin/PathFinding)                                                             | C++ PathFinding example for raylib.                                                                                                        |
| [Rledrin/RayCasting2D](https://github.com/Rledrin/RayCasting2D)                                                           | C++ Raycasting example for raylib.                                                                                                         |
| [nezvers/Raylib_TrueTileCollision](https://github.com/nezvers/Raylib_TrueTileCollision)                                   | Retro platformer collision paired with modern approach utilizing delta time.                                                               |
| [justinac0/raylib-raycaster](https://github.com/justinac0/raylib-raycaster)                                               | Basic raycaster implementation in C using raylib for rendering.                                                                            |
| [RafaelOliveira/raylib-bunnymark](https://github.com/RafaelOliveira/raylib-bunnymark)                                     | Simple Bunnymark test with raylib.                                                                                                         |
| [henriquel1997/webcam_raylib](https://github.com/henriquel1997/webcam_raylib)                                             | Test program that displays a webcam feed into a window and uses ESCAPI and raylib.                                                         |
| [yaram/match-three](https://github.com/yaram/match-three)                                                                 | C++ Simple match-three prototype using raylib.                                                                                             |
| [erikerlandson/ray-odh-demo](https://github.com/erikerlandson/ray-odh-demo)                                               | Prototype an integration of ray with Open Data Hub, using a singleuser profile to provision a ray cluster.                                 |
| [neonmoe/metro](https://github.com/neonmoe/metro)                                                                         | Raymarched exploration of floating-point errors in a metro tunnel.                                                                         |
| [afreytes/RLSolarSystem](https://github.com/afreytes/RLSolarSystem)                                                       | Solar system simulation based on [arinal/WPFSolarSystem](https://github.com/arinal/WpfSolarSystem) but via raylib-cs in C#.                |
| [Adobe-Android/raylib-demo](https://github.com/Adobe-Android/raylib-demo)                                                 | raylib demo project using C++ and CMake.                                                                                                   |
| [PHILLIPGATLIN/Caption](https://github.com/PHILLIPGATLIN/Caption)                                                         | Image captioning program made with raylib.                                                                                                 |
| [adamszymanowski/RayLibExamples](https://github.com/adamszymanowski/RayLibExamples)                                       | raylib 3.5 examples.                                                                                                                       |
| [gihadmecha/raylib_examples_to_learn](https://github.com/gihadmecha/raylib_examples_to_learn)                             | Some raylib examples.                                                                                                                      |
| [danimartin82/rayMaschine](https://github.com/danimartin82/rayMaschine)                                                   | Project for the raylib 32x32 Competition.                                                                                                  |
| [JusticeShultz/RaylibPhysics](https://github.com/JusticeShultz/RaylibPhysics)                                             | Physics in C++.                                                                                                                            |
| [pintertamas/my-awesome-project](https://github.com/pintertamas/my-awesome-project)                                       | Programming homework that uses the raylib library for graphics.                                                                            |
| [bruhmoment3124/raylib](https://github.com/bruhmoment3124/raylib)                                                         | Things made with raylib.                                                                                                                   |
| [feihong/gamedev-experiments](https://github.com/feihong/gamedev-experiments)                                             | [Feihong](https://github.com/feihong)'s raylib quickstart.                                                                                 |
| [creikey/raylib-particles](https://github.com/creikey/raylib-particles)                                                   | Particles life made in raylib.                                                                                                             |
| [t0rre/Raylib-3d-Test](https://github.com/t0rre/Raylib-3d-Test)                                                           | Test with 3D in raylib.                                                                                                                    |
| [JohnLins/GravitationalAcceleration](https://github.com/JohnLins/GravitationalAcceleration)                               | Example(s) for gravity with acceleration!                                                                                                  |
| [Nuuttif/2x2RubiksCubeSimulator](https://github.com/Nuuttif/2x2RubiksCubeSimulator)                                       | WIP 2x2 Rubik's cube simulator.                                                                                                            |
| [DoctorAkula/Altair8800](https://github.com/DoctorAkula/Altair8800)                                                       | Front panel emulation of the MITS Altair 8800 written in C using raylib.                                                                   |
| [fullnitrous/rsim](https://github.com/fullnitrous/rsim)                                                                   | Cross platform rocket simulation software package written in C with raylib.                                                                |
| [jessp/Pepper-s-Pi-Cone](https://github.com/jessp/Pepper-s-Pi-Cone)                                                       | WIP repository to adapt Roxanne Luo's Pepper's cone into C with raylib with the intention of running it off a Raspberry Pi.                |
| [Nachasic/vicarious-rs](https://github.com/Nachasic/vicarious-rs)                                                         | Gamedev experiments with raylib and Rust.                                                                                                  |
| [buribalazs/raylib-rs-play_sound_multi](https://github.com/buribalazs/raylib-rs-play_sound_multi)                         | Example to demonstrate a crash on windows 10 written in Rust.                                                                              |
| [teh-cmc/rts](https://github.com/teh-cmc/rts)                                                                             | Building an RTS the old way, with Rust, raylib & Emscripten.                                                                               |
| [jestarray/raylib_ffi_bug](https://github.com/jestarray/raylib_ffi_bug)                                                   | Incorrect FFI call which turning bool to a random number, Written in Rust.                                                                 |

### Templates

| Name                                                                                                      | Description                                                                                                                                |
|-----------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| [tducasse/raylib_starter](https://github.com/tducasse/raylib_starter)                                     | Simple raylib template for Windows and Web targets.                                                                                        |
| [daandruff/rbpi400raylib](https://github.com/daandruff/rbpi400raylib)                                     | Simple raylib template for Raspberry Pi 400.                                                                                               | 
| [irskep/raylibtest](https://github.com/irskep/raylibtest)                                                 | raylib Nim bindings test example.                                                                                                          |
| [jamiltron/ray-starter](https://github.com/jamiltron/ray-starter)                                         | Skeleton of a raylib project with CMake.                                                                                                   |
| [benweidig/raylib-template](https://github.com/benweidig/raylib-template)                                 | Linux template for raylib.                                                                                                                 |
| [CapsCollective/raylib-cpp-starter](https://github.com/CapsCollective/raylib-cpp-starter)                 | Portable and automated template for raylib projects with C++ bindings.                                                                     |
| [inque/simple_raylib_template](https://gitlab.com/inque/simple_raylib_template)                           | This is a simple raylib boilerplate that can be used as a starting point for raylib, It has also utility to build for Web!                 |
| [oswjk/raylib-imgui-template](https://github.com/oswjk/raylib-imgui-template)                             | Basic raylib + Dear ImGui template.                                                                                                        |
| [AIE-Seattle-Prog/raygame](https://github.com/AIE-Seattle-Prog/raygame)                                   | Sample C++ project setup with raylib for Visual Studio 2017.                                                                               |
| [AIE-Seattle-Prog/raygamecsharp](https://github.com/AIE-Seattle-Prog/raygamecsharp)                       | Sample C# project setup with raylib-cs for Visual Studio 2017.                                                                             |
| [DaNiKhan-GbR/Dnkvw-Raylib-Minimal-Example](https://github.com/DaNiKhan-GbR/Dnkvw-Raylib-Minimal-Example) | Minimal example that demonstrates the usage of Dnkvw with raylib, Can be used as a project template.                                       |
| [krzosa/RaylibHotReloadTemplate](https://github.com/krzosa/RaylibHotReloadTemplate)                       | Template for hot reload code in raylib.                                                                                                    |
| [WEREMSOFT/c99-raylib-template](https://github.com/WEREMSOFT/c99-raylib-template)                         | Starting template to work with raylib, Uses make for build.                                                                                |
| [WEREMSOFT/c99-raylib-cimgui-template](https://github.com/WEREMSOFT/c99-raylib-cimgui-template)           | Simple template to integrate raylib with imgui on C99, Uses cimgui bindings.                                                               |
| [WEREMSOFT/raylib-network-template](https://github.com/WEREMSOFT/raylib-network-template)                 | Kinda serverless multiplayer template. It can be used to make a very basic multiplayer game.                                               |
| [SasLuca/raylib-cmake-template](https://github.com/SasLuca/raylib-cmake-template)                         | Very minimal project template for raylib using CMake that works well in CLion & Visual Studio.                                             |
| [SasLuca/rayfork-sokol-template](https://github.com/SasLuca/rayfork-sokol-template)                       | Simple rayfork project template with sokol-app and CMake.                                                                                  |
| [RaniSputnik/go-raylib-template](https://github.com/RaniSputnik/go-raylib-template)                       | Starter template for building games with the raylib Golang bindings.                                                                       |
| [Hidden-Pixel/raylib-starter-kit](https://github.com/Hidden-Pixel/raylib-starter-kit)                     | This repository is to raylib starter kit to help get up and running quickly after installing MSVC, clang or gcc, and emcc.                 |
| [oswjk/rayskeleton](https://github.com/oswjk/rayskeleton)                                                 | Skeleton project template for raylib. Uses CMake.                                                                                          |
| [braedenf/RaylibStarterProjectXcode](https://github.com/braedenf/RaylibStarterProjectXcode)               | Basic window implemented with raylib in XCode.                                                                                             |
| [jacmoe/raystart](https://github.com/jacmoe/raystart)                                                     | Quick CMake based project template for exploratory graphics programming using raylib.                                                      |
| [JamieMair/RaylibVSTemplate](https://github.com/JamieMair/RaylibVSTemplate)                               | Template Visual Studio 2019 C++ project for the raylib library.                                                                            |
| [Yrds/raylib-boilerplate](https://github.com/Yrds/raylib-boilerplate)                                     | out-of-box environment to develop raylib games.                                                                                            |
| [Qinbeans/raylib_graphic_template](https://github.com/Qinbeans/raylib_graphic_template)                   | Template for future use and has working adjustable resolution.                                                                             |
| [CodingCor/tempraylib](https://github.com/CodingCor/tempraylib)                                           | Simple C++ template to use raylib in Linux and Windows.                                                                                    |
| [MrOneTwo/Raylib-Scons-boilerplate](https://github.com/MrOneTwo/Raylib-Scons-boilerplate)                 | Boilerplate for raylib with Scons as build system.                                                                                         |
| [gilzoide/raylib-meson-template](https://github.com/gilzoide/raylib-meson-template)                       | Minimal template project for C/C++ applications using raylib built using Meson.                                                            |
| [Ushio/raylibMinimumVS](https://github.com/Ushio/raylibMinimumVS)                                         | Simple C++ template for raylib for use with Visual Studio 2017.                                                                            |
| [janderkkotlarski/raylib_template](https://github.com/janderkkotlarski/raylib_template)                   | C++ Simple raylib template that should works when raylib is correctly installed.                                                           |
| [Lattay/raylib-lsk](https://github.com/Lattay/raylib-lsk)                                                 | Lattay's Starter Kit for raylib, small boiler plate for raylib projects.                                                                   |
| [charlesmartinreed/vscode-raylib-base](https://github.com/charlesmartinreed/vscode-raylib-base)           | Setup used by GamesFromScratch when he made tutorials for raylib.                                                                          |
| [AIESydProgYr12021/RaylibCSharpStarter](https://github.com/AIESydProgYr12021/RaylibCSharpStarter)         | raylib C# game starter kit.                                                                                                                |
| [LodisAIE/RaylibStarterCPP](https://github.com/LodisAIE/RaylibStarterCPP)                                 | raylib C++ game starter kit.                                                                                                               |
| [HeatXD/Raylib-with-Flecs-Template](https://github.com/HeatXD/Raylib-with-Flecs-Template)                 | Template for raylib with a custom flecs pipline for raylib.                                                                                |
| [dwperrin/raylib-template-vscode](https://github.com/dwperrin/raylib-template-vscode)                     | VSCode template for raylib!                                                                                                                |
| [underscorenygren/parsec_raylib_template](https://github.com/underscorenygren/parsec_raylib_template)     | Starter project for the parsec and raylib integration article series, Use this as a base from which to create your own games.              |
| [LeHaine/kotlin-native-raylib-starter](https://github.com/LeHaine/kotlin-native-raylib-starter)           | Base projected configured to link, build, and run raylib with Kotlin Native.                                                               |
| [JustinKatic/Raylib-C-starterProj](https://github.com/JustinKatic/Raylib-C-starterProj)                   | Basic startup setup for raylib with a clear Start and Update function.                                                                     |
| [ruscito/raylib_template](https://github.com/ruscito/raylib_template)                                     | raylib template for MacOS.                                                                                                                 |
| [waruqi/raylib-scaffold](https://github.com/waruqi/raylib-scaffold)                                       | Minimal raylib project template that uses XMake.                                                                                           |
| [GoldenbergDaniel/RayTemplateC](https://github.com/GoldenbergDaniel/RayTemplateC)                         | Template for the raylib library in C.                                                                                                      |

### Articles

- [How to add hot reload when using raylib?](https://www.developing-stuff.com/how-to-add-hot-reload-when-using-raylib)
- [How to add hot reload to your raylib project (in C) ?](https://medium.com/@TheElkantor/how-to-add-hot-reload-to-your-raylib-proj-in-c-698caa33eb74)
- [raylib Game Tutorial : Space Invaders using VSCode](https://monsterbraininc.com/2018/12/raylib-game-tutorial-space-invaders-using-vscode)
- [Easy Blitzmax Streaming realtime audio with raylib](https://www.syntaxbomb.com/index.php?topic=5807.0)
- [Advanced Matrix transforms with raylib](https://bedroomcoders.co.uk/advanced-matrix-transforms-with-raylib)
- [Drawing textured 2D polygons with rlgl (raylib)](https://bedroomcoders.co.uk/drawing-textured-2d-polygons-with-rlgl-raylib)
- [What About Making Games Without Engines?](https://medium.com/@thelukaswils/what-about-making-games-without-engines-188c65f16672)
- [deepsource.io - Spotlight: Ramon Santamaria](https://deepsource.io/spotlight/ramon-santamaria)
- [Simple PHP Game in PHP using raylib: Snake (with source code)](https://thephp.website/en/issue/games-with-php)
- [Compiling raylib programs with SCons](http://ciesie.com/post/building_raylib_with_scons)
- [raylib game coding library for C](http://bedroomcoders.co.uk/raylib-game-coding-library-for-c)
- [raylib novices guide for creating a simple game](http://bedroomcoders.co.uk/raylib-a-novices-guide-for-creating-a-simple-game)
- [Creating a simple game (part 2)](http://bedroomcoders.co.uk/creating-a-simple-game-part-2)
- [Creating a simple game (part 3)](http://bedroomcoders.co.uk/creating-a-simple-game-part-3)
- [Creating a simple game (part 4)](http://bedroomcoders.co.uk/creating-a-simple-game-part-4)
- [Creating a simple game (part 5) finishing up](http://bedroomcoders.co.uk/creating-a-simple-game-part-5-finishing-up)
- [Complete Template for Raylib](http://bedroomcoders.co.uk/complete-template-for-raylib)
- [3d Physics with raylib and ODE](http://bedroomcoders.co.uk/3d-physics-with-libray-and-ode)
- [raylib adding a static terrain (ODE)](http://bedroomcoders.co.uk/raylib-adding-a-static-terrain-ode)
- [Looking again at compiling a Windows raylib app](http://bedroomcoders.co.uk/looking-again-at-compiling-a-windows-raylib-app)
- [Creating a 64 bit executable with raylib on windows](http://bedroomcoders.co.uk/creating-a-64-bit-executable-with-raylib-on-windows)
- [Aiming at moving targets…](http://bedroomcoders.co.uk/aiming-at-moving-targets)
- [Aiming at 3d moving targets](http://bedroomcoders.co.uk/aiming-at-3d-moving-targets)
- [Painting on a 3d Mesh with raylib](http://bedroomcoders.co.uk/painting-on-a-3d-mesh-with-raylib)
- [Raylib, projecting 3D onto 2D handy for debugging](http://bedroomcoders.co.uk/raylib-projecting-3d-onto-2d-handy-for-debugging)
- [Raylib and Chipmunk2d](http://bedroomcoders.co.uk/raylib-and-chipmunk2d)
- [PhysFS and raylib](http://bedroomcoders.co.uk/physfs-and-raylib)
- [Using libmpeg2 with raylib](http://bedroomcoders.co.uk/using-libmpeg2-with-raylib)
- [Aligning a model with a terrain (raylib)](http://bedroomcoders.co.uk/aligning-a-model-with-a-terrain-raylib)
- [A simple maze creation algorithm (C99 and raylib)](http://bedroomcoders.co.uk/a-simple-maze-creation-algorithm-c99-and-raylib)
- [Using RayLib with an ECS](http://bedroomcoders.co.uk/using-raylib-with-an-ecs)
- [Animating sky with raylib](http://bedroomcoders.co.uk/animating-sky-with-raylib)
- [raylib Fog](http://bedroomcoders.co.uk/raylib-fog)
- [Sprite Sheets with rayLib](http://bedroomcoders.co.uk/sprite-sheets-with-raylib)
- [Shaders with raylib](http://bedroomcoders.co.uk/shaders-with-raylib)
- [Lighting with raylib](http://bedroomcoders.co.uk/lighting-with-raylib)
- [2D Spotlight shader with rayLib](http://bedroomcoders.co.uk/2d-spotlight-shader-with-raylib)
- [Implementing a 3d GUI with raylib](http://bedroomcoders.co.uk/implementing-a-3d-gui-with-raylib)
- [Creating Raspberry Pi applications with raylib and Ruby (Part 1)](https://medium.com/@avik.das/creating-raspberry-pi-applications-with-raylib-and-ruby-fba3d35b2877)
- [Creating Raspberry Pi applications with raylib and Ruby (Part 2)](https://medium.com/@avik.das/creating-raspberry-pi-applications-with-raylib-and-ruby-part-ii-edc47680157b)
- [Ubuntu 18.04 için raylib kurulumu (Turkish)](https://medium.com/@msoygen/ubuntu-18-04-raylib-kurulumu-8ff9c4274b91)
- [raylib: 6 years of fun](https://gist.github.com/raysan5/04a2daf02aa2a6e79010331f77bf983f)
- [rGuiIcons Making Of Diary](https://gist.github.com/raysan5/fe769f77b43b6c612600166498ce3640)

### Tutorials

- [Learn X in Y minutes, Where X=raylib](https://learnxinyminutes.com/docs/raylib)
- [Raylib 2.0 Tutorial Series by SkyVaultGames](https://www.youtube.com/playlist?list=PL5gRzHmN4Dg3ubcneVFkHPm0mTGYTUHDn)
- [List of raylib tutorials by HE360](https://www.youtube.com/playlist?list=PLZBVMzyySalVhcWEJcnG-HK8OXQli_tcV)
- [سلسلة تعلم برمجة الألعاب بسي شارب و جافا (Arabic, by Rabia Alhaffar)](https://www.youtube.com/playlist?list=PLZBVMzyySalXG0AdUHJj9rcpd0R7hBczR)
- [How to create a game with 'raylib' in C](https://www.youtube.com/watch?v=kBky9_X8j3Y)
- [How to get started with Raylib 3.0 in C# - Tutorial](https://www.youtube.com/watch?v=SoXD5y24WQw)
- [Let's learn D programming Game Dev!](https://www.youtube.com/playlist?list=PLgM-lc_kSqFQPF0UXgmFZpZalqcrSofe-)
- [Coding a Breakout Arcade clone in C with Raylib](https://www.youtube.com/watch?v=UKecFbu61Oc)
- [Graphics programming challenges by raysan5 (GitHub repository)](https://github.com/raysan5/challenges)
- [Raylib Game Tutorial : Space Invaders using VSCode](https://monsterbraininc.com/2018/12/raylib-game-tutorial-space-invaders-using-vscode)
- [raylib -- A C++ Game Library That's Perfect For Beginners](https://www.youtube.com/watch?v=xGPF3Gn-yhA)
- [How to build & set up raylib for Visual studio](https://www.youtube.com/watch?v=mfj0JG2LdVM)
- [Create Videos Games in PHP (With RayLib)](https://www.youtube.com/watch?v=q1X_6TYd030)
- [Compiler Raylib sur Windows (French)](https://www.youtube.com/watch?v=XEpmMBM01Zg)
- [Raylib setup on Codeblocks](https://www.youtube.com/watch?v=a2IUxJFr8sg)
- [Tile maps en Raylib con Tileson (Spanish)](https://www.youtube.com/watch?v=Gq9sTaeHtj4)

### Videos

- [RayLib Review / Open source free game library / Game Engine / Delphi, Pascal, Lazarus, C, C++, C#](https://www.youtube.com/watch?v=Z6Eg9UfC_6U&t=616s)
- [RayLib / Обзор игровой библиотеки / Pascal, Delphi, Lazarus, C++, C#, Java, JavaScript, Python, Perl(Russian)](https://www.youtube.com/watch?v=GUDzyXlmpVk&t=74s)
- [Making a Game With Trash](https://www.youtube.com/watch?v=sKlcCplUODw)
- [Best C++ Game Wins $1000 - Game Making Challenge](https://www.youtube.com/watch?v=_yyKYl1LAHM)
- [9ª QIDV (8/11) : Ramón Santamaría presenta su RayLib (Spanish)](https://www.youtube.com/watch?v=LKdqM8Wv6qk)
- [QIDV 12 (03) - Ramón Santamaría nos presenta la nueva versión de su Raylib (Spanish)](https://www.youtube.com/watch?v=tKq9mpEBQFg)
- [raylib events automation](https://www.youtube.com/watch?v=3dZenkpmRzM)
- [path following raylib and ODE vehicles](https://www.youtube.com/watch?v=p7kU5SmBZ3M)
- [ODE Vehicle Raylib](https://www.youtube.com/watch?v=LjsKEO105Dw)
- [Raylib 3.7 - raylib4Vita](https://www.youtube.com/watch?v=ISPID_2XBDs)
- [C64 demo raylib mock-up](https://www.youtube.com/watch?v=SegPe1kgILA)
- [Making a game WITHOUT a GAME ENGINE](https://www.youtube.com/watch?v=MPMELcP8-RM)
- [Learning C++ and making a GAME WITHOUT A GAME ENGINE](https://www.youtube.com/watch?v=kc4AhROG05g)
- [Bad Apple!! but its 7600 ReCT and Raylib Logos [info in description]](https://www.youtube.com/watch?v=8LnQ1A0rJ9s)
- [Why I'm Glad I Didn't Use a Game Engine](https://www.youtube.com/watch?v=nBaCRp9UzDw)
- [raylib C - Simple sand game](https://www.youtube.com/watch?v=o8QOWVHaMsg)
- [Using Android's sensor with Raylib](https://www.youtube.com/watch?v=2woi4NR7xPA)
- [Raylib SpriteEngine](https://www.youtube.com/watch?v=mMPtnHUiZbM)
- [Bad Apple!! but its 7600 ReCT and Raylib Logos [info in description]](https://www.youtube.com/watch?v=8LnQ1A0rJ9s)
- [C++ Sorting Algorithms Visualized (Raylib Library)](https://www.youtube.com/watch?v=E2Brnev0Olc)
- [Test of synchronize video and audio with OpenGL (powered by raylib)](https://www.youtube.com/watch?v=KGcC-d19-lg)
- [Traduzindo e estudando exemplos do Raylib](https://www.youtube.com/watch?v=3KKLh3W0III) (Portuguese)
- [Rayblade 2d Game Devlog using Raylib-C](https://www.youtube.com/watch?v=AmWc9qoD4UA)
- [2D Raylib Experiments Livestream (Part 1) - Making the Player Bleed](https://www.youtube.com/watch?v=N2ytx3Awt8c)
- [2D Raylib Experiments Livestream (Part 2) - Slime Time](https://www.youtube.com/watch?v=-oup057X4xw)
- [Raylib Raspberry Pi Sound Demo](https://www.youtube.com/watch?v=_vQ7PDqziO0)
- [Odin-Raylib Game Programming #000: Windows Environment Setup](https://www.youtube.com/watch?v=CDlYQtxyhPs)
- [Raylib works with Neatbeans and mac os x](https://www.youtube.com/watch?v=GFFgt1zxeck)
- [EPIC raylib c++ rpg game dev](https://www.youtube.com/watch?v=VqQDkz0t7lE)
- [Quick sort in raylib. Oh yeah.](https://www.youtube.com/watch?v=psede2nHvRE)
- [Randomness RNG vs Perlin Noise with Raylib 3.0](https://www.youtube.com/watch?v=6NLolZ-aiVA)
- [raylib - 3rd anniversary](https://www.youtube.com/watch?v=o8T9oNfsCOs)
- [Raylib oLd SkOoL 2](https://www.youtube.com/watch?v=M2WYWYQNjYg)
- [Pangea Demo - Editing Heightmaps With Raylib](https://www.youtube.com/watch?v=fWWUG9VMoQw)
- [raylib on Mobian PinePhone](https://www.youtube.com/watch?v=Vi4TXnrnExo)
- [Coding a Synthesizer in C (episode #1)](https://www.youtube.com/watch?v=p1VQuMziTek)
- [Coding a Synthesizer in C (episode #2)](https://www.youtube.com/watch?v=jZSnH33Vkh4)
- [Coding a Synthesizer in C (episode #3)](https://www.youtube.com/watch?v=WXoyF5jYujE)
- [Coding a Synthesizer in C (episode #4)](https://www.youtube.com/watch?v=SmKYWmQQmsk)
- [Coding a Synthesizer in C (episode #5)](https://www.youtube.com/watch?v=fqUbYIhLTqw)
- [How To Use Raylib With C++ And VSCode](https://www.youtube.com/watch?v=u6LXRF-iMg8)
- [Digital Crafters #2 - Ramon Santamaria](https://www.youtube.com/watch?v=wnbJpdjAHg8)
- [Interview with @imakefoss curator and Ramon Santamaria about raylib](https://www.youtube.com/watch?v=NM1gMvHwDwA)
- [Official raylib 2.5 presentation](https://www.youtube.com/watch?v=78aa2wuiGmI)
- [raylib 4.0 Released -- The Easiest C/C++ Game Library Just Got Even Better](https://www.youtube.com/watch?v=H_Oe82SqQ8Y)
- [raylib 3.7 Released](https://www.youtube.com/watch?v=c8hUF75f0kk)
- [RayLib 3.5 Released -- C/C++ GameDev Easy Mode](https://www.youtube.com/watch?v=RZJ-Z--6uxY)
- [Raylib 3.0 Released -- The Best Way to Learn C or C++ Game Development*](https://www.youtube.com/watch?v=xx9ntuvA1t0)
- [Raylib 2.0 Released -- C/C++ Game Framework Perfect For Beginners](https://www.youtube.com/watch?v=QwLHHasIO6k)
- [Raylib 1.8 Released -- Easiest C Game Framework I've Ever Found](https://www.youtube.com/watch?v=FDbIQZBar7g)
- [RayLib Receives An Epic MegaGrant!](https://www.youtube.com/watch?v=jZWwisQn76A)
- [Raylib Terrain Erosion Demo](https://www.youtube.com/watch?v=jYCSkodrg6w)
- [Checking out raylib](https://www.youtube.com/watch?v=fHojJ9Nxb0E)
- [Checking out Raylib — Part 2 — 3D Game Development](https://www.youtube.com/watch?v=QqravLVpoI8)
- [raylib -- A C++ Game Library That's Perfect For Beginners](https://www.youtube.com/watch?v=xGPF3Gn-yhA)
- [C++ | Implementing Boid: 0 Visualization | Raylib 3.0](https://www.youtube.com/watch?v=GM3TM5Hi16w)
- [How to compile Raylib from scratch and set up your first projects (Windows / C ) in 15 minutes](https://www.youtube.com/watch?v=HPDLTQ4J_zQ)
- [Making a Game for FIVE Different Consoles - Ludum Dare 46](https://www.youtube.com/watch?v=mE6_A1hRcQk)
- [Totally Not Failing at Making a Game in Raylib and C During AP Exam Week.. Retro Game Jam 2020](https://www.youtube.com/watch?v=aK_m-1wtr3A)
- [Raymarched Mandelbulb with Raylib](https://www.youtube.com/watch?v=dxOUef36bK4)
- [Particle System using RayLib | C++ GameDev | C++ Particle System](https://www.youtube.com/watch?v=j5dVx0LTtAs)
- [CRT scan line retro shader with RayLib](https://www.youtube.com/watch?v=Custpsdpgj4)
- [Using RayLib on a 32x32 "screen"](https://www.youtube.com/watch?v=DxbikNW6zN4)
- [LIVE : Raylib, une lib C / C++ idéale pour débuter ?](https://www.youtube.com/watch?v=PZi-Z9XyJo8) (French)
- [C++ | BubbleSort with RayLib 2.6 Speed Coding](https://www.youtube.com/watch?v=T-pNv6BewC8)
- [FPS game written in C](https://www.youtube.com/watch?v=xE1MG1-Yh6s)
- [Raylib Voronoi Map Generation](https://www.youtube.com/watch?v=HTZFXYpu-G0)
- [raylib and open dynamics engine](https://www.youtube.com/watch?v=sjsPUW12WYE)
- [Distributed computing of the Mandelbrot Set using Go, gRPC and Raylib](https://www.youtube.com/watch?v=pDbuClfEAIY)
- [raylib on 32x32 LED](https://www.youtube.com/watch?v=u1BzNAJORN8)
- [Procedural Island Gen and A* Pathfinding Demo](https://www.youtube.com/watch?v=vpzFoRA6Y3Q)
- [Install RayLib in LazarusIDE](https://www.youtube.com/watch?v=lAFWOgDahtk)
- [Raylib c'est bien !](https://www.youtube.com/watch?v=aaIBSuymo0Y) (French)
- [Windows 3D Maze Screensaver in C++ with raylib](https://www.youtube.com/watch?v=HuyNTB689yQ)
- [QIDV12 (03) - Ramón Santamaría nos presenta la nueva versión de su Raylib](https://www.youtube.com/watch?v=tKq9mpEBQFg) (Spanish)
- [Borak Buat Game - Belajar Raylib](https://www.youtube.com/watch?v=tMPBdjP0dp8) (Malay)
- [Belajar Raylib Part 2 - 3D Camera dan Simple Collision](https://www.youtube.com/watch?v=rMNVXFpAkg8) (Malay)
- [How to install raylib on a chromebook (OpenGl 2.1)](https://www.youtube.com/watch?v=R0jsXG4xahM)
- [Compiler Raylib sur Windows](https://www.youtube.com/watch?v=XEpmMBM01Zg) (French)
- [RayLib-PHP DevLog Fonts & Tiled Support](https://www.youtube.com/watch?v=JYGtt0sfbzw)
- [C | Implementing Epicycloid with Raylib 3.0 Speed Coding](https://www.youtube.com/watch?v=wZDEkIwkyFk)
- [C | Implementing Fractal Tree with Raylib 3.0 Speed Coding](https://www.youtube.com/watch?v=WdPnUAJW3YM)
- [Coding a Breakout Arcade clone in C with Raylib](https://www.youtube.com/watch?v=UKecFbu61Oc)
- [A brief introduction to Raylib](https://www.youtube.com/watch?v=J4eLE9YYQp0)
- [How to get started with Raylib 3.0 in C# - Tutorial](https://www.youtube.com/watch?v=SoXD5y24WQw)
- [Raylib - adventure in shaders - ep00](https://www.youtube.com/watch?v=siosc2B1bA4)
- [Raylib - adventure in shaders - ep01](https://www.youtube.com/watch?v=8205iyicv5k)
- [Raylib - Fixing the "Skipping Incompatible ../src\libraylib.a When Searching For -lraylib" Error](https://www.youtube.com/watch?v=rgV9AoVdFlA)

### Promo Images

- [Overview](https://github.com/raysan5/raylib)

![raylib overview](promos/banner13.png)

- [Overview (Wide)](https://github.com/raysan5/raylib)

![raylib overview (wide)](promos/banner7.png)

- [Last 6 years of raylib](https://twitter.com/raysan5/status/1174631716734013440)

![last 6 years of raylib](promos/banner0.png)

- [Game development is about to explode!](https://twitter.com/raysan5/status/1083782102653587456)

![raylib gamedev is about to explode](promos/banner10.png)

- [raylib 2.5 architecture](https://twitter.com/raysan5/status/1141349399316115458)

![raylib 2.5 architecture](promos/banner45.png)

- [Current raylib architecture](https://github.com/raysan5/raylib/wiki/raylib-architecture)

![raylib architecture](promos/banner1.png)

- Difference between raylib 3.5 architecture and raylib 3.7 architecture

![Difference between raylib 3.5 architecture and raylib 3.7 architecture](promos/banner57.png)

- [raylib 5th anniversary](https://twitter.com/raysan5/status/1064139050704089089)

![raylib 5th anniversary](promos/banner8.jpg)

- [raylib 6th anniversary](https://twitter.com/raysan5/status/1190963229171814401)

![raylib 6th anniversary](promos/banner2.png)

- [6 years of fun](https://gist.github.com/raysan5/04a2daf02aa2a6e79010331f77bf983f)

![raylib 6 years of fun](promos/banner4.png)

- [raylib 1.5](https://twitter.com/raysan5/status/755364768052019200)

![raylib 1.5 is ready](promos/banner25.jpg)

- [raylib 1.7](https://twitter.com/raysan5/status/865513349450129408)

![raylib 1.7](promos/banner31.jpg)

- [raylib 1.8](https://twitter.com/raysan5/status/922373390039703552)

![raylib 1.8 is out!](promos/banner26.jpg)

- [raylib 2.0 #1](https://twitter.com/raysan5/status/1020768415802380289)

![raylib 2.0 #1](promos/banner9.png)

- [raylib 2.0 #2](https://twitter.com/raysan5/status/1015222845494956033)

![raylib 2.0 #2](promos/banner29.jpg)

- [raylib 2.5](https://twitter.com/raysan5/status/1134429674472452097)

![raylib 2.5](promos/banner33.png)

- [raylib 3.0](https://twitter.com/raysan5/status/1245314287037530112)

![raylib 3.0](promos/banner6.png)

- [raylib 3.5](https://twitter.com/raysan5/status/1319036064804331521)

![raylib 3.5](promos/banner5.png)

- [raylib 3.7](https://twitter.com/raysan5/status/1386728711131734017)

![raylib 3.7](promos/banner58.png)

- [raylib parser](https://twitter.com/raysan5/status/1398948422913343488)

![raylib 4.0](promos/banner60.png)

- [raylib 4.0](https://twitter.com/raysan5/status/1456359846920458240)

![raylib parser](promos/raylib_parser_info.png)

- [raylib receives an Epic MegaGrant](https://twitter.com/raysan5/status/1291690021221736450)

![raylib received epic megagrant](promos/banner3.png)

- [raygui](https://github.com/raysan5/raygui)

![raygui](promos/banner14.png)

- [rGuiIcons](https://raylibtech.itch.io/rguiicons)

![rGuiIcons](promos/banner16.png)

- [rfxgen](https://github.com/raysan5/rfxgen)

![rfxgen](promos/banner15.png)

- [raylib technologies's tools Linux support](https://twitter.com/raylibtech/status/1180878350782533632)

![raylib technologies's tools Linux support](promos/banner12.png)

- [raylib custom build flags](https://twitter.com/raysan5/status/1298956174071664640)

![raylib build flags](promos/banner11.png)

- [raylib on Handmade Seattle](https://twitter.com/raysan5/status/1193866190126551041)

![raylib on handmade seattle](promos/banner18.png)

- [raylib 200 contributors](https://twitter.com/raysan5/status/1375789665219977217)

![raylib contributors](promos/banner19.png)

- [raylib API usage analysis](https://gist.github.com/raysan5/7c0c9fff1b6c19af24bb4a51b7383f1e)

![raylib API usage analysis](promos/banner59.png)

- [raylib in numbers](https://gist.github.com/raysan5/1e34df90dfbcef3c55b19d37d2d5ab2a)

![raylib in numbers](promos/banner20.png)

- [raylib on Wikipedia](https://twitter.com/raysan5/status/1285157701589360640)

![raylib on Wikipedia!](promos/banner27.png)

- [raylib and WebAssembly](https://twitter.com/raysan5/status/1226837835770142720)

![raylib and WebAssembly!](promos/banner28.jpg)

- [raylib FreeBSD support](https://twitter.com/raysan5/status/924913149094060032)

![raylib supports FreeBSD!](promos/banner30.jpg)

- [raylib and Global Game Jam 2018](https://twitter.com/raysan5/status/956681310239641602)

![raylib on GGJ2018!](promos/banner40.jpg)

- [raylib and Global Game Jam 2019](https://twitter.com/raysan5/status/1087728261608759299)

![raylib on GGJ2019!](promos/banner36.jpg)

- [raylib and Global Game Jam 2020](https://twitter.com/raysan5/status/1222869512984371200)

![raylib on GGJ2020!](promos/banner34.jpg)

- [raylib is simple and easy-to-use!](https://twitter.com/raysan5/status/1324789207844458496)

![raylib is simple and easy-to-use](promos/banner35.png)

- [raylib standalone modules](https://twitter.com/raysan5/status/1141354483391303681)

![raylib standalone modules](promos/banner38.png)

- [raylib social networks](https://twitter.com/raysan5/status/1141352450789711872)

![raylib social networks](promos/banner39.png)

- [raylib Discord server](https://twitter.com/raysan5/status/1019992500868657152)

![raylib discord server](promos/banner37.jpg)

- [raylib on NiceOneBarcelona](https://twitter.com/raysan5/status/1198945957293043713)

![raylib on N1B](promos/banner41.png)

- [raylib technologies's CLI study](https://twitter.com/raylibtech/status/1043097789843087361)

![raylib technologies - command line study](promos/banner42.jpg)

- [rPBR release!](https://twitter.com/elfisac/status/856882503948398592)

![rPBR released!](promos/banner43.jpg)

- [raylib supported platforms #1](https://twitter.com/raysan5/status/943880148922912768)

![raylib platforms support #1](promos/banner44.jpg)

- [raylib supported platforms #2](https://twitter.com/raysan5/status/1141350297308147721)

![raylib platforms support #2](promos/banner46.png)

- [raylib got over 30 bindings!](https://twitter.com/raysan5/status/1141350977695559681)

![raylib 30 bindings!](promos/banner47.png)

- [raylib got over 40 bindings!](https://twitter.com/raysan5/status/1162759633532063744)

![raylib 40 bindings!](promos/banner49.png)

- [Choose your flavor #1](https://twitter.com/raysan5/status/825652171425378304)

![raylib - choose your flavor #1](promos/banner51.jpg)

- [Choose your flavor #2](https://twitter.com/raysan5/status/1050346893388210178)

![raylib - choose your flavor #2](promos/banner50.jpg)

- [raylib technologies tools](https://twitter.com/raysan5/status/1141355911115681792)

![raylib technologies tools](promos/banner48.png)

- [raylib GitHub Actions build table](https://twitter.com/raysan5/status/1296148718488518656)

![raylib GitHub Actions build table](promos/banner52.jpg)

- [raylib modules](https://twitter.com/raysan5/status/840901794050002944)

![raylib modules](promos/banner53.png)

- [raylib's Google Open Source Peer Bonus](https://twitter.com/raysan5/status/1141348566167896065)

![raylib - Google Open Source Peer Bonus](promos/banner54.png)

- [Let's talk (raylib technologies)](https://twitter.com/raylibtech/status/1029061605634531329)

![raylib technologies - let's talk!](promos/banner21.jpg)

- [Working hard on the best tools!](https://twitter.com/raysan5/status/1052639309508038656)

![raylib - working hard on the best tools!](promos/banner17.jpg)

- [raylib coding examples](https://twitter.com/raysan5/status/1141353212320059392)

![raylib - +95 coding examples!](promos/banner55.png)

### Logos

[![raysan5/raylib](logos/raylib.png)](https://github.com/raysan5/raylib "raysan5/raylib")
[![SasLuca/rayfork](logos/rayfork.png)](https://github.com/SasLuca/rayfork "SasLuca/rayfork")
[![Rabios/rayport](logos/rayport.png)](https://github.com/Rabios/rayport "Rabios/rayport")
[![RobLoach/raylib-cpp](logos/raylib-cpp.png)](https://github.com/robloach/raylib-cpp "RobLoach/raylib-cpp")
[![ChrisDill/Raylib-cs](logos/raylib-cs.png)](https://github.com/ChrisDill/Raylib-cs "ChrisDill/Raylib-cs")
[![Rabios/raylib-boo](logos/raylib-boo.png)](https://github.com/Rabios/raylib-boo "Rabios/raylib-boo")
[![gen2brain/raylib-go](logos/raylib-go.png)](https://github.com/gen2brain/raylib-go "gen2brain/raylib-go")
[![Lachee/raylib-goplus](logos/raylib-go-plus.png)](https://github.com/Lachee/raylib-goplus "Lachee/raylib-goplus")
[![deltaphc/raylib-rs](logos/raylib-rust.png)](https://github.com/deltaphc/raylib-rs "deltaphc/raylib-rs")
[![raysan5/raylib-lua](logos/raylib-lua.png)](https://github.com/raysan5/raylib-lua "raysan5/raylib-lua")
[![RobLoach/raylib-lua-sol](logos/raylib-lua-sol.png)](https://github.com/RobLoach/raylib-lua-sol "RobLoach/raylib-lua-sol")
[![TSnake41/raylib-lua](logos/tsnake41-raylib-lua.png)](https://github.com/TSnake41/raylib-lua "TSnake41/raylib-lua")
[![HDPLocust/raylib-luamore](logos/raylib-luamore.png)](https://github.com/HDPLocust/raylib-luamore "HDPLocust/raylib-luamore")
[![Rabios/raylua](logos/raylua.png)](https://github.com/Rabios/raylua "Rabios/raylua")
[![Andre-LA/raylib-nelua](logos/raylib-nelua.png)](https://github.com/Andre-LA/raylib-nelua "Andre-LA/raylib-nelua")
[![AregevDev/raylib-cr](logos/raylib-cr.png)](https://github.com/AregevDev/raylib-cr "AregevDev/raylib-cr")
[![drezgames/raylib-pascal](logos/raylib-pascal.png)](https://github.com/drezgames/raylib-pascal "drezgames/raylib-pascal")
[![GuvaCode/Ray4Laz](logos/ray4laz.png)](https://github.com/GuvaCode/Ray4Laz "GuvaCode/Ray4Laz")
[![overdev/raylib-py](logos/raylib-py.png)](https://github.com/overdev/raylib-py "overdev/raylib-py")
[![RobLoach/node-raylib](logos/node-raylib.png)](https://github.com/RobLoach/node-raylib "RobLoach/node-raylib")
[![Rabios/raylib-v7](logos/raylib-v7.png)](https://github.com/Rabios/raylib-v7 "Rabios/raylib-v7")
[![RobLoach/raylib-chaiscript](logos/raylib-chaiscript.png)](https://github.com/RobLoach/raylib-chaiscript "RobLoach/raylib-chaiscript")
[![ArnautDaniel/raylib-factor](logos/raylib-factor.png)](https://github.com/ArnautDaniel/raylib-factor "ArnautDaniel/raylib-factor")
[![ArnautDaniel/gforth-raylib](logos/gforth-raylib.png)](https://github.com/ArnautDaniel/gforth-raylib "ArnautDaniel/gforth-raylib")
[![TSnake41/raylib-wren](logos/raylib-wren.png)](https://github.com/TSnake41/raylib-wren "TSnake41/raylib-wren")
[![Not-Nik/raylib-zig](logos/raylib-zig.png)](https://github.com/Not-Nik/raylib-zig "Not-Nik/raylib-zig")
[![bmx-ng/ray.mod](logos/raylib-blitzmax.png)](https://github.com/bmx-ng/ray.mod "bmx-ng/ray.mod")
[![tjammer/raylib-ocaml](logos/raylib-ocaml.png)](https://github.com/tjammer/raylib-ocaml "tjammer/raylib-ocaml")
[![D-a-n-i-l-o/raylib-purebasic](logos/raylib-purebasic.png)](https://github.com/D-a-n-i-l-o/raylib-purebasic "D-a-n-i-l-o/raylib-purebasic")
[![M0n7y5/raylib-beef](logos/raylib-beef.png)](https://github.com/M0n7y5/raylib-beef "M0n7y5/raylib-beef")
[![RedCubeDev-ByteSpace/Relib](logos/relib.png)](https://github.com/RedCubeDev-ByteSpace/Relib "RedCubeDev-ByteSpace/Relib")
[![CreedVI/Raylib-J](logos/raylib-j.png)](https://github.com/CreedVI/Raylib-J "CreedVI/Raylib-J")
[![victorfisac/Physac](logos/physac.png)](https://github.com/victorfisac/Physac "victorfisac/Physac")
[![raysan5/raygui](logos/raygui.png)](https://github.com/raysan5/raygui "raysan5/raygui")
[![raysan5/rpng](logos/rpng.png)](https://github.com/raysan5/rpng "raysan5/rpng")
[![raysan5/rres](logos/rres.png)](https://github.com/raysan5/rres "raysan5/rres")
[![raysan5/rfxgen](logos/rfxgen.png)](https://github.com/raysan5/rfxgen "raysan5/rfxgen")
[![victorfisac/FNode](logos/fnode.png)](https://github.com/victorfisac/FNode "victorfisac/FNode")
[![SliverLIVE/Raylib-for-GLBasic](logos/raylib-glbasic.png)](https://github.com/SliverLIVE/Raylib-for-GLBasic "SliverLIVE/Raylib-for-GLBasic")
[![ForeignSasquatch/hxRaylib](logos/hxraylib.png)](https://github.com/ForeignSasquatch/hxRaylib "ForeignSasquatch/hxRaylib")

### Stickers

- [Mobile](https://twitter.com/raysan5/status/1233460424114364418)

![raylib mobile sticker](promos/banner56.jpg)

- [Bag](https://twitter.com/raysan5/status/1121527359801262094)

![raylib bag sticker](promos/banner24.jpg)

### Resources and Links

- [What raylib uses?](https://github.com/raysan5/raylib/wiki/raylib-dependencies)
- [raylib Official Cheatsheet](https://www.raylib.com/cheatsheet/cheatsheet.html)
- [raylib Official examples](https://www.raylib.com/examples.html)
- [raylib Official Wiki](https://github.com/raysan5/raylib/wiki)
- [raylib on Wikipedia](https://en.wikipedia.org/wiki/Raylib)
- [raylib website](https://raylib.com)
- [raylib YouTube channel](https://www.youtube.com/channel/UC8WIBkhYb5sBNqXO1mZ7WSQ)
- [raylib Discord channel](https://discord.gg/VkzNHUE)
- [raylib on Reddit](https://www.reddit.com/r/raylib)
- [raylib on Handmade](https://raylib.handmade.network)
- [raylib page on itch.io](https://raysan5.itch.io/raylib)

> Can't find your awesome stuff or you want to improve the list? Make issue or pull request for that!
