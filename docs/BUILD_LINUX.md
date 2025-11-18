# Zeronsd Linux ARM64 package build

This document describes how to build the Linux ARM64 `.deb` package for Zeronsd.

## Build steps

```bash
cargo build --release
cargo deb
