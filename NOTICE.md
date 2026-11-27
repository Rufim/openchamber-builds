# Notice

These builds are unofficial. They are not made, endorsed or supported by the
OpenChamber authors.

They are derived from [openchamber/openchamber](https://github.com/openchamber/openchamber)
at tag `v2.8.1`, distributed under the MIT License; the full license text is in
LICENSE (Copyright (c) 2025 Bohdan Triapitsyn).

Changes made for these builds:

- Russian locale (`ru.json`) compiled into the i18n dictionaries before the build;
- a local patch that stops the client from releasing OpenCode locations
  (`debug.location.evict`), because it canceled server-side interactions that
  the renderer did not know about.

The packaged application also bundles Electron/Chromium, OpenCode and other
components under their own licenses, included with the application files.
