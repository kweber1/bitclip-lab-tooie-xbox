# Bit-Clip Lab data: Banjo-Tooie · Xbox

Data files for the [Bit-Clip Lab](https://kweber1.github.io/bitclip-lab/tooie/?v=xbox) viewer (the viewer and the tools that make these files are in [kweber1/bitclip-lab](https://github.com/kweber1/bitclip-lab)). Each game version has its own repository so each gets its own 1 GB GitHub Pages site; the viewer loads from all of them on the same `kweber1.github.io` address.

The Xbox 360 (XBLA) census: the same exhaustive census as the N64 version, run with the 360 build's own float operations (fused multiply-adds, dot-product order; `tools/tooie/tcensus.cu -DTX360`, see `tools/tooie-xbox/README.md` in the main repository). It was checked in Xenia on 85 exact floats. Levels appear here as they finish.

Files end in `.wasm` so GitHub Pages serves the gzipped bytes as they are. No game art is published here.
