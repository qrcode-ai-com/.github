<p align="center">
  <a href="https://qrcode-ai.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" type="image/webp" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/hero-dark.webp?v=0a67e843852c">
      <source type="image/webp" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/hero-light.webp?v=6943a20dfb9a">
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/hero-dark.gif?v=6e29b48a0fd0">
      <img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/hero-light.gif?v=8947fe5daa3e" alt="QR Code AI, open source: open-source QR code and barcode scanning. One Rust engine sweeps a QR code and a barcode, and a dial rates how reliably each one reads." width="100%">
    </picture>
  </a>
</p>

# QR Code AI

**Open-source QR code and barcode technology.**

[QR Code AI](https://qrcode-ai.com) is an online [QR code generator](https://qrcode-ai.com/en-US/qr-code-generator) and [barcode generator](https://qrcode-ai.com/en-US/barcode-generator), with [custom designs](https://qrcode-ai.com/en-US/custom-qr-code), [QR code art](https://qrcode-ai.com/en-US/qr-code-art) and [scan tracking](https://qrcode-ai.com/en-US/tracking). This organization is where its technology is published as open source.

It starts with **[QR Code & Barcode Scanner](https://github.com/qrcode-ai-com/qrcode-barcode-scanner)**: one Rust engine that reads QR codes and barcodes from images and camera frames, entirely on your device. More of QR Code AI will be published here as open source.

**[Scanner source](https://github.com/qrcode-ai-com/qrcode-barcode-scanner)** · [Get started](https://github.com/qrcode-ai-com/qrcode-barcode-scanner#get-started) · [Examples](https://github.com/qrcode-ai-com/qrcode-barcode-scanner#examples) · [Releases](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/releases) · [Distribution guide](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md) · [qrcode-ai.com](https://qrcode-ai.com)

## One engine for QR codes and barcodes

<p align="center">
  <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner#supported-formats"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/engine-qr-codes-dark.gif?v=5e6c352d1b6e"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/engine-qr-codes-light.gif?v=956ef36870af" alt="QR codes, read by the one engine: QR Code, Micro QR and rMQR, from everyday prints to artistic designs. An image is dropped on the reader and its QR code is read as a link." width="49%"></picture></a>
  <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner#supported-formats"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/engine-barcodes-dark.gif?v=a726665fa990"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/engine-barcodes-light.gif?v=0ac6abf92b91" alt="Barcodes, read by the same engine: EAN, UPC, Code 128, Data Matrix, PDF417 and more, in the same scan. A phone camera reads the barcode of a label." width="49%"></picture></a>
</p>

A QR code and a barcode are read by the same engine, in the same scan. An image that holds a QR code and a Code 128 label returns both, each with its value and its format, and its position when available. There is one scanner to install, whichever code you read.

| Family | Formats |
| --- | --- |
| QR | QR Code, Micro QR, rectangular Micro QR (rMQR) |
| Matrix and stacked | Data Matrix, Aztec, PDF417, MaxiCode |
| Retail | EAN-13, EAN-8, UPC-A, UPC-E |
| Other linear | Code 128, Code 39, Code 93, Codabar, ITF, GS1 DataBar, GS1 DataBar Expanded, Telepen |

The engine also scores how reliably a QR design can be read, a check QR Code AI uses before export.

| | QR codes | Barcodes |
| --- | --- | --- |
| **Try the scanner live** | [QR code scanner](https://qrcode-ai.com/en-US/qr-code-scanner) | [Barcode scanner](https://qrcode-ai.com/en-US/barcode-scanner) |
| **Developer guide** | [QR code scanner SDK](https://qrcode-ai.com/en-US/qr-code-scanner/sdk) | [Barcode scanner SDK](https://qrcode-ai.com/en-US/barcode-scanner/sdk) |
| **Create a code** | [QR code generator](https://qrcode-ai.com/en-US/qr-code-generator) | [Barcode generator](https://qrcode-ai.com/en-US/barcode-generator) |

## Install it from the tools you already use

<p align="center">
  <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/destinations-dark.png?v=aac80a06a2b0">
      <img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/destinations-light.png?v=4443be3d3592" alt="Where the engine is published: crates.io, npm, PyPI, Go, Homebrew, Scoop, GitHub Releases, Debian, Arch Linux, Fedora, AppImage, a container image, MCP, OpenClaw, jsDelivr, UNPKG, esm.sh, docs.rs, deps.dev, Libraries.io and Lib.rs." width="100%">
    </picture>
  </a>
</p>

The engine is published where developers already install software. Choose by where the image is handled: inside your application, in a terminal, in a container or through an AI agent. Every route runs the same engine and returns its report.

### Runtime packages

<p align="center">
  <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner#get-started">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/journey-packages-dark.gif?v=d9871ce2185d">
      <img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/journey-packages-light.gif?v=f5d9eb652fc4" alt="Scan inside your application, in Rust, Node.js, browser WASM or Python, in three steps: install and initialize, pass an image or a camera frame, read the result." width="100%">
    </picture>
  </a>
</p>

| Runtime | Install | Published on |
| :---: | --- | --- |
| <a href="https://crates.io/crates/qrcode-barcode-scanner"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-rust-dark.png?v=29c91f35ae96"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-rust-light.png?v=dfee0b65843e" alt="crates.io" width="40" height="40"></picture></a><br>**Rust** | `cargo add qrcode-barcode-scanner` | [crates.io](https://crates.io/crates/qrcode-barcode-scanner) · API on [docs.rs](https://docs.rs/qrcode-barcode-scanner) |
| <a href="https://www.npmjs.com/package/@qrcode-ai-com/qrcode-barcode-scanner"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-npm-dark.png?v=579ee1c41857"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-npm-light.png?v=9e18ac1e844b" alt="npm" width="40" height="40"></picture></a><br>**Node.js** | `npm install @qrcode-ai-com/qrcode-barcode-scanner` | [npm](https://www.npmjs.com/package/@qrcode-ai-com/qrcode-barcode-scanner) · native macOS, Linux, Windows |
| <a href="https://www.npmjs.com/package/@qrcode-ai-com/qrcode-barcode-scanner-wasm"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-npm-dark.png?v=579ee1c41857"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-npm-light.png?v=9e18ac1e844b" alt="npm" width="40" height="40"></picture></a><br>**Browser** | `npm install @qrcode-ai-com/qrcode-barcode-scanner-wasm` | [npm](https://www.npmjs.com/package/@qrcode-ai-com/qrcode-barcode-scanner-wasm) · WASM and camera components |
| <a href="https://pypi.org/project/qrcode-barcode-scanner/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-pypi-dark.png?v=9eb9542e6e4b"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-pypi-light.png?v=efc51e4ad58b" alt="PyPI" width="40" height="40"></picture></a><br>**Python** | `python -m pip install qrcode-barcode-scanner` | [PyPI](https://pypi.org/project/qrcode-barcode-scanner/) |
| <a href="https://pkg.go.dev/github.com/qrcode-ai-com/qrcode-barcode-scanner-go"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-go-dark.png?v=adad0b7cccbc"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-go-light.png?v=b903f161f3b7" alt="Go" width="40" height="40"></picture></a><br>**Go** | `go get github.com/qrcode-ai-com/qrcode-barcode-scanner-go` | [pkg.go.dev](https://pkg.go.dev/github.com/qrcode-ai-com/qrcode-barcode-scanner-go) · drives `qrscan` |
| <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner-php"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-github-dark.png?v=1beef6411e01"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-github-light.png?v=84629428944a" alt="GitHub" width="40" height="40"></picture></a><br>**PHP** | [Source and guide](https://github.com/qrcode-ai-com/qrcode-barcode-scanner-php#readme) | [GitHub](https://github.com/qrcode-ai-com/qrcode-barcode-scanner-php) · drives `qrscan` |

The Rust, Node.js, browser and Python packages hold the engine. The Go and PHP packages hold no decoder: each one drives the installed `qrscan` command and returns its report.

### Command line

<p align="center">
  <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner#command-line">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/journey-cli-dark.gif?v=ea1650c40454">
      <img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/journey-cli-light.gif?v=1e7d191ba337" alt="Scan from a terminal or a script, installed with Homebrew, Scoop, Debian, Arch, Fedora or AppImage, in three steps: choose the image, read the report and status, pass the result to your script." width="100%">
    </picture>
  </a>
</p>

`qrscan` is the engine as a command: it reads an image file and prints a JSON report.

| Channel | Install | Platforms |
| :---: | --- | --- |
| <a href="https://github.com/qrcode-ai-com/homebrew-tap"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-homebrew-dark.png?v=d408ba800294"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-homebrew-light.png?v=bf1ed0794d75" alt="Homebrew" width="40" height="40"></picture></a><br>**[Homebrew](https://github.com/qrcode-ai-com/homebrew-tap)** | `brew install qrcode-ai-com/tap/qrscan` | macOS and GNU/Linux |
| <a href="https://github.com/qrcode-ai-com/scoop-bucket"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-scoop-dark.png?v=acab24ad6857"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-scoop-light.png?v=53f0fc5cfb45" alt="Scoop" width="40" height="40"></picture></a><br>**[Scoop](https://github.com/qrcode-ai-com/scoop-bucket)** | `scoop bucket add qrcode-ai https://github.com/qrcode-ai-com/scoop-bucket`<br>`scoop install qrcode-ai/qrcode-barcode-scanner` | Windows x64 |
| <a href="https://crates.io/crates/qrcode-barcode-scanner-cli"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-rust-dark.png?v=29c91f35ae96"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-rust-light.png?v=dfee0b65843e" alt="crates.io" width="40" height="40"></picture></a><br>**[Cargo](https://crates.io/crates/qrcode-barcode-scanner-cli)** | `cargo install qrcode-barcode-scanner-cli --locked` | Any Rust toolchain |
| <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner/releases"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-github-dark.png?v=1beef6411e01"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-github-light.png?v=84629428944a" alt="GitHub Releases" width="40" height="40"></picture></a><br>**[Releases](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/releases)** | [Download and verify an archive](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/cli/README.md#download-and-verify) | macOS, GNU/Linux, Windows |
| <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md#cli-and-containers"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-debian-dark.png?v=fe0bc2eb1292"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-debian-light.png?v=b0dbf95cf37d" alt="Debian" width="40" height="40"></picture></a><br>**Debian** | [Install the `.deb` package](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md#cli-and-containers) | Debian 12, Ubuntu 24.04 |
| <a href="https://aur.archlinux.org/packages/qrcode-barcode-scanner-bin"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-archlinux-dark.png?v=a5c779b6e553"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-archlinux-light.png?v=321428bf3921" alt="Arch Linux" width="40" height="40"></picture></a><br>**[AUR](https://aur.archlinux.org/packages/qrcode-barcode-scanner-bin)** | [Arch install guide](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/aur/README.md) | Arch Linux x86_64 |
| <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md#cli-and-containers"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-fedora-dark.png?v=cf9efdf2c0c6"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-fedora-light.png?v=6376f4214086" alt="Fedora" width="40" height="40"></picture></a><br>**Fedora** | [Install the RPM package](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md#cli-and-containers) | Fedora 44 |
| <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md#cli-and-containers"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-appimage-dark.png?v=b2fb5a4f1434"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-appimage-light.png?v=f8bcfd877cc8" alt="AppImage" width="40" height="40"></picture></a><br>**AppImage** | [Run the AppImage](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md#cli-and-containers), one file with nothing to install | GNU/Linux |

### Containers

<p align="center">
  <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md#cli-and-containers">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/journey-containers-dark.gif?v=ed8653255d6d">
      <img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/journey-containers-light.gif?v=6d1da6200234" alt="Run the scanner in a container from GitHub Container Registry, on Linux AMD64 or ARM64, in three steps: choose the version and architecture, mount the image file, read the result on the host." width="100%">
    </picture>
  </a>
</p>

| Registry | Image | Platforms |
| :---: | --- | --- |
| <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner/pkgs/container/qrcode-barcode-scanner"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-docker-dark.png?v=111f4320e3a8"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-docker-light.png?v=0e33dac05ba7" alt="Container image" width="40" height="40"></picture></a><br>**GHCR** | [`ghcr.io/qrcode-ai-com/qrcode-barcode-scanner`](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/pkgs/container/qrcode-barcode-scanner) on GitHub Container Registry. The [container guide](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md#cli-and-containers) shows how to run it. | Linux AMD64 and ARM64 |

### AI agents

<p align="center">
  <a href="https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/distribution/README.md#published-agent-integrations">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/journey-agents-dark.gif?v=1969e449552b">
      <img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/journey-agents-light.gif?v=7e6d8bc897db" alt="Give your agent a scanner, as an MCP server on npm, an OpenClaw plugin or a portable skill, in three steps: connect the host and choose the tool, send the image to the server, review the report." width="100%">
    </picture>
  </a>
</p>

| Integration | Published as | Set up |
| :---: | --- | --- |
| <a href="https://www.npmjs.com/package/@qrcode-ai-com/qrcode-barcode-scanner-mcp"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-mcp-dark.png?v=c72c5de9be05"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-mcp-light.png?v=6c123f2fc1a5" alt="MCP" width="40" height="40"></picture></a><br>**MCP server** | [`@qrcode-ai-com/qrcode-barcode-scanner-mcp`](https://www.npmjs.com/package/@qrcode-ai-com/qrcode-barcode-scanner-mcp) on npm, listed in the [Official MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers/io.github.qrcode-ai-com%2Fqrcode-barcode-scanner/versions/latest) | [MCP installation](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/tree/main/integrations/mcp) |
| <a href="https://clawhub.ai/qrcode-ai-com/skills/qrcode-barcode-scanner"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-openclaw-dark.png?v=9fcbd222bc5c"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-openclaw-light.png?v=f92868642883" alt="ClawHub" width="40" height="40"></picture></a><br>**Portable skill** | [`qrcode-barcode-scanner`](https://clawhub.ai/qrcode-ai-com/skills/qrcode-barcode-scanner) on ClawHub | [Skill instructions](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/tree/main/skills/qrcode-barcode-scanner) |
| <a href="https://clawhub.ai/qrcode-ai-com/plugins/qrcode-barcode-scanner"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-openclaw-dark.png?v=9fcbd222bc5c"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-openclaw-light.png?v=f92868642883" alt="OpenClaw" width="40" height="40"></picture></a><br>**OpenClaw plugin** | [`@qrcode-ai-com/qrcode-barcode-scanner`](https://clawhub.ai/qrcode-ai-com/plugins/qrcode-barcode-scanner) on ClawHub | [Plugin setup](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/tree/main/integrations/openclaw) |

### Browser CDNs and package indexes

| <a href="https://www.jsdelivr.com/package/npm/@qrcode-ai-com/qrcode-barcode-scanner-wasm"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-jsdelivr-dark.png?v=704e9fe56573"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-jsdelivr-light.png?v=8258a3d2624c" alt="jsDelivr" width="40" height="40"></picture></a> | <a href="https://unpkg.com/browse/@qrcode-ai-com/qrcode-barcode-scanner-wasm/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-unpkg-dark.png?v=9240e361b8bd"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-unpkg-light.png?v=ab42a30b0c3a" alt="UNPKG" width="40" height="40"></picture></a> | <a href="https://esm.sh/@qrcode-ai-com/qrcode-barcode-scanner-wasm"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-esm-dark.png?v=f28f1715017a"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-esm-light.png?v=24d30c1c4ac7" alt="esm.sh" width="40" height="40"></picture></a> | <a href="https://docs.rs/qrcode-barcode-scanner"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-docsrs-dark.png?v=a4db02014c02"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-docsrs-light.png?v=cb7d97c77d8f" alt="docs.rs" width="40" height="40"></picture></a> | <a href="https://deps.dev/npm/%40qrcode-ai-com%2Fqrcode-barcode-scanner"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-depsdev-dark.png?v=e866b7c993df"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-depsdev-light.png?v=3ae40490d86f" alt="deps.dev" width="40" height="40"></picture></a> | <a href="https://libraries.io/npm/@qrcode-ai-com%2Fqrcode-barcode-scanner"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-librariesio-dark.png?v=fb6425afbe1c"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-librariesio-light.png?v=2c6f9781f3cd" alt="Libraries.io" width="40" height="40"></picture></a> | <a href="https://lib.rs/crates/qrcode-barcode-scanner"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-librs-dark.png?v=cbc60370271d"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/mark-librs-light.png?v=59a27a02a142" alt="Lib.rs" width="40" height="40"></picture></a> |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [jsDelivr](https://www.jsdelivr.com/package/npm/@qrcode-ai-com/qrcode-barcode-scanner-wasm) | [UNPKG](https://unpkg.com/browse/@qrcode-ai-com/qrcode-barcode-scanner-wasm/) | [esm.sh](https://esm.sh/@qrcode-ai-com/qrcode-barcode-scanner-wasm) | [docs.rs](https://docs.rs/qrcode-barcode-scanner) | [deps.dev](https://deps.dev/npm/%40qrcode-ai-com%2Fqrcode-barcode-scanner) | [Libraries.io](https://libraries.io/npm/@qrcode-ai-com%2Fqrcode-barcode-scanner) | [Lib.rs](https://lib.rs/crates/qrcode-barcode-scanner) |
| Browser CDN | Browser CDN | Browser CDN | Rust API | Package index | Package index | Crate index |

The CDNs serve the npm browser package. The indexes describe the packages published to npm and crates.io.

<sub>Platform names and logos belong to their owners. They show where the packages are published and imply no endorsement.</sub>

## Create the codes it reads

<p align="center">
  <a href="https://qrcode-ai.com/en-US/qr-code-generator"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/create-qr-code-dark.gif?v=c151500f5b38"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/create-qr-code-light.gif?v=b9f3cf07ff50" alt="QR code generator on qrcode-ai.com: design a QR code with your logo, shape and colors." width="49%"></picture></a>
  <a href="https://qrcode-ai.com/en-US/barcode-generator"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/create-barcode-dark.gif?v=3864666d3b3d"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/create-barcode-light.gif?v=cb0b9d9b9bc7" alt="Barcode generator on qrcode-ai.com: create EAN, UPC, Code 128 and Code 39 labels." width="49%"></picture></a>
</p>

Reading a code is half of its life. On [qrcode-ai.com](https://qrcode-ai.com) you create the QR codes and barcodes that scanners read, then follow how they are used.

| | On qrcode-ai.com |
| --- | --- |
| **QR codes** | [QR code generator](https://qrcode-ai.com/en-US/qr-code-generator) · [Custom QR code with logo and colors](https://qrcode-ai.com/en-US/custom-qr-code) · [QR code templates](https://qrcode-ai.com/en-US/custom-qr-code/templates) · [QR code art](https://qrcode-ai.com/en-US/qr-code-art) · [QR code art templates](https://qrcode-ai.com/en-US/qr-code-art/templates) |
| **QR code types** | [Link](https://qrcode-ai.com/en-US/qr-code-generator/link) · [Wi-Fi](https://qrcode-ai.com/en-US/qr-code-generator/wifi) · [vCard](https://qrcode-ai.com/en-US/qr-code-generator/vcard) · [PDF](https://qrcode-ai.com/en-US/qr-code-generator/pdf) · [Menu](https://qrcode-ai.com/en-US/qr-code-generator/menu) · [WhatsApp](https://qrcode-ai.com/en-US/qr-code-generator/whatsapp) · [Email](https://qrcode-ai.com/en-US/qr-code-generator/email) · [SMS](https://qrcode-ai.com/en-US/qr-code-generator/sms) · [Text](https://qrcode-ai.com/en-US/qr-code-generator/text) · [GitHub](https://qrcode-ai.com/en-US/qr-code-generator/github) |
| **Barcodes** | [Barcode generator](https://qrcode-ai.com/en-US/barcode-generator) · [Code 128](https://qrcode-ai.com/en-US/barcode-generator/code-128) · [EAN-13](https://qrcode-ai.com/en-US/barcode-generator/ean-13) · [UPC-A](https://qrcode-ai.com/en-US/barcode-generator/upc-a) · [Data Matrix](https://qrcode-ai.com/en-US/barcode-generator/data-matrix) · [GS1-128](https://qrcode-ai.com/en-US/barcode-generator/gs1-128) · [ITF-14](https://qrcode-ai.com/en-US/barcode-generator/itf-14) · [Code 39](https://qrcode-ai.com/en-US/barcode-generator/code-39) |
| **After the scan** | [QR code tracking and analytics](https://qrcode-ai.com/en-US/tracking) · [URL shortener](https://qrcode-ai.com/en-US/url-shortener) · [Deep link generator](https://qrcode-ai.com/en-US/deep-link-generator) · [UTM builder](https://qrcode-ai.com/en-US/utm-builder) |
| **Learn** | [What is a QR code?](https://qrcode-ai.com/en-US/qr-code) · [What is a barcode?](https://qrcode-ai.com/en-US/barcode) · [All features](https://qrcode-ai.com/en-US/features) |

## Open source

- **License.** The scanner's project-authored source is under the MIT License; published archives retain their packaged license. The [licensing guide](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/LICENSING.md) gives the detail.
- **Contributing.** Read the [contribution guide](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/CONTRIBUTING.md) and the [code of conduct](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/CODE_OF_CONDUCT.md). Report a vulnerability through the [security policy](https://github.com/qrcode-ai-com/qrcode-barcode-scanner/blob/main/SECURITY.md).
- **What comes next.** The scanner is the first project published here. More of QR Code AI will follow as open source: follow [qrcode-ai-com](https://github.com/qrcode-ai-com) to see it arrive.

| Repository | Content |
| --- | --- |
| [qrcode-barcode-scanner](https://github.com/qrcode-ai-com/qrcode-barcode-scanner) | The QR code and barcode scanner engine, in Rust, with its packages, command and agent integrations. |
| [qrcode-barcode-scanner-go](https://github.com/qrcode-ai-com/qrcode-barcode-scanner-go) | Go package that reads images through the installed `qrscan` command. |
| [qrcode-barcode-scanner-php](https://github.com/qrcode-ai-com/qrcode-barcode-scanner-php) | PHP package that reads images through the installed `qrscan` command. |
| [homebrew-tap](https://github.com/qrcode-ai-com/homebrew-tap) | Homebrew tap for the `qrscan` command on macOS and Linux. |
| [scoop-bucket](https://github.com/qrcode-ai-com/scoop-bucket) | Scoop bucket for the `qrscan` command on Windows. |

## Contact

For product questions, partnerships or feedback, write to [contact@qrcode-ai.com](mailto:contact@qrcode-ai.com).

**[qrcode-ai.com](https://qrcode-ai.com)** · [QR code generator](https://qrcode-ai.com/en-US/qr-code-generator) · [Barcode generator](https://qrcode-ai.com/en-US/barcode-generator) · [QR code scanner](https://qrcode-ai.com/en-US/qr-code-scanner) · [Barcode scanner](https://qrcode-ai.com/en-US/barcode-scanner)

<p align="center">
  <a href="https://qrcode-ai.com"><img src="https://raw.githubusercontent.com/qrcode-ai-com/.github/main/profile/assets/footer.png?v=655cf7dcccb5" alt="QR Code AI, a SuperNovae Studio product." width="100%"></a>
</p>

<sub>QR Code AI · A SuperNovae Studio product.</sub>
