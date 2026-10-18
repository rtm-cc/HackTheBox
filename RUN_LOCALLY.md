# 💻 Running Hack The Box Walkthroughs Locally (Zensical)

This site is powered by **[Zensical](https://zensical.org/)**, the next-generation successor to Material for MkDocs.

---

## 🚀 Quick Start

You can run the documentation site locally with either **Python / uv** or **npm**:

### Option A: Using `uv` (Fastest, zero install)
```bash
uv tool run zensical serve -a 127.0.0.1:4321
```

### Option B: Using `pip`
```bash
pip install zensical
zensical serve -a 127.0.0.1:4321
```

### Option C: Using `npm`
```bash
npm run dev
```

Once running, open your browser at:
👉 **[http://localhost:4321/HackTheBox/](http://localhost:4321/HackTheBox/)**

---

## ✍️ Writing Walkthroughs & Notes

Adding new documentation is completely automatic:

1. Create a standard `.md` file anywhere in `docs/` (e.g. `docs/machines/my-machine.md`).
2. Add a title at the top of your file (`# My Machine` or `title: "My Machine"` in frontmatter).
3. **That's it!** Zensical automatically detects the file, places it in the sidebar navigation, and indexes it in full-text search.

---

## 🔄 Looking for the Old Astro Starlight Setup?

The original Astro Starlight version is preserved on the `archive/astro` branch:

```bash
git checkout archive/astro
npm run dev
```
