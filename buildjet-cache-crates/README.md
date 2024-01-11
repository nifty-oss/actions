# Cache dependencies of multiple crates using BuildJet

Cache all crate related folders using `buildjet/cache`. This includes Rust global folders and all `target` folders under a given folder.

```yaml
- uses: nifty-oss/actions/buildjet-cache-crates@v1
  with:
    folder: ./programs
    key: programs
```

- Inputs:
  - `folder`: Path to the folder containing the crates (without trailing slash). Defaults to `./programs`.
  - `key`: A unique key prefix for the cache. Defaults to `programs`.
