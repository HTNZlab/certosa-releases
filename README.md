# Certosa — free and open source

**English** · [Italiano](README.it.md)

Certosa is a personal digital library for writing, reading and collecting ideas
in notebooks. Illustrated rooms give it the feel of a physical library, while
notebooks and passwords stay on your device.

Certosa is **free** and its code is **MIT licensed**. No account, email,
activation code, paid licence or trial expiry is required.

[Open Certosa](https://certosa.htnzlab.it/) ·
[Product page and downloads](https://htnzlab.it/prodotto/certosa)

## Certosa 0.3.10 — Windows and Web/PWA

Default writing follows one ruled line per text line. New notebooks use continuous
text; existing notebooks keep their saved mode. Switching modes preserves existing
page content, formatting, notes and media. Compatible with MCP alpha.3.

Text import grows a notebook beyond its initial pages up to the compatible limit
of 10,000 pages, then creates the next numbered volume. Independent pages retain
the layout of illustrated books. The settings explain both modes.

- [Windows x64 — installer](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.10/Certosa-0.3.10-windows-setup.exe)
- [Windows x64 — portable](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.10/Certosa-0.3.10-windows-portabile.zip)
- [Windows source: Rust/Tauri wrapper and embedded client frontend](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.10/Certosa-0.3.10-windows-sorgenti.zip)
- [Open the Web/PWA](https://certosa.htnzlab.it/)
- [Web/PWA package](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.10/Certosa-0.3.10-web.zip)
- [Offline HTML with client code](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.10/Certosa-0.3.10-offline.html)
- [SHA256SUMS](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.10/SHA256SUMS.txt) · [Windows manifest](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.10/MANIFEST-WINDOWS.json)
- [MCP 0.0.6-alpha.3](https://github.com/HTNZlab/certosa-mcp/releases/tag/v0.0.6-alpha.3)

Windows requires WebView2. Native-lite uses the device's speech voice; optional
TTS models are excluded. Binaries are unsigned. Tested on Windows 11 x64:
installer, portable app, encrypted archives, full restart, PNG/PDF/WAV roundtrip,
upgrade from 0.3.8, and library preservation during uninstall.

Keep **Certosa-dati** beside the portable EXE. Before updating, export a
password-protected `.certosa` backup. Preserve the data folder when replacing
the program. [Build from source](WINDOWS-BUILD.md).
PDF content, OCR and attachment filenames are not indexed.
Previous Linux packages remain in [release 0.3.4](https://github.com/HTNZlab/certosa-releases/releases/tag/v0.3.4).

## Pacchetti desktop precedenti — 0.3.4

[Download storici 0.3.4](https://github.com/HTNZlab/certosa-releases/releases/tag/v0.3.4).

## Your notebooks

Close and Put away save automatically. **Save now**, or Ctrl/Cmd+S, saves while
you write and confirms completion. JSON export can include a selection, a
notebook or the whole library; attachments are excluded by default. JSON is
not encrypted.

Before updating, removing the app or clearing browser data, use **Export
library (.certosa)** and keep the encrypted backup and its password outside
the app folder. HTNZLab cannot recover your password. The PWA stores data in
browser storage; installing it does not replace an external backup.

## Licence

Certosa's current free line is available under the [MIT licence](LICENSE.md).
You may use, study, modify and redistribute the code, including commercially,
while retaining its copyright and licence notices.

Fonts, libraries, voice models, recordings and other third-party components
retain their own licences. Their notices are included in the packages that
distribute them; Certosa's MIT licence does not replace those terms.

### Historical releases

GitHub releases `v0.1f-beta.1` and `v0.2beta.5` remain available as an archive
of the earlier beta. They are **not the current free distribution** and are
not retroactively relicensed: each old package remains subject to the licence
included when it was published.

For current use, choose the Web/PWA or the versioned desktop downloads.

This repository hosts public documentation and official releases.
