# novellib-builds

Unofficial APK test builds of [nimbice/NovelLibrary](https://github.com/nimbice/NovelLibrary), a fork of [gmathi/NovelLibrary](https://github.com/gmathi/NovelLibrary). These are not official NovelLibrary releases, and the NovelLibrary developer doesn't make or support them. Each release names the source branch and commit it was built from.

## Before installing

- These are debug builds, meant for testing. Anyone with USB-debugging access to a phone running one can read the app's data, including site logins.
- They use the official app's package name with a different signing key, so Android won't install one over the Play Store or official release. Back up in Settings > General > Backup & Restore, uninstall the official app, install the build, then restore.
- arm64 phones only, Android 8.0 or newer.
- Firebase isn't configured, so cloud sync, push notifications and crash reporting don't work.

## License

NovelLibrary is licensed under the [Apache License 2.0](LICENSE). These builds include changes made in the fork; its commit history shows what changed.
