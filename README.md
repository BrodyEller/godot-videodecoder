# Godot Video Decoder

GDNative Video Decoder library for [Godot Engine](https://godotengine.org),
using the [ffmpeg](https://ffmpeg.org) library.

## Build Instructions

1. Clone the repository
	- `git clone https://github.com/BrodyEller/godot-videodecoder.git`
2. Install `ffmpeg` using your system package manager(pacman, homebrew, MSYS2, etc.)
	- **Note:** This will be changed in the future to use a custom build of `ffmpeg`
3. `cd` into the **godot-videodecoder** folder, and initialize the submodules:
	- `cd godot-videodecoder`
   - `git submodule update --init`
4. Use `scons` to build the project:
   - macOS: `scons platform=osx`
   - Linux: `scons platform=x11`
   - Windows: `scons platform=win64`
5. Copy and paste the **test/addons** folder into your Godot project
