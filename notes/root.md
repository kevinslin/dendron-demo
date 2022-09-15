---
id: sz1yrvz8s3s2rilwr56f8dn
title: Root
desc: ''
updated: 1663267449652
created: 1663264918764
---

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

## Lookup

This section contains useful links to related resources.

- [Getting Started Guide](https://link.dendron.so/6b25)
- [Discord](https://link.dendron.so/6b23)
- [Home Page](https://wiki.dendron.so/)
- [Github](https://link.dendron.so/6b24)
- [Developer Docs](https://docs.dendron.so/)