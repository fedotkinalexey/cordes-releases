# Cordes for Mac

Builds of the Cordes desktop app. Download from the latest release:

**https://github.com/fedotkinalexey/cordes-releases/releases/latest**

- **Mac** (Apple Silicon): `Cordes_<version>_aarch64.dmg`

Windows builds are paused: releases from 0.6.4 on are Mac only. 0.6.3 is the
last one with a Windows installer, and a copy installed from it stays on 0.6.3.

Once installed, Cordes finds new versions here by itself and offers
**Restart to update**. Nothing is installed until you press it.

**Mac, the first time:** macOS may say it can't check the app for malicious
software, because these builds aren't notarised by Apple. Open **System
Settings → Privacy & Security** and press **Open Anyway** next to Cordes.
Updates after that don't ask again.

**Windows, the first time:** the installer isn't code-signed yet, so
SmartScreen says "Windows protected your PC". Press **More info**, then
**Run anyway**. It installs for your account only, with no administrator
password. Updates install the same way, in a small progress window, and
Cordes opens again by itself.

This repository holds only the builds and the workflow that makes them. The
source is private.
