# feiyanglyy-stack.github.io

Angelina's page: https://feiyanglyy-stack.github.io/

A single static `index.html`. The text a visitor reads is the `PROFILE` block at the top of the script;
everything else is read live — the worlds and films from the museum's
[`manifest.json`](https://feiyanglyy-stack.github.io/atlas-museum/manifest.json)
([atlas-museum](https://github.com/feiyanglyy-stack/atlas-museum)) and the public repositories from the GitHub API.
Adding a work to the museum or a public repo shows up here without editing this page.

**中 / EN.** The button in the top-right corner switches the page between English and Chinese. A first visit follows the
browser's language (Chinese → Chinese, anything else → English); a manual switch is remembered in `localStorage` under
`wv-lang`, the same key the museum uses, so on the live site the choice carries across both. `?lang=zh` / `?lang=en` in a
link picks the language for that visit. The Chinese text of the museum's works comes from the `zh` fields in its manifest.

**Share card.** `og.jpg` (1200×630) is the preview image X, Slack and WeChat show for a link to this page; the `og:` and
`twitter:` tags in `<head>` point to it.
