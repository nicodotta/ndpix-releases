# NDPix Releases

This repository hosts public release downloads and third-party source disclosure
material for NDPix, a desktop photo editing application by NicoDottaPhoto.

## Downloads

The official NDPix download and information page is:

<https://nicodottaphoto.com/ndpix-photo-editor/>

Use the GitHub Releases page to download published NDPix installers and update
packages directly:

<https://github.com/nicodotta/ndpix-releases/releases>

For Windows users, the recommended download is the installer:

```text
NDPixSetup-<version>.exe
```

The `NDPix-windows.zip` file is the updater package consumed by the NDPix
desktop update system. It is published here so the application can download a
versioned, checksum-protected package.

## Update Feed

GitHub Releases is used as public file hosting for release assets. The NDPix
desktop update feed remains managed separately by NicoDottaPhoto and is the
source of truth used by the app.

## Checksums

Release assets include `.sha256` files. These files contain SHA-256 checksums
that can be used to verify downloaded installers and updater packages.

## Third-Party Source Disclosure

NDPix is proprietary software. This repository does not publish the NDPix
application source code.

Some third-party components distributed with NDPix require public source
availability under their own license terms. The small `source-disclosure/`
directory records the source disclosure index for each release. Larger
third-party source archives, when required, are uploaded as GitHub Release assets
next to the binary downloads.

For NDPix 1.0.0 Windows, the release assets include source archives for the Qt
6.7.0 modules distributed with the app and LibRaw 0.22.0, plus matching
`.sha256` files.

## Support

NDPix information and support are available through NicoDottaPhoto:

<https://nicodottaphoto.com/ndpix-photo-editor/>
