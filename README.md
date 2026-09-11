# Vscan Releases

Public, binary-only update channel for **Vscan Android**.

The Vscan Android source code remains private in `xz64uj777/Vscan`. This repository exists only so installed Vscan builds can check for updates without embedding a GitHub credential in the APK.

## What is published here

GitHub Releases may contain:

- a signed `Vscan-vX.Y.Z.apk`
- the matching SHA-256 checksum file
- release notes

No signing keys, source repository credentials, scan results, user data, or private application source belong in this repository.

## Update verification

Before Vscan hands an update to Android's installer, the app verifies the downloaded APK's package identity and signing-certificate continuity. It also verifies the published SHA-256 digest when GitHub provides one for the release asset.

Android still presents the final installation/update confirmation to the user.

## Canonical source

Development happens in the private `xz64uj777/Vscan` repository. This repository is distribution infrastructure only.
