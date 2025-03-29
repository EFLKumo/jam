# jam

[![Tests](https://github.com/EFLKumo/jam/actions/workflows/ci.yml/badge.svg)](https://github.com/EFLKumo/jam/actions/workflows/ci.yml) [![Excavator](https://github.com/EFLKumo/jam/actions/workflows/excavator.yml/badge.svg)](https://github.com/EFLKumo/jam/actions/workflows/excavator.yml)

🍯 A [scoop](https://scoop.sh) bucket made by EFL.

Install `jam` by:
```pwsh
scoop bucket add jam https://github.com/EFLKumo/jam
```

List apps:
```pwsh
scoop search | Where-Object { $_.Source -eq "jam" }
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
