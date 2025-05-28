# Clone Source:

```bash
git clone -b vince https://github.com/vince-labs/local_manifests --depth=1 .repo/local_manifests
```
# Then to sync up:
```
repo sync -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
```
