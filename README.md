# Gnome Gold Web Prototypes

Browser-based prototypes created while exploring the Gnome Gold game concept. The repository keeps the real local prototypes together without presenting them as a production release.

## What is included

- `index.html` — the latest Gnome Gold Runner prototype.
- `prototypes/runner-v1.html` — the first runner iteration.
- `prototypes/runner-v2.html` — the second runner iteration.
- `prototypes/runner-v3.html` — the third runner iteration.
- `prototypes/gnome-raid.html` — an earlier raid and inventory interaction prototype.

The runner prototypes use Three.js from jsDelivr and keep demo state in the browser. Wallet-shaped input is used only as a local player identifier; these files do not connect to a wallet or call a smart contract.

## Run locally

Serve the repository with any static file server, then open the reported local URL. For example:

```bash
npx serve .
```

Open `index.html` for the latest runner, or a file under `prototypes/` to inspect an earlier iteration.

## Status and scope

This repository contains experimental web prototypes only. It does not include production infrastructure, deployed-contract source code, private keys, deployment credentials, or mainnet tooling.

## Repository structure

```text
.
|-- index.html
|-- prototypes/
|   |-- gnome-raid.html
|   |-- runner-v1.html
|   |-- runner-v2.html
|   `-- runner-v3.html
`-- README.md
```
