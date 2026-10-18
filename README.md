# iidx2bms fork

[简体中文](README.zh-CN.md) · English

This is my personal fork of [iidx2bms](https://github.com/Glebsin/iidx2bms), kept **only** as an internal
component of the [LR2oraja Endless Dream](https://github.com/seraxis/lr2oraja-endlessdream) environment
I run locally. This repository is not affiliated with either of those projects, and it is not meant for
anyone else.

## Branches

- **`orajaroot`**: the read-only plugin dependency used by the LDJ side; do not modify.
- **`orajaroot-plus`**: the branch for the LDJPlus direct-read work; this README describes it.

## What this branch is

`orajaroot-plus` is a trimmed, non-interactive variant of the upstream project: the GUI application, the
packaging script and icon, and the unused `ifs_unpack` module have been dropped.

Runtime dependencies:

- `ifstools`: an external Python dependency, installed separately (`pip install ifstools`)
- `ffmpeg/ffmpeg.exe`: too large for the repository, so it is placed manually; only needed when an
  old-style `.s3p` contains WMA keysounds

## Copyright notice

- This repository does not provide any patch, key or method for breaking, bypassing or decrypting any
  protection or encryption.
- It does not provide links to, or information about, where game data can be obtained.
- It provides no setup, usage, conversion or troubleshooting guides.
- No license is granted for any part of this repository. I claim no rights over any third-party or
  game-derived content it contains or references; that content remains the property of its respective
  rights holders, and is not licensed, distributed or supported here.
- Upstream iidx2bms and the helper tools bundled with it remain the property of their respective authors.

> [!CAUTION]
> Don't use this to play non-permitted copyrighted contents.
