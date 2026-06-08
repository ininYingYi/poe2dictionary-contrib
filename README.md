# POE2 Dictionary — Community Contributions

This is the public contribution repository for [POE2 Dictionary](https://poe2dictionary.com), a bilingual (Traditional Chinese / English) reference site for Path of Exile 2.

Community-contributed articles appear on the site under the **Community** section.

---

## How to Contribute

### Option A — Submit via Issue (recommended for most users)

No git knowledge required.

1. Click **[Issues](../../issues) → New Issue**
2. Choose a template:
   - **Content Contribution** — submit a new article
   - **Edit Existing Content** — suggest a correction or update
3. Fill in the form and submit

A maintainer will review and publish your content.

### Option B — Submit a Pull Request (for technical users)

1. Fork this repo
2. Create a folder for your article under `en/` or `zh/` (see structure below)
3. Open a pull request

You only need to write in the language you know — maintainers will handle the other language.

---

## File Structure

Each article is a **folder** containing an `index.md` and any images used in that article.

```
en/
  introduction/
    index.md
  beginner-guide/
    index.md
    currency-overview.png
    skill-tree.jpg
  currency-trading/
    index.md
    chaos-orb.png

zh/
  introduction/
    index.md
  beginner-guide/
    index.md
    通貨概覽.png
```

### Folder naming

Always use **English lowercase with hyphens** for folder names in both `en/` and `zh/`. This keeps URLs consistent across languages and makes it easy to match the same article in both languages.

```
en/beginner-guide/   → poe2dictionary.com/community/en/beginner-guide
zh/beginner-guide/   → poe2dictionary.com/community/zh/beginner-guide
```

### index.md frontmatter

Each `index.md` should start with:

```markdown
---
sidebar_label: Your Article Title
---

# Your Article Title

Content goes here...
```

### Adding images

Place image files in the same folder as `index.md`, then reference them with a relative path:

```markdown
![Currency Overview](./currency-overview.png)
```

You can also paste image URLs directly if the image is hosted elsewhere (e.g. a GitHub issue upload).

---

## Content Guidelines

- Information must be accurate to the **current version** of Path of Exile 2
- Cite your sources (patch notes, official site, in-game tooltips)
- Keep language appropriate and constructive

---

## License

Contributed content is published under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
