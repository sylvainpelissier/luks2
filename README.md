# luks2
[![GithubCI Status](https://github.com/sylvainpelissier/luks2/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/sylvainpelissier/luks2/actions/workflows/rust.yml?query=branch%3Amaster)

Interact with (currently: read metadata and data from) LUKS2 partitions from Rust.

Build with `RUSTFLAGS="-C target-feature=+aes"` to use the AES processor instruction set (if
available on your platform).

