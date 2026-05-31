# Summit

Summit is a Windows desktop sync client for self-hosted Immich libraries.

It is designed to give an Immich server a OneDrive-style desktop experience on Windows:
- sync photos and videos between Immich and a local PC
- keep a local sync folder in step with the server
- support Windows Files On-Demand style placeholders for cloud-backed media
- provide tray-based background sync behavior

This repository is the public release repository for Summit installers and update artifacts.

## Downloads

Current release files:
- `Summit_1.0.0_x64-setup.exe`
- `Summit_1.0.0_x64-setup.exe.sig`
- `Summit_1.0.0_arm64-setup.exe`
- `Summit_1.0.0_arm64-setup.exe.sig`
- `latest.json`

## Which installer should I use?

- Use `x64` on most Intel and AMD Windows PCs.
- Use `arm64` on Windows on ARM devices such as Snapdragon-based systems.

## Installation

1. Download the correct installer for your Windows architecture.
2. Run the installer.
3. Launch Summit.
4. Sign in to your Immich server and configure the local sync folder.

## Auto-updates

`latest.json` and the `.sig` files are used by Summit's updater to validate and download the correct installer for each supported Windows architecture.

## Notes

- This repository contains release artifacts only.
- The application source code is maintained separately.
