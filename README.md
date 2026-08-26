# vanlabeke/homebrew-tap

Homebrew tap for [vanlabeke](https://github.com/vanlabeke) projects.

```sh
brew tap vanlabeke/tap
```

## Available

### exshell — terminal viewer for CSV and XLSX files

```sh
brew install --cask exshell
```

A cask rather than a formula because the tap ships pre-built, signed and
notarized binaries; Homebrew formulas are expected to build from source.

## Contents

`Casks/` is written automatically by
[GoReleaser](https://goreleaser.com) on each upstream release — edit the
project's `.goreleaser.yaml`, not the files here, or your change will be
overwritten by the next release.
