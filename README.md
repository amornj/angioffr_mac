# angioFFR for macOS

Current build: angioFFR 0.55.6, which fixes cloud backup and recovery in the desktop app by routing Cloud Storage through the local desktop server. Google sign-in and the desktop save/export fix from 0.55.4–0.55.5 are retained.

Use the `.dmg` matching the Mac architecture: `x64` for Intel and `arm64` for Apple Silicon. Install by opening the disk image and dragging angioFFR to Applications.

Build from the source project with:

```sh
npm run desktop:build:mac
```

The app is unsigned and not notarized. If macOS blocks the first launch, right-click the app in Applications and choose **Open**.
