# Fragmenta wheels

Python wheels built for [Fragmenta](https://github.com/MAz-Codes/Fragmenta) where upstream doesn't publish one. Fragmenta's installer downloads them from the [releases](https://github.com/MAz-Codes/Fragmenta-wheels/releases) here and checks each file against a hash pinned in its lock files. You don't need to install anything from this repo yourself.

| Package | Version | Platforms | Why it's here | License |
|---|---|---|---|---|
| flash-attn | 2.8.3.post2 | Linux x86_64, Windows x64 (NVIDIA, RTX 30 series or newer) | No Python 3.14 wheels upstream | BSD-3-Clause |
| python-rtmidi | 1.5.8 | Linux x86_64, Windows x64, macOS arm64 | No Python 3.14 wheels upstream | MIT; bundles LGPL-2.1-or-later libjack on Linux |

Each release lists how its wheels were built, with their checksums in `SHA256SUMS`. The wheels are built from unmodified upstream source and stay under their upstream licenses, which are included in the wheels and release assets.
