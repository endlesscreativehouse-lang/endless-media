# endless-media

Public image host for @endlesskuwait Instagram publishing. Meta downloads each image
from here at post time, so these paths must stay public and stable.

```
media/
  posts/<nn>-<name>/          one folder per feed post, numbered in posting order
      1-en.jpg  2-ar.jpg      prefix = slide position (odd posts lead with English,
                              even posts lead with Arabic)
  stories/highlights/<name>/  one folder per profile highlight
      cover.png               the highlight cover
      1-...-en.jpg  2-...-ar.jpg   stories in the order they sit in the highlight
```

Base URL: `https://raw.githubusercontent.com/endlesscreativehouse-lang/endless-media/main/media`

Images only. No tokens, no `.env`, no `posted.json`.
