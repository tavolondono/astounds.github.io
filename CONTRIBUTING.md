# Contributing

## Adding translations

To translate the letter, copy `index.md` into `_translations/`
and name it `index_lang.md` where `lang` is language code you are going to translate into.

Make sure to set `locale` to the appropriate language code. Set `image` to a translated version of social-media-preview.png (for an editable template, see #3324), if there's any. Then you can start translating this file.

For example: `_translations/index_de.md`

```md
---
layout: signed
title: Git dojo, using github-pages
description: Dojo Git example, using github-pages
image: /assets/social-media-preview.png
locale: de_DE
twitter:
  card: summary_large_image
---

2022-12-05

Jesus E., ...
```

There are lots of translation already, if you feel lost, be sure to check out how its done in other ones.

When you translated the text you can commit your change and make pull request.
