## Assemble The Awesome

**AssemblyScript Package, Project, and Resources List 🚀**
## Contents

- [Packages](#packages)
    - [Utility](#utility)
    - [Security](#security)
    - [Blockchain](#blockchain)
    - [Web](#web)
    - [Backend](#backend)
    - [Serialization](#serialization)
    - [Game Dev](#game-dev)
    - [Testing](#testing)
    - [Math/Numbers](#math-numbers)
    - [Transforms](#transforms)
    - [Build Tools](#build-tools)
    - [I/O](#io)
    - [Memory Tools](#memory-tools)
    - [Compression](#compression)
    - [WASI](#wasi)
    - [Lunatic VM](#lunatic-vm)
- [Projects](#projects)
- [Resources](#resources)
    - [Books](#books)
    - [Videos](#videos)
    - [Tutorials](#tutorials)
    - [Blogs](#blogs)
    - [Community](#community)

## Packages
#### Utility
- [as-container](https://github.com/JairusSW/assemble-the-awesome) - Rust-like `Result`` and `Option`` types
- [as-variant](https://github.com/MaxGraey/as-variant) - `Variant` type providing dynamicness
- [as-string-sink](https://github.com/MaxGraey/as-string-sink) - Efficient String Builder
- [as-random](https://github.com/MaxGraey/as-random) - Random number generators
#### Security
- [wasm-crypto](https://github.com/jedisct1/wasm-crypto) - Many hashing algorithms (not updated)
- [superfasthash](https://github.com/mjethani/superfasthash) - SuperFastHash implementation (unmaintained)
- [xoroshiro128starstar](https://github.com/krisselden/xoroshiro128starstar) - Port of xoroshiro128starstar.c
- [rabin-wasm](https://github.com/hugomrdias/rabin-wasm) - Port of Rabin Fingerprinting
#### Blockchain
- [subscript](https://github.com/ascontract/subscript) - Subscript blockchain SDK
- [biturbo](https://github.com/ewasm/biturbo) - Ethereum 1 EE using Turboproofs
#### Web
- [asdom](https://github.com/lume/asdom) - (WIP) DOM bindings
- [ecmassembly](https://github.com/aspkg/ecmassembly) - (Some) JavaScript APIs ported to AssemblyScript
#### Backend
#### Serialization
- [RLP](https://github.com/SteerProtocol/rlp) - RLP implementation (Private as of now)
- [as-json](https://github.com/JairusSW/as-json) - JSON implementation
- [karmem](https://github.com/inkeliz/karmem) - Fast binary serialization format
- [FASS](https://github.com/JairusSW/fass) - A blindingly fast schema-driven serialization format
- [as-proto](https://github.com/piotr-oles/as-proto) - Protobuf implementation
- [as-msgpack](https://github.com/wapc/as-msgpack) - MessagePack implementation
- [serial-as/borsh](https://github.com/gagdiez/serial-as/tree/main/borsh) - Borsh implementation
- [serial-as/json](https://github.com/gagdiez/serial-as/tree/main/json) - JSON implementation (unmaintained dependency)
- [assemblyscript-bson](https://github.com/nearprotocol/assemblyscript-bson) - BSON implementation (unmaintained)
- [assemblyscript-json](https://github.com/near/assemblyscript-json) - JSON implementation (unmaintained)
- [as-lzma](https://github.com/01alchemist/AS-LZMA) - LZMA implementation (unmaintained)
#### Game-Dev
- [VectorEngine](https://github.com/battlelinegames/VectorEngine) - Vector rendering engine. Retro style.
- [ASWebGlue](https://github.com/battlelinegames/ASWebGLue) - WebGL bindings
- [Koora](https://github.com/mrchantey/koora) - 3D game framework
#### Testing
- [as-pect](https://github.com/jtenner/as-pect) - Testing framework inspired by Jest
#### Math/Numbers
- [as-bignum](https://github.com/MaxGraey/as-bignum) - Fixed length big numbers
- [as-big](https://github.com/ttulka/as-big) - Arbitrary precision big numbers
- [as-bigint](https://github.com/polywrap/as-bigint) - Math with arbitrarily large integers
- [as-bignumber](https://github.com/polywrap/as-bignumber) - Arbitrary precision integers and decimals

#### Transforms
- [visitor-as](https://github.com/as-pect/visitor-as) - Tools to build transforms
#### Build-tools
#### IO
#### Memory Tools
- [as-malloc](https://github.com/fabriciopashaj/as-malloc) - Lightweight implementation of `malloc`, `realloc`, and `free` functions
#### Compression
#### WASI
- [wasi-shim](https://github.com/AssemblyScript/wasi-shim) - WASI Shim for AssemblyScript
#### Lunatic VM
- [as-lunatic](https://github.com/lunatic-solutions/as-lunatic) - A take on WASI adding Processes, Networking, IPC, and Distributed computing.
## Projects
- [Hoofdkantoor Demoscene](https://wasm-demo.codument.com/demo.html) - 90's Demoscene built with AssemblyScript
### Games
- [project-h](https://github.com/Tugcga/Project-H) - Game and experiment with paths
- [wasmboy](https://github.com/torch2424/wasmBoy) - GameBoy emulator
- [atari-2600](https://github.com/ColinEberhardt/atari2600-wasm) - Atari2600 emulator
- [wa-spectrum](https://github.com/Dotneteer/wa-spectrum-engine) - ZX Spectrum emulator
- [chess](https://github.com/mhonert/chess) - Wasabi chess engine implementation
- [gomoku](https://github.com/jolestar/gomoku-wasm) - Go(moku) engine implementation
- [breadcrumb-lost](https://github.com/ttulka/2d-videogame-in-assemblyscript) - A 2d platformer game
