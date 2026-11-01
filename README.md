# Eigenbook

An offline picture book of machine learning, written for ML research interviews. 51 lessons — math, deep learning, LLMs, post-training, inference, systems design and research — where every step is one sentence, one picture or looping animation, and typed PyTorch, and every name has a hover definition.

## Install on Android

1. Open the [latest release](https://github.com/ML-Chen/eigenbook/releases/latest) on your phone and download `eigenbook.apk`.
2. Open it. Android asks once to allow installs from your browser; allow it, then tap **Install**.

The app works with no connection. When it is online it checks this repository's latest release:

- **New lessons** download in the background, and the app offers to reload.
- **A new version of the app** asks before downloading; Android then asks you to confirm the install.

Every release is signed with the same key, so updates install over the previous version and keep your marks and notes.

## Read in a browser

Download `book.html` from the latest release and open it. It is one self-contained file and also works offline.

## Release assets

| File | What it is |
|---|---|
| `eigenbook.apk` | The Android app (Android 8.0 or newer) |
| `book.html` | All lessons as one offline page |
| `version.json` | `version` (lessons), `app_revision` (app code); the app compares these to decide what to update |
