# appBucket

[![Tests](https://github.com/MiyZQ/appBucket/actions/workflows/ci.yml/badge.svg)](https://github.com/MiyZQ/appBucket/actions/workflows/ci.yml) [![Excavator](https://github.com/MiyZQ/appBucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/MiyZQ/appBucket/actions/workflows/excavator.yml)

Own bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

Run the following:

```pwsh
scoop bucket add appBucket https://github.com/MiyZQ/appBucket
scoop install appBucket/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
