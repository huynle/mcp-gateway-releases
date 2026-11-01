# mcp-gateway-releases

Public release binaries for **mcp-gateway**. The source repository is private; this repository holds
only the built release assets (archives, `checksums.txt`, `install.sh`) so clients can install without GitHub credentials.

## Install

```sh
brew install huynle/tap/mcp-gateway
# or
curl -fsSL https://github.com/huynle/mcp-gateway-releases/releases/latest/download/install.sh | sh
```

Verify any download against `checksums.txt` from the same release.

Releases here are mirrored automatically by the mcp-gateway release workflow. Do not edit or upload assets by hand.
