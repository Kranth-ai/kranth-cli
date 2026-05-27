# kranth-cli

Premium interactive terminal client for [Kranth](https://kranth.com) — stress-test ideas against adversarial AI personas without leaving your shell.

> This repo hosts release binaries only. Source lives at [`Kranth-ai/kranth`](https://github.com/Kranth-ai/kranth) (private).

## Install

| Channel | Command | Status |
|---|---|---|
| **curl** (universal) | `curl -fsSL https://kranth.com/install.sh \| sh` | ✓ live |
| **npm** | `npm i -g @kranth/cli` | ✓ live |
| **Manual download** | [releases/latest](https://github.com/Kranth-ai/kranth-cli/releases/latest) | ✓ live |
| Homebrew | `brew install kranth-ai/tap/kranth` | ⏳ tap pending |
| Cargo | `cargo install kranth-cli` | ✓ live |

## Quick start

```bash
kranth login          # device-code browser handshake
kranth                # drop into the interactive shell
kranth run "<idea>"   # one-shot for scripting / CI
```

Try the canned walkthrough first (no API call, no credits burned):

```
▌ /demo
```

## Platforms

Each release ships five binaries + sha256 sidecars:

| Platform | Asset |
|---|---|
| Linux x86_64 (musl, static) | `kranth-x86_64-unknown-linux-musl` |
| Linux aarch64 (musl, static) | `kranth-aarch64-unknown-linux-musl` |
| macOS Intel | `kranth-x86_64-apple-darwin` |
| macOS Apple Silicon | `kranth-aarch64-apple-darwin` |
| Windows x86_64 | `kranth-x86_64-pc-windows-msvc.exe` |

## Docs

Full reference at [kranth.com/docs](https://kranth.com/docs) → CLI section.

## License

Apache-2.0 © Kranth, Inc.
