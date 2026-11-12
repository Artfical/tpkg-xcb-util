# xcb-util

xcb-util libraries: icccm, ewmh, image, keysyms, render-util, cursor (what Qt and window managers use on top of libxcb)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install xcb-util
```

| | |
|---|---|
| Version | 0.4.1 |
| Licence | MIT |
| Upstream | https://xcb.freedesktop.org |
| Needs | [`xorg`](https://github.com/Artfical/tpkg-xorg), [`xcb-libs`](https://github.com/Artfical/tpkg-xcb-libs) |
| Needs tOS build | 618 or newer |
| Size | 61256 bytes (233594 unpacked) |
| SHA-256 of the `.tpkg` | `02aac32396896ffe340fcd5f059797c3164870cec4443c025fe3ef10d3a75b59` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`xcb-util-0.4.1.tpkg`) and the sources it was built from are the assets of the
[v0.4.1 release](https://github.com/Artfical/tpkg-xcb-util/releases/tag/v0.4.1).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `xcb-util-0.4.1.tar.xz`
- `xcb-util-image-0.4.1.tar.xz`
- `xcb-util-keysyms-0.4.1.tar.xz`
- `xcb-util-renderutil-0.3.10.tar.xz`
- `xcb-util-wm-0.4.2.tar.xz`
- `xcb-util-cursor-0.1.5.tar.xz`

Check a download: `sha256sum xcb-util-0.4.1.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: MIT. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
