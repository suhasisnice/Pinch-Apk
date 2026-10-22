# Pinch APK

Built releases of [Pinch](https://github.com/suhasisnice/pinch), pushed here so a phone can grab one without needing the source tree.

Only one file is ever present — `Pinch.apk`, always the latest build. It gets overwritten and committed on every release rather than kept as a growing pile of version-numbered files; every past build is still recoverable from git history (`git log --oneline -- Pinch.apk`, then `git show <commit>:Pinch.apk > old.apk`).

**Current file:** Pinch 0.9.3, built 11 Sep 2026. The source repo has moved on since then (0.9.25), and a newer build has not been published here yet.

To install: download `Pinch.apk` on an Android phone and allow installs from your browser when asked. Pinch only runs on Android.
