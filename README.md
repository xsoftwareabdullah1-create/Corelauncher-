# CoreLauncher

CoreLauncher is an Android launcher project based on PojavLauncher. This repository retains upstream attribution and licensing; it is not an official PojavLauncher release.

![CoreLauncher logo](corelauncher-logo.svg)

## Build APK
1. Open **Actions**.
2. Select **Build CoreLauncher APK**.
3. Tap **Run workflow** on the `main` branch.
4. When the run completes successfully, open its **Artifacts** section and download `corelauncher-apk`. The APK inside is named `corelauncher.apk`.

The build workflow installs the CoreLauncher logo as the launcher icon and app icon before building. A successful workflow run is required; no APK is claimed until GitHub Actions confirms the build.

## Logo replacement
The app icon source is `corelauncher-logo.svg`. The workflow converts it to Android launcher icon resources and applies those resources before running the Gradle build. To replace the icon, update that SVG and run the build workflow again.

## Upstream and licensing
CoreLauncher is based on [PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher). Preserve the upstream license, notices, and attribution when redistributing modified builds.