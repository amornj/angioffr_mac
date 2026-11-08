# angioFFR for macOS

Current build: angioFFR 0.55.5, which fixes Google sign-in in the desktop app and retains the desktop save/export fix for JSON studies, PDF reports, and CSV files.

Use the `.dmg` matching the Mac architecture: `x64` for Intel and `arm64` for Apple Silicon. Install by opening the disk image and dragging angioFFR to Applications.

Build from the source project with:

```sh
npm run desktop:build:mac
```

The app is unsigned and not notarized. If macOS blocks the first launch, right-click the app in Applications and choose **Open**.
