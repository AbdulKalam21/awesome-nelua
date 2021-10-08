# awesome-nelua
A curated list of awesome frameworks, libraries, and software for the nelua programming language.

## Contents
- [awesome-nelua](https://github.com/AKDev21/awesome-nelua)
    - [General Purpose](#general-purpose)
    - [Utility](#utility)
    - [Math](#math)
    - [ffi](#ffi)
    - [Parsing](#parsing)
    - [Package Manager](#package-manager)
    - [Web](#web)
    - [Games](#games)
    - [Game Development](#game-development)
    - [Graphics](#graphics)
    - [Window and Input](#window-and-Input)
    - [IDE and Code Editor Support](#ide-and-code-editor-support)
    - [Testing](#testing)
    - [Generating Documentation](#generating-documentation)
    - [Virtual Machines](#virtual-machines)
    - [Operating Systems](#operating-Systems)
    - [Live Development](#live-development)
    - [Resources](#resources)
    - [Block Chain](#block-chain)
    - [Benchmarks](#Benchmarks)

### General Purpose
- [pancake-lib](https://github.com/linkpy/pancake-lib) - General purpose library and tools for Nelua.

### Utility
- [fs](https://github.com/edubart/nelua-batteries) - Cross platform file system library, you can use to manage files and directories.
- [nelua-decl](https://github.com/edubart/nelua-decl) - C binding generator for Nelua using GCC the Lua plugin.
- [backtrace](https://github.com/edubart/nelua-batteries) - Provides a way to get trace backs at runtime, using the popular libbacktrace library.
- [blockly-nelua](https://github.com/Rabios/blockly-nelua) - Blockly that generates Nelua.

### Math
- [lua-bint](https://github.com/edubart/lua-bint) - Small portable arbitrary-precision integer arithmetic library in pure Lua for computing with large integers.
- [manthkit](https://github.com/Rabios/nelua-fun/tree/main/mathkit) - a library for Vector, Quaternion and Matrices math.

### ffi
- [ffi](https://github.com/edubart/nelua-batteries) - Cross platform FFI for Nelua, you can use it to load symbols from shared libraries.

### Parsing
- [lpegrex](https://github.com/edubart/lpegrex) - Parse programming languages syntax into an AST using PEGs with ease (LPeg Extension).

### Package Manager
- [pancake-pm](https://github.com/linkpy/pancake-pm) - Simple pancake manager for Nelua.

### Web
- [NeluaWS](https://github.com/Elpersonn/NeluaWS/) - Simple webSocket program written in Nelua.
- [nelua-webview-demo](https://github.com/edubart/nelua-webview-demo) - An example using Nelua for WebView apps.

### Games
- [Alpinist VS The Alien Invasion in Mount Roraima](https://github.com/Andre-LA/alpinist-vs-the-mount-roraima-alien-invasion) - Game made for IGDFE Game Jam 2 made using Nene.
- [nelua-game2048](https://github.com/edubart/nelua-game2048) - Clone of the 2048 game in Nelua using Raylib.
- [nelua-tetris](https://github.com/edubart/nelua-tetris) - Tetris game clone in Nelua with Raylib.
- [Castle Escape](https://github.com/Andre-LA/baixada-game-jam-game/) - Game made for Baixada Game Jam, written in Nelua using Raylib.
- [Game Of Life in Arduino](https://gist.github.com/edubart/4991c5dd51205288519419f7d438adcf) - Game of Life coded in Arduino with Nelua.
- [Cesleste](https://gist.github.com/edubart/a79bf78a249d1fff2b77728c260c7605) - Celeste game clone in Nelua using SDL2.
- [nelua-Ping-Pong](https://github.com/AKDev21/nelua-ping-pong) - Ping Pong game in Nelua using Raylib.

### Game Development
- [nene](https://github.com/Andre-LA/nene) - Tiny game library built around SDL2 and it's extension libraries, written in Nelua.
- [raylib-nelua](https://github.com/Andre-LA/raylib-nelua) - Raylib wrapper for nelua, raylib - A simple and easy-to-use library to enjoy videogames programming.
- [Rotor-nelua](https://github.com/Andre-LA/Rotor-nelua-mirror) - Rotor is a set of libraries for doing ECS in Nelua.
- [irene](https://github.com/Andre-LA/irene) - A collection of systems and components for Rotor-nelua.
- [zlnl](https://github.com/darltrash/zlnl) - A minimalist RPG game engine made in nelua for c99.
- [sigil](https://github.com/Rabios/nelua-fun/tree/main/sigil) - Bindings of sigil for nelua, SIGIL - A very simple cross-platform library for playing audio, handling basic input, and drawing 2D graphics.

### Graphics
- [marcherstein3d](https://github.com/edubart/marcherstein3d) - Realtime pseudo 3D raycaster on the CPU using 2D ray marching.
- [nelua-raytracing](https://github.com/Andre-LA/nelua-raytracing-card-mirror) - Tiny raytracing that fits on a business card.
- [nprof](https://github.com/Andre-LA/nprof) - Very basic profiler for raylib-nelua.

### Window and Input
- [nelua-glfw](https://github.com/AKDev21/nelua-glfw) - GLFW bindings for nelua, GLFW - A multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input.
- [Xinput](https://github.com/Rabios/nelua-fun/tree/main/xinput) - Xinput bindings for nelua, Xinput - API enables applications to receive input from the Xbox Controller for Windows.

### IDE and Code Editor Support
- [nelua-lsp](https://github.com/codehz/nelua-lsp) - Langauge server plugin for nelua.
- [nelua-vscode](https://github.com/edubart/nelua-vscode) - Nelua syntax highlighting for Visual Studio Code.
- [nelua-sublime](https://github.com/edubart/nelua-sublime) - Nelua syntax highlighting for Sublime Text.
- [nelua-lite-xl](https://gist.github.com/Andre-LA/2f56f69bc7b3ac9042534bb2c831639b) - Nelua syntax highliting for Lite-xl.
- [nelua.vim](https://github.com/stefanos82/nelua.vim) - Nelua syntax highlighting for Vim.
- [micro-nelua-plugin](https://github.com/leapofazzam123/micro-nelua-plugin) - Nelua syntax highliting and linter for the micro text editor.
- [nelua-highlight](https://github.com/Enter1he/nelua-highlight) - Small syntax highlighter for nelua in vs-code.

### Testing
- [Lester](https://github.com/edubart/lester) - Lester is a minimal unit testing framework for Lua with a focus on being simple to use.
- [nester](https://github.com/edubart/nelua-batteries) - Minimal unit testing framework inspired by lester.

### Generating Documentation
- [nldoc](https://github.com/edubart/nldoc) - Tool to generate documentation for Nelua source files.

### Virtual Machines
- [riscvm](https://github.com/edubart/riscvm) - Tiny RISC-V virtual machine written in Nelua (and C as consequence).

### Operating Systems
- [nelua-osdev](https://github.com/radgeRayden/nelua-osdev-barebones) - An Operating System written in nelua.

### Live Development
- [luamon](https://github.com/edubart/luamon) - Live development utility for Lua inspired by nodemon.
- [forkmoon](https://github.com/edubart/forkmon) - Watch for file changes and auto restart an application using fork checkpoints to continue the process (for quick live development).


### Resources
- [nelua-by-example](https://github.com/nelua-by-example) - A tutorial for Nelua, based on examples.
- [nelua-samples](https://github.com/edubart/nelua-samples) - Some sample applications write in Nelua.
- [aoc202](https://github.com/edubart/aoc2020) - Advent of Code 2020 in Nelua.
- [lunray](https://github.com/edubart/lunray) - Ray tracing experiment in Nelua.

### Block Chain
- [NeChain](https://github.com/AliChraghi/NeChain) - A Single File Blockchain written in Nelua.

### Benchmarks
- [nelua-benchmarks](https://github.com/edubart/nelua-benchmarks) - Benchmarks for comparing efficiency of Nelua with Lua, LuaJIT and C.
- [realist](https://github.com/nsauzede/realist) - SDL2 raytracer + benchmark for Rust, Nelua, Nim, C, C++, Odin, V, Go.