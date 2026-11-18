<p align="center"><img src="assets/vumiro-logo.svg" alt="Vumiro" width="600"></p>

# Vumiro

**Share your view. Stay close.**

Screen sharing, voice, chat and customizable community spaces for friends.

- Share your screen and spend time together with voice.
- Talk in direct and Room chats, with shared Room/Community text formatting and emoji behavior.
- Organize Community hubs with Spaces, channels and access controls.
- Make spaces feel like yours with themes and artwork.

## Windows download

[Download the latest Windows release](https://github.com/snoopeh/Vumiro-downloads/releases/latest).

The current release is **1.22.8 for Windows x64 only**. No Linux or Android builds are provided in this release.

### Install the complete portable app

1. Download **Vumiro-win-x64-v2.zip** from the release assets. This is the complete package for a fresh installation; there is no setup installer.
2. Close Vumiro, then extract the complete archive into a separate application folder.
3. Run **Vumiro.exe**.

Requirements: **Windows 10 or 11, x64**, **.NET Framework 4.8**, and the **Microsoft Edge WebView2 Runtime**.

Existing clients configured for the old private update feed need this manual installation to move to the public feed. **Vumiro-win-x64.zip** is the legacy updater bridge, not the complete package for a fresh installation.

## Verification and current limits

Update metadata is signed with **RSA-PSS-SHA256** and verified against the embedded publisher trust root. The Windows executables do not have an Authenticode certificate. Compare manual downloads with **SHA256SUMS.txt** from the same release. Checksums alone are not publisher signatures.

Real-device capture, real-network sessions and compatibility with the deployed backend have not been validated for this release. Community functions require configured services and a compatible backend. Local demonstrations are simulated and do not establish live service availability.

Read the release notes for the exact checks and limitations of each build.

## Attribution and notices

Vumiro continues [Eslam Hamouda's ScreenTask](https://github.com/EslaMx7/ScreenTask) under **GPL-3.0-or-later**. Downloaded packages retain **COPYING** and **THIRD-PARTY.md**, along with bundled third-party license notices.
