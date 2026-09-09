<h1 align="center">LineageOS for Pixel 8 Pro</h1>

<div align="center">

<p><i>OTA update support for the Google Pixel 8 Pro (husky), providing the latest available LineageOS builds.</i></p>

[![LineageOS](https://img.shields.io/badge/LineageOS-167C80?style=for-the-badge&logo=lineageos&logoColor=white)](https://lineageos.org/)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://www.android.com/)
[![OTA](https://img.shields.io/badge/OTA-Update-167C80?style=for-the-badge&logo=android&logoColor=white)](#)
[![Active](https://img.shields.io/badge/Status-Active-2EA44F?style=for-the-badge)](#)

</div>

## About

This repository contains the OTA metadata required to provide update information for the Google Pixel 8 Pro (`husky`).

The repository is intentionally minimal and contains the update configuration used by the LineageOS updater.

## Device

| Property      | Value                |
| ------------- | -------------------- |
| Device        | Google Pixel 8 Pro   |
| Codename      | `husky`              |
| ROM           | LineageOS            |
| Update method | OTA                  |
| Architecture  | ARM64                |

## Repository Structure

```text
.
├── husky.json
├── husky-stable.json
├── husky-beta.json
└── husky-alpha.json
```

## OTA Channels

- **Stable**: [husky-stable.json](https://raw.githubusercontent.com/rhythmcreative/lineageos-husky-ota/main/husky-stable.json)
- **Beta**: [husky-beta.json](https://raw.githubusercontent.com/rhythmcreative/lineageos-husky-ota/main/husky-beta.json)
- **Alpha**: [husky-alpha.json](https://raw.githubusercontent.com/rhythmcreative/lineageos-husky-ota/main/husky-alpha.json)
- **Default**: [husky.json](https://raw.githubusercontent.com/rhythmcreative/lineageos-husky-ota/main/husky.json)

> **Note:** This repository only provides OTA metadata. The actual LineageOS builds are hosted separately.

## Disclaimer

This is an unofficial project and is not affiliated with or endorsed by the LineageOS project or Google.

<div align="center">

<p>Made with ❤️ from rhythmcreative.</p>

</div>
