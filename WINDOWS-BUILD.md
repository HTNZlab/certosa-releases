# Build Windows 0.3.8

The release source ZIP includes the Rust/Tauri wrapper, lockfiles, NSIS template,
license resources and the exact HTML/CSS/JavaScript frontend/media used for the native build.
Use an x64 Visual Studio Developer PowerShell with C++ Build Tools, Rust and Node.

1. Extract `Certosa-0.3.8-windows-sorgenti.zip` into a working directory.
2. Run `npm ci` in `packaging/tauri`.
3. Run `cargo fetch --locked` in `packaging/tauri/src-tauri` to populate the Cargo cache.
4. From the extracted root, run `powershell -File packaging/build-windows.ps1`.

The build script compiles offline after dependencies are fetched. It records
frontend, EXE and installer hashes in `dist/native-build.json`. The SDK/toolchain
and archive timestamps may differ from the published build; compare the included
frontend/source manifest and recorded provenance, not an assumed reproducible EXE hash.

The NSIS payload has the `NSS` bundle marker; the standalone EXE has `UNK`.
This is an expected three-byte bundler distinction. Both variants were tested.
The binaries are unsigned and require WebView2. Tests used isolated H: project
directories and synthetic encrypted archives; no personal notebooks were used.
