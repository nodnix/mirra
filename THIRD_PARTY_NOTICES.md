# Mirra Third-party Software Notices

[简体中文](THIRD_PARTY_NOTICES.zh-CN.md) | English

Mirra is a closed-source product that includes third-party software under separate licenses. Copyright in those components belongs to their respective rights holders. Mirra's product terms do not override their licenses.

## Main components

- **Qt 6.10.2:** Distributed using the LGPL-3.0 open-source license option and dynamic linking. The actual modules and plugins are listed in the license materials included with each platform's release package.
- **FFmpeg 7.1.2:** The Qt Multimedia backend may distribute FFmpeg runtime libraries. Release builds are prepared under an LGPL-2.1-or-later configuration, without substituting GPL or nonfree builds.
- **Fraunhofer FDK AAC 2.0.3:** Used to decode AAC-ELD audio on Windows. Its original license notice applies and does not grant patent rights.
- **Go and Go dependencies:** Covered by the separate licenses of Go and each dependency.

## Complete materials

Official release packages for each platform should include the full third-party copyright notices, license texts, information on obtaining corresponding source code, and library replacement instructions where applicable:

- macOS: `Mirra.app/Contents/Resources/licenses/`
- Windows: `licenses/` in the extracted Mirra portable package

This page is a readable summary, not a replacement for the complete license materials in the release package. The actual distributed components, versions, and original licenses in the relevant Release package control.

For your rights to modify, replace, relink, and debug third-party software, see [Open-source Software Rights](OPEN_SOURCE_RIGHTS.md).
