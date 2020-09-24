# d2x-xl-lightmaps
These are precomputed lightmaps for D2X-XL.  They were generated on a Mac using version 1.18.64, the most recent Mac release available right now, Descent 1 v1.5, Descent 2 v1.2, and Vertigo.

The `Lights` and `Meshes` directories contain data which are shared amongst all lightmaps, but the contents of the `Lightmaps` directory are divided according to quality settings, as some of the calculated lightmaps share filenames and overwrite other previously-calculated lightmaps.

For an actual installation, place the contents as follows (putting the `.lmapX` files directly in the `Lightmaps` location, not in a subdirectory):

macOS:
- `Lightmaps`: `~/Library/Caches/D2X-XL/Lightmaps`
- `Lights`: `~/Library/Caches/D2X-XL/Lights`
- `Meshes`: `~/Library/Caches/D2X-XL/Meshes`

Linux:
- TBD (please let me know if you have this info)

Windows:
- TBD (please let me know if you have this info)