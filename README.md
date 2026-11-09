# BORDeck distribution

Files the BORDeck app downloads: OpenBOR engine builds today; app releases and the update feed later. BORDeck checks every file it downloads from here against its SHA-256 before using it.

## Releases

Each release publishes files unchanged, with their source and SHA-256 in its notes. A published release is never replaced: a new file gets a new release.

| Release | File | SHA-256 | Source |
|---|---|---|---|
| `engine-openbor-7735-windows` | `openbor_7735.rar` | `874f6040cdfedfbca3dd7d4a5beb82e095f06dbe3862e9f08be5a069a817351b` | The official OpenBOR 4.0 Build 7735 archive from chronocrash.com (resource "OpenBOR"), published unchanged. It holds the Windows (`windows/OpenBOR-x86.exe`), Linux and Wii builds. |

## Licences

OpenBOR is © the OpenBOR Team and contributors and is distributed under the BSD-3-Clause licence; its source is at [github.com/DCurrent/openbor](https://github.com/DCurrent/openbor). The engines also contain SDL2 (zlib License), zlib (zlib License), libpng (libpng License), libogg and libvorbis (BSD-3-Clause) and libvpx (BSD-3-Clause). Each release lists the licence texts that apply to it in [licenses/](licenses/).
