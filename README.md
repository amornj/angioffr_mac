# angioFFR for macOS

Current build: **angioFFR 0.58.1**. Built from source commit [3e6a0f7](https://github.com/amornj/angioFFR/commit/3e6a0f7).

Downloads:

- [angioFFR-0.58.1-mac-arm64.dmg](angioFFR-0.58.1-mac-arm64.dmg)
- [angioFFR-0.58.1-mac-x64.dmg](angioFFR-0.58.1-mac-x64.dmg)

Checksums: [SHA256SUMS](SHA256SUMS).

This update includes:

- Up to four angiographic images, with dedicated branch tracing and a selected best measurement view for each branch.
- Nested branch origins, visible-tree length and volume summaries, and crown-based Mode 5 flow allocation.
- PDF vessel models colored by calculated angioFFR, with the matching legend, regardless of the workspace color selection.
- Existing desktop Google sign-in, cloud backup/recovery, and save/export support.

Mode 5 is an independent research implementation; it does not inherit CathWorks FFRangio validation.

Use the `.dmg` matching the Mac architecture: `x64` for Intel and `arm64` for Apple Silicon. Install by opening the disk image and dragging angioFFR to Applications.

Build from the source project with:

```sh
npm run desktop:build:mac
```

The app is unsigned and not notarized. If macOS blocks the first launch, right-click the app in Applications and choose **Open**.
