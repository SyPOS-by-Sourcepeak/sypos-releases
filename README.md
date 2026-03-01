# Sypos Releases

This repository contains **official binary releases** of the Sypos application.

It exists solely to host **public, versioned build artifacts** used by the Sypos auto-update system.

---

## What this repo is

- ✔️ A public distribution endpoint for Sypos installers
- ✔️ Used by the in-app updater for forced and optional updates
- ✔️ Versioned via GitHub Releases
- ✔️ Anonymous, direct-download friendly (no auth, no cookies)

---

## What this repo is NOT

- ❌ It does **not** contain source code
- ❌ It is **not** the main development repository
- ❌ It does **not** accept issues or pull requests
- ❌ It is **not** meant for browsing implementation details

---

## How releases are organized

Each GitHub Release corresponds to a Sypos version:

vX.Y.Z
├─ Sypos-X.Y.Z-arm64.dmg
├─ Sypos-X.Y.Z-x64.exe
└─ (other platform artifacts)

Release assets are referenced by the Sypos update manifest and downloaded directly by client applications.

---

## Security & integrity

- Releases may include checksum metadata in the update manifest
- Only official builds published by the Sypos team are hosted here
- If you downloaded an installer from elsewhere, it is **not trusted**

---

## Need help?

If you are a user experiencing issues, please contact Sypos support through official channels.

This repository is intentionally minimal.

---

© Sypos. All rights reserved.
