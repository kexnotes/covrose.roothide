# covrose.roothide

Sileo/APT mirror of RootHide Procursus for **iphoneos-arm64e / 1900** (iOS 16+, including iOS 18.6.2).

Built from [https://roothide.github.io/procursus](https://roothide.github.io/procursus) so Covrose can pin its own copy of the bootstrap package set.

## Add in Sileo

Paste this URL (flat repo — Sileo looks for `/Release` here):

```
https://kexnotes.github.io/covrose.roothide/procursus
```

The dists layout is also kept for:

```
deb https://kexnotes.github.io/covrose.roothide/procursus iphoneos-arm64e/1900 main
```

## Contents

- 772 mirrored Procursus records plus **Covrose Patcher** (`com.covrose.patcher`)
- ~664 MB
- Suite matching Dopamine RootHide `getCFMajorVersion()` = `1900`

Search Sileo for **Covrose Patcher** (`com.roothide.patcher` 2.2.1). The home-screen name is **CvPatcher**. Converted debs go to `/var/mobile/Documents/CvPatcher`.

iOS 15 (`1800`) is not mirrored here: GitHub Pages has a 1 GB site limit, and `1800` is another ~664 MB.
