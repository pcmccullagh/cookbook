# My Cookbook 🍳

All my recipes in one place — from Brian Lagerstrom, the web, and anywhere else I save them. The ⚡ quick ones (≤40 minutes) are flagged and sorted to the top.

**Live site:** https://pcmccullagh.github.io/lagerstrom-cookbook/

## Contents

- **189 recipes**
  - **164 Brian Lagerstrom dinners**
  - **25 personal recipes** saved from around the web (marked 📌 Personal)
- **41+ tagged ⚡ "≤40 min"** for quick weeknight dinners
- Every card: photo, time badge, category, servings, ingredients, instructions, and source link

## Features

- ⭐ **Star favorites** — click the star on any card (saved in browser localStorage)
- ✕ **Delete recipes** — removes from the page (and syncs across records via the sync script)
- 🔍 **Filters** — All / ⭐ Favorites / ⚡ Quick only
- 📌 **Personal badge** — distinguishes saved recipes from the Lagerstrom catalog

## Deleting a recipe

Deleting on the page hides it locally (localStorage). To remove it from **all records** (site data, second brain, Notion cache), run:

```bash
python3 ~/.hermes/scripts/sync_recipe_deletions.py
```

## Local use

```bash
git clone https://github.com/pcmccullagh/lagerstrom-cookbook.git
cd lagerstrom-cookbook
open index.html
```

---

*Recipes and images © their respective authors. This is a personal-use index; all rights to the recipes belong to their authors.*
