# Know You Downloads

Public download artifacts and landing page for Know You macOS releases.

- Release page: https://github.com/gift-is-coding/know-you-downloads/releases/tag/v1.0.0-build109
- Direct download: https://github.com/gift-is-coding/know-you-downloads/releases/download/v1.0.0-build109/KnowYou-macOS-v1.0-build1-3c05f40.zip
- Checksum: `76720050f283a1103e0e2a73aefe42845cc8a83cbb4f68bdd33563dc79098998`

## Release Asset Contract

Each release must contain exactly:

- 1 primary `.zip` asset for the macOS app
- 1 matching `.zip.sha256` checksum file

The repository validates this automatically in GitHub Actions on every published or edited release.
If a release contains multiple primary zip files, or the checksum file does not match the zip
name, the validation workflow fails so the download redirect on `giiift.site` never has to guess.
