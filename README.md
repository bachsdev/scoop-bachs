# Scoop bucket for the Bachs CLI (Windows)

```powershell
scoop bucket add bachs https://github.com/bachsdev/scoop-bachs
scoop install bachs
```

Then:

```powershell
bachs login --api-key sk_sandbox_...
bachs listen --forward-to localhost:3000/webhooks
```

Manifests are written by [GoReleaser](https://goreleaser.com) when a release is
cut from [bachsdev/bachs-cli](https://github.com/bachsdev/bachs-cli) — edit
them there, not here.

Docs: https://docs.bachs.io/developer-portal/local-testing
