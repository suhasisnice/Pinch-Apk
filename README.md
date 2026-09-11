# Pinch APK

Built releases of [Pinch](https://github.com/suhasisnice/pinch), pushed here so a phone can grab one without needing the source tree.

Only one file is ever present — `Pinch.apk`, always the latest build. It gets overwritten and committed on every release rather than kept as a growing pile of version-numbered files; every past build is still recoverable from git history (`git log --oneline -- Pinch.apk`, then `git show <commit>:Pinch.apk > old.apk`).
