# entities-godot-gdscript-compiler-demo

An engine project that runs a sandboxed script and compiles its source to a RISC-V program with the sandbox addon's in-guest compiler.

## What it is for

The main scene attaches a sandboxed script to a label and calls its methods, then loads the compiler program into a sandbox, compiles the same source and writes the result to `result_buffer.elf`. It exercises the compiler end to end inside the engine, with the addon's binaries checked in.

## Build and run

    godot --path .

The project needs a double-precision engine build.

## Licence

The licence is not stated.
