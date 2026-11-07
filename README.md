# Drover releases

Prebuilt Drover bundles (Linux x86_64/aarch64, macOS arm64/x86_64) and the installer.

Install or update:

```sh
curl -fsSL https://github.com/babymum7/drover-releases/releases/latest/download/get.sh | sh
```

On a machine reached over SSH (herdr-core only):

```sh
curl -fsSL https://github.com/babymum7/drover-releases/releases/latest/download/get.sh | sh -s -- --headless
```

Every release carries `SHA256SUMS`; `get.sh` checks the bundle against it. Afterwards, `drover update` keeps the machine current.
