---
title:  "Blog Update"
date:   2025-10-12 13:22
categories:
  - essay
tags: [jekyll, essay]
---
# upgrade to latest jekyll 4.4.1

I'm back and upgrade my blog to jekyll 4.4.1 using theme `minimal-mistakes-jekyll`.

## steps

1. follow [guide](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/) to install `minimal-mistakes-jekyll` theme.
2. create `_pages` folder in root directory.Create category-archieve.md and tag-archieve.md following [archieve setting](https://mmistakes.github.io/minimal-mistakes/docs/configuration/#archive-settings).
3. update `_config.yml` include the folder with below codes

    ```
    include:
      - _pages
    ```

## tips

- must fill `url` in `_config.yml`, otherwise the comments would not be loaded.
