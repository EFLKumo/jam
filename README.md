# jam

[![Tests](https://github.com/EFLKumo/jam/actions/workflows/ci.yml/badge.svg)](https://github.com/EFLKumo/jam/actions/workflows/ci.yml) [![Excavator](https://github.com/EFLKumo/jam/actions/workflows/excavator.yml/badge.svg)](https://github.com/EFLKumo/jam/actions/workflows/excavator.yml)

🍯 `jam` is a [scoop](https://scoop.sh) bucket that emphasizes reliability and cleanliness.

I always believe that `scoop` is not just a package manager, but also has the goal of achieving clean, tidy, and well-structured app management on the Windows platform. This bucket contains applications that are not included in the official bucket, or are included but are unreliable in certain aspects. All manifests in this bucket are written or reviewed carefully, ensuring **portability** of applications (using scoop's `persist` feature) and **reliability**.

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
