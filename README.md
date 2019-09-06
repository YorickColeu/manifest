Fetch manifest:

```
repo init -u https://github.com/YorickColeu/manifest
```

Fetch all projects refered by manifest:

```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
