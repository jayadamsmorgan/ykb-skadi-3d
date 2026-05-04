# YKB Skadi 3D files

## Build

Clone repository with its submodules:

```bash
git clone https://github.com/jayadamsmorgan/ykb-skadi-3d --recursive
```
Build:

```bash
meson setup build
meson compile -C build
```

Run:

```bash
./build/skadi
```
This will generate OpenSCAD files in `output/scad` directory.

## Generate STL

```bash
./gen_stl.sh
```

This will generate STL files with OpenSCAD in `output/stl` directory.
