# Cache crate dependencies using BuildJet

Cache all folders related to the given folder using `buildjet/cache`. This includes Rust global folders and its `target` folder.

```yaml
- uses: nifty-oss/actions/buildjet-cache-crate@v1
  with:
    folder: ./programs/asset
    key: program-asset
```

- Inputs:
  - `folder`: Path to the folder containing the crate (without trailing slash). **Required**.
  - `key`: A unique key prefix for the cache identifying the crate. **Required**.
