# scoop-molt

Scoop bucket for Molt.

## Install

```powershell
scoop bucket add adpena https://github.com/adpena/scoop-molt
scoop install molt
```

## Updating

Manifests are generated from Molt release manifests:

```bash
python3 tools/release/update_manifests.py release_manifest.json
```

Copy the rendered manifests from `packaging/out/scoop/` into this repo.
