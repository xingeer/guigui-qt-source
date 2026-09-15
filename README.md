# GuiGui Qt 5.15.2 Source

This repository provides the Qt 5.15.2 source archive corresponding to the Qt libraries distributed with GuiGui Windows and macOS packages.

## Scope

- Qt version: 5.15.2
- Platforms: Windows x64 and x86; macOS Intel x86_64
- Windows: Microsoft Visual C++ 2019 Qt binaries, dynamically linked as DLLs
- macOS: Qt 5.15.2 OpenSource `clang_64` shared Frameworks and plugins, dynamically linked by GuiGui

The source archive is platform- and architecture-independent. The same archive applies to the corresponding Qt 5.15.2 libraries distributed with these GuiGui packages. Each platform's actual Qt files, architecture, and hashes are identified in the materials accompanying that package.

## Source Archive

- File: `qt-everywhere-src-5.15.2.zip`
- Size: `1009224272` bytes
- SHA256: `6c5d37aa96f937eb59fd4e9ce5ec97f45fbf2b5de138b086bdeff782ec661733`
- Release: [Qt 5.15.2 source for GuiGui Windows and macOS](https://github.com/xingeer/guigui-qt-source/releases/tag/qt-5.15.2-windows-msvc2019-x64)
- Qt upstream: [qt-everywhere-src-5.15.2.zip](https://download.qt.io/archive/qt/5.15/5.15.2/single/qt-everywhere-src-5.15.2.zip)

The provided archive is byte-for-byte identical to the Qt 5.15.2 source archive published by the Qt Project.

The Qt binaries covered by the current GuiGui Windows component manifests were verified against the official Qt 5.15.2 MSVC 2019 packages. No product-specific modifications to those Windows Qt binaries were identified. The macOS Qt binaries have a separate package-specific inventory, provenance comparison, and replacement record; the Windows comparison must not be applied to macOS binaries.

The archive includes Qt source code, build scripts, license materials, Qt WebEngine and Chromium source trees, and related third-party license materials. Independently distributed non-Qt components are outside the scope of this Qt archive.

This repository provides the corresponding Qt source materials. GuiGui's independently developed proprietary application source code is not part of Qt and is not included in this repository.

## Availability

This release and its source archive are intended to remain available for users of the corresponding GuiGui Windows and macOS packages. A new tag and release will be created if the distributed Qt version or corresponding Qt source is changed.
