<div align="center">

⛅ &nbsp; **r2-install-action** &nbsp; ⛅

store versioned binaries in cloudflare r2

</div>

## getting started

```yaml
-   name: 💝 Install prebuilts 💝
    uses: rarestype/r2-install-action@v1
    with:
        tracker: you/your-metadata-repo
        project: your-project
        archive: products.tar.gz
```

a `tracker` is just a GitHub repository containing tags that the action can use to determine the latest version of the binaries to download. alternatively, you can pass `version` instead, to select a specific version.
