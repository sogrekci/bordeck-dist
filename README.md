# BORDeck distribution

Files the BORDeck app downloads: OpenBOR engine builds today (official archives, and builds BORDeck makes for macOS from the official source); app releases and the update feed later. BORDeck checks every file it downloads from here against its SHA-256 before using it.

## Releases

Each release publishes files unchanged, with their source and SHA-256 in its notes. A published release is never replaced: a new file gets a new release.

| Release | File | SHA-256 | Source |
|---|---|---|---|
| `engine-openbor-7735-windows` | `openbor_7735.rar` | `874f6040cdfedfbca3dd7d4a5beb82e095f06dbe3862e9f08be5a069a817351b` | The official OpenBOR 4.0 Build 7735 archive from chronocrash.com (resource "OpenBOR"), published unchanged. It holds the Windows (`windows/OpenBOR-x86.exe`), Linux and Wii builds. |
| `engine-openbor-3994-macos` | `OpenBOR-3.0-Build-3994-macos.zip` | `bdc3f620f36b6db4910f29a4023a72c819662a6c6351d1343574935a5e907940` | OpenBOR 3.0 Build 3994 built for macOS by BORDeck from github.com/DCurrent/openbor commit 32d20cf7: universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |
| `engine-openbor-4011-macos` | `OpenBOR-3.0-Build-4011-macos.zip` | `fea347ff0dc5baa880bfcef2a01005f230ae8cc51551c16e8a6289863088ad72` | OpenBOR 3.0 Build 4011 built for macOS by BORDeck from github.com/DCurrent/openbor commit 4df56add: universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |
| `engine-openbor-4079-macos` | `OpenBOR-3.0-Build-4079-macos.zip` | `5a04a18078d975e6e48ee1a339ce0ec33488d380fa50c9f1367a460e8bd2bbd6` | OpenBOR 3.0 Build 4079 built for macOS by BORDeck from github.com/DCurrent/openbor commit d363087c: universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |
| `engine-openbor-4432-macos` | `OpenBOR-3.0-Build-4432-macos.zip` | `ad50123cb181c8121c1a60e253929d85e4afcbfac6e9c31323c29c1d0794a0f1` | OpenBOR 3.0 Build 4432 built for macOS by BORDeck from github.com/DCurrent/openbor commit 2566cbee: universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |
| `engine-openbor-4750-macos` | `OpenBOR-3.0-Build-4750-macos.zip` | `eea9e721bb27b5d0c413650c4610ff8508e134e1d0a0e65ae86655d39ddeee33` | OpenBOR 3.0 Build 4750 built for macOS by BORDeck from github.com/DCurrent/openbor commit 61ae161b (the history's nearest commit; the exact one is not known): universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |
| `engine-openbor-4905-macos` | `OpenBOR-3.0-Build-4905-macos.zip` | `7fb50e3736832d2277614263a7ab37556ac77fbab2881d19bb2da2041823592b` | OpenBOR 3.0 Build 4905 built for macOS by BORDeck from github.com/DCurrent/openbor commit df708746 (the history's nearest commit; the exact one is not known): universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |
| `engine-openbor-6119-macos` | `OpenBOR-3.0-Build-6119-macos.zip` | `a2cf0cce330dbf740895f30115d5aca48b4a3384e827ad60f9c3695c23f505f6` | OpenBOR 3.0 Build 6119 built for macOS by BORDeck from github.com/DCurrent/openbor commit 46a500b4: universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |
| `engine-openbor-6297-macos` | `OpenBOR-3.0-Build-6297-macos.zip` | `12ce2d1277f062ef144617fbc229f9e19fd376455196c893001e8dc75ff596c2` | OpenBOR 3.0 Build 6297 built for macOS by BORDeck from github.com/DCurrent/openbor commit 87245656: universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |
| `engine-openbor-6330-macos` | `OpenBOR-3.0-Build-6330-macos.zip` | `efea719d29514be18e67f8e6e1a1078e01f5c36cc4301550be85bd6183de4a9c` | OpenBOR 3.0 Build 6330 built for macOS by BORDeck from github.com/DCurrent/openbor commit 4b1705fa: universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |
| `engine-openbor-7142-macos` | `OpenBOR-4.0-Build-7142-macos.zip` | `009b03633dd83ff098096ab1d7833ec01e31d65287e44f5a5b8e7f2348fe3930` | OpenBOR 4.0 Build 7142 built for macOS by BORDeck from github.com/DCurrent/openbor commit 9dcd966d: universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |
| `engine-openbor-7533-macos` | `OpenBOR-4.0-Build-7533-macos.zip` | `766736d06d4e90ebd4a2cb500b679aac56b6fb4371ecf9c9a211bd9fd6d54aca` | OpenBOR 4.0 Build 7533 built for macOS by BORDeck from github.com/DCurrent/openbor commit 5c826144: universal (Apple silicon and Intel), macOS 12 or later, ad-hoc signed, licence texts in `licenses/` |

## Licences

OpenBOR is © the OpenBOR Team and contributors and is distributed under the BSD-3-Clause licence; its source is at [github.com/DCurrent/openbor](https://github.com/DCurrent/openbor). The engines also contain SDL2 (zlib License), SDL_gfx's frame rate code (zlib License; the macOS 3.0 builds), zlib (zlib License), libpng (libpng License), libogg and libvorbis (BSD-3-Clause) and libvpx (BSD-3-Clause). Each release lists the licence texts that apply to it in [licenses/](licenses/).
