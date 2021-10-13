# Releasing

Releases of this crate are fairly automated.

To create a new release:

1. Trigger [this](https://github.com/monero-rs/base58m/actions/workflows/draft-new-release.yml) workflow with the desired version number.
2. Merge the resulting PR (watch your notifications).

The `[Unreleased]` section of `CHANGELOG.md` must contain all the changes that will be documented for the release.
