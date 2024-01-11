# Install Anchor CLI

Install Anchor CLI with optional caching and verify the installed version.

```yaml
- uses: nifty-oss/actions/install-anchor-cli@v1
  with:
    version: "0.29.0"
    cache: true
```

- Inputs:
  - `version`: The Anchor CLI version to install. Defaults to `0.29.0`.
  - `cache`: Whether the downloaded Anchor CLI release should be cached using `buildjet/cache`. Defaults to `true`.
