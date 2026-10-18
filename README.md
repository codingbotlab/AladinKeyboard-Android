# Aladin Keyboard — Free Android Beta

**App ID:** `in.aladin.keyboard`

**Latest cloud-sync test build:** `0.1.2-beta.1` (debug-signed; test only)

**Previous UI test build:** `0.1.1-beta.1` (debug-signed; test only)

**Previous publisher-signed beta:** `0.1.0-beta.1`

**Minimum Android:** 8.0 (API 26)

- [Download the Supabase sync test APK](https://github.com/codingbotlab/AladinKeyboard-Android/releases/download/v0.1.2-beta.1/AladinKeyboard-0.1.2-beta.1-SUPABASE-TEST-DEBUG.apk)
- [Previous UI test APK](https://github.com/codingbotlab/AladinKeyboard-Android/releases/download/v0.1.1-beta.1/AladinKeyboard-0.1.1-beta.1-UI-TEST-DEBUG.apk)
- [Previous publisher-signed beta](https://github.com/codingbotlab/AladinKeyboard-Android/releases/download/v0.1.0-beta.1/AladinKeyboard-0.1.0-release.apk)
- [Browse the open-source Android source (MIT License)](https://github.com/codingbotlab/AladinKeyboard)
- [Read the beta privacy notice](PRIVACY.md)

Aladin Keyboard is a free Android keyboard beta. The source repository is public under the MIT License. The responsive UI and opt-in Supabase learning-count sync changes compile successfully in CI and are included in the latest test APK. **This APK is signed with a temporary CI debug key, not the publisher release key; it may not update an existing installation. Do not uninstall an existing app unless local data is backed up. Cloud sync requires Supabase Anonymous Sign-Ins to be enabled in the project settings and remains off until the user explicitly opts in.**

## Beta notes

This is an early beta, not a store-reviewed release. Install only if you trust the publisher and understand the limitations. Voice typing depends on the speech-recognition provider installed on your device.

The optional PC learning sync currently uses plain HTTP and a shared beta token on the local network. **Only use it on a trusted private Wi-Fi network; do not expose the PC receiver to the internet or use sync on public Wi-Fi.** The sync design needs hardening before a production release.

A GitHub release does not imply that the app is approved or listed in Google Play, F-Droid, IzzyOnDroid, Uptodown, or any other store.
