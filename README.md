# Visual Client Community

Copyright (c) 2026 Alatic. Released under the MIT licence. Reuse is permitted; retain the copyright and licence notice in redistributed copies or substantial portions. Third-party components retain their own notices.

## Install
Use Minecraft Java 1.21.11, Java 21, Fabric Loader 0.18.4 or newer, and Fabric API 0.141.3+1.21.11. Put the separately supplied community JAR in your instance's mods folder. Right Shift opens the GUI. No account, licence key or launcher is required.

## Build
Install a JDK 21, then run `./gradlew build` (Windows: `gradlew.bat build`). The installable Fabric JAR is in `build/libs/`; use the normal JAR, not the `-sources` JAR. The build retrieves public Fabric/Minecraft dependencies. Local configs support saving, loading, import and export; no hosted config service is used.

## Scope
This edition excludes World Shaders, Party and Tomorrowland. Authentication, licence checks, hardware identification, private server integrations, protection tooling, development captures and production data are not part of this release. Other visual modules remain included.

The optional Windows media-session bridge has source in `native/windows-media/`. Other platforms keep the remaining music providers. See THIRD-PARTY-NOTICES.md and bundled font notices for third-party credits.
