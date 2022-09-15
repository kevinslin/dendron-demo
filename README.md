# dendron-demo

This is to test dendron publishing a site locally and then pushing it to a github repo without CI and accessing the webpage from gh-pages.

## Step by step

1. Use the following settings in `dendron.yml`:
```yaml
publishing:
    siteUrl: https://ccamara.github.io
    siteRootDir: docs
    assetsPrefix: /dendron-demo
```
2. Run `npx dendron publish build`
3. Export notes `npx dendron publish export`
4. Copy exports to repo `cp -r .next/out docs`
