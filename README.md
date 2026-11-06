# koi-updates

[update.koi.surf](https://update.koi.surf/updates/browser/Darwin_aarch64-gcc3/release/update.xml),
where installed copies of [Koi](https://koi.surf) check for a new version.

Koi asks for `updates/browser/<build target>/<channel>/update.xml`. An empty
`<updates>` means it is up to date; a release's file names the version and
where to download its update, which is attached to that release on GitHub.
[`scripts/release.sh`](https://github.com/Awhalen1999/koi/blob/main/scripts/release.sh)
in Koi's repo writes it as `dist/update.xml`; it goes here once the release
is published.
