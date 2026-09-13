# DAL CLI — Distribution

Build artifacts for the DAL CLI. No source lives here; every release is a tarball
attached to a [release](../../releases).

## Install

```bash
npm install -g https://github.com/DeepAILab-Team/dal-dist/releases/latest/download/deepailab-dal.tgz
dal
```

No account or registry configuration is needed. npm fetches the package straight
from this repository's CDN; its dependencies still resolve from the public npm
registry as usual.

Requires Node.js 22.19 or newer.

## Update

```bash
dal update
```

`dal` checks for new releases here on startup and reports them, but never
rewrites your global install without you asking.

## Pinning a version

Each release also carries a versioned tarball. To install a specific one:

```bash
npm install -g https://github.com/DeepAILab-Team/dal-dist/releases/download/v0.1.10/deepailab-dal-0.1.10.tgz
```
