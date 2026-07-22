# James IDE

<p align="center">
  <b>A premium, modern IDE for building Android apps — on Android.</b><br>
  Developed and maintained by <b>James</b>.
</p>

---

## About

James IDE is a full-featured integrated development environment that runs entirely on your Android device. Write, build, and ship real Gradle-based Android apps without a PC.

## Features

- **Code editor** — syntax highlighting, code completion, and diagnostics for Java, Kotlin, and XML
- **Terminal** — a full Linux-style terminal with a package manager
- **Gradle support** — build real Android projects with the standard Gradle toolchain
- **Android SDK support** — manage and use the Android SDK directly on the device
- **Git support** — clone, commit, push, and manage repositories from the IDE
- **Modern UI** — Material 3 design with a refined dark theme and smooth animations

## Building

James IDE is built with Gradle. To build the debug APK:

```bash
./gradlew :core:app:assembleDebug
```

The APK is generated at `core/app/build/outputs/apk/debug/`.

> **Note:** Building requires JDK 17+ and an internet connection so Gradle can
> resolve dependencies. See `REBRANDING.md` for notes about signing and runtime
> services (terminal bootstrap and build-tools downloads).

## Contact

- **Developer:** James
- **Email:** raloci1063@gicont.com

## License

```
James IDE is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

James IDE is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.
```

James IDE is a derivative work based on the open-source AndroidIDE project and
its forks, used under the terms of the GNU General Public License v3.0. In
compliance with the GPL, original license headers in source files are
preserved. Full license text is available in [LICENSE](./LICENSE).
