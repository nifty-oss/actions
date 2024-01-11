# Cache IDL generators using BuildJet

Cache the hidden folder that caches IDL generators, such as Shank and Anchor, using `buildjet/cache`.

```yaml
- uses: nifty-oss/actions/buildjet-cache-idl-generators@v1
  with:
    path: ./.crates/
    key: idl-generators
```

- Inputs:
  - `path`: Path(s) to cache. Defaults to `./.crates/`.
  - `key`: A unique key prefix for the cache. Defaults to `idl-generators`.
