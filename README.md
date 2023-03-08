# Test cases for the issue in Astro v2.0.7-v2.0.15 + astro-icon

**Update (2023-03)**: the issue was [fixed in Astro v2.0.16](https://github.com/withastro/astro/releases/tag/astro%402.0.16)

There was an issue where Astro (v2.0.7-v2.0.15) injects CSS `link` elements inside `body` when using `<Sprite.Provider>` in astro-icon.

https://github.com/natemoo-re/astro-icon/issues/83
https://github.com/withastro/astro/issues/6318
