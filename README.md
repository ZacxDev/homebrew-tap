# ZacxDev Homebrew tap

Homebrew casks for [ZacxDev](https://github.com/ZacxDev) tools.

Casks in this tap are **generated automatically by
[GoReleaser](https://goreleaser.com)** on each upstream release — they point at
the checksummed release tarballs published on GitHub. Do not hand-edit files in
`Casks/`; changes are overwritten on the next release.

## Install

> **Homebrew 6.0 (2026-06-11) requires third-party taps to be explicitly trusted**
> before their code is evaluated, and no longer auto-taps untrusted taps. So the
> single-line `brew install ZacxDev/tap/<name>` no longer works on its own — you
> must tap and trust this repository first. Check `brew tap --help` on your
> installed version for the exact trust flag.

```sh
brew tap ZacxDev/tap
brew install --cask civitai-manager
```

## What's here

| Cask | Upstream |
|---|---|
| `civitai-manager` | https://github.com/ZacxDev/civitai-manager |

## Verifying releases

Release artifacts carry GitHub build provenance. You can verify a downloaded
tarball independently of Homebrew:

```sh
gh attestation verify --owner ZacxDev civitai-manager_<version>_<os>_<arch>.tar.gz
```

## License

The casks here are generated metadata. Each tool is covered by its own upstream
license.
