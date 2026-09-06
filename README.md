# Brian Lagerstrom + Personal Dinner Cookbook 🍳

A browsable HTML cookbook combining:
1. **All dinner recipes from [brianlagerstrom.com](https://brianlagerstrom.com)** — the ⚡ quick ones (≤40 minutes) flagged and sorted to the top
2. **Peter's personal saved recipes** — marked with a 📌 Personal badge, from sources like The Modern Nonna, RecipeTin Eats, Mob Kitchen, and more

**Live site:** https://pcmccullagh.github.io/lagerstrom-cookbook/

## Contents

- **198 recipes total**
  - **173 Brian Lagerstrom dinners** (breakfasts, breads, desserts, and sauces filtered out)
  - **25 personal recipes** saved from around the web
- **41+ tagged ⚡ "≤40 min"** for quick weeknight dinners
- Every card includes: photo, prep/cook time, category, servings, ingredients, instructions, and a link to the full recipe
- Fully static — just open `index.html` in any browser

## Features

- ⭐ **Star favorites** — click the star on any card (saved in browser localStorage)
- ✕ **Delete recipes** — hide ones you don't want (recoverable)
- 🔍 **Filters** — All / ⭐ Favorites / ⚡ Quick only
- 📌 **Personal badge** — distinguishes your saved recipes from the Lagerstrom catalog

## How it was built

- Brian Lagerstrom catalog: pulled from the site's WordPress REST API (283 posts → filtered to 173 dinners), extracted structured data (times, ingredients, instructions, images) from the WPRM recipe blocks
- Personal recipes: exported from Peter's Notion-based cookbook (`pcmccullagh/cookbook`), converted to the same card format
- Tagged quick dinners where published total time ≤40 min (or prep+cook ≤40, or the chef's own title says so)

## Local use

```bash
git clone https://github.com/pcmccullagh/lagerstrom-cookbook.git
cd lagerstrom-cookbook
open index.html
```

---

*Recipes and images © their respective authors. This is a personal-use index; all rights to the recipes belong to their authors.*
