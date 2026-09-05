# Brian Lagerstrom Dinner Cookbook 🍳

A browsable HTML cookbook of all dinner recipes from [brianlagerstrom.com](https://brianlagerstrom.com), with the **⚡ quick ones (≤40 minutes)** flagged and sorted to the top.

**Live site:** https://pcmccullagh.github.io/lagerstrom-cookbook/

## Contents

- **173 dinner recipes** (breakfasts, breads, desserts, and sauces filtered out)
- **41 tagged ⚡ "≤40 min"** for quick weeknight dinners
- Every card includes: photo, prep/cook time, category, servings, ingredients, instructions, and a link to the full recipe
- Fully static — just open `index.html` in any browser

## The quick list (≤40 min)

15 Minute Beef & Broccoli · Linguine and Clams · Basil Pesto Pasta · Alfredo E Pepe · Chicken Thigh Orange Chicken · 25 Minute Shrimp Tacos · Dan Dan Noodles · Italian Sausage and Rapini Pasta · 5 Ingredient Mexican Tostada · Bacon and Peas Pasta · Rapini Anchovy Pasta · 25 Minute Stir Fry · Speed Scratch Chicken Soup · Pasta alla Vodka · 15 Minute Carbonara · Spaghetti Chow Mein · Shrimp Scampi Pasta · Mapo Tofu · Pasta Vodka · Budget Pad Woon Sen · 30 Minute Chili · Brown Butter Sage Pasta · Quick Green Curry · Quick & Easy Indian Dinner · Chicken Piccata · Fried Rice · Chicken Thigh Khao Soi · Thai Green Curry · Ravioli With Marsala Cream Sauce · Chicken Teriyaki · 5 Ingredient Mexican Mushroom Quesadilla · 5 Ingredient Mexican Enchiladas · Keema Curry · Sheet Pan Fajitas · 30 Minute Pad Woon Sen · Chicken Aloo Vindaloo · Weeknight Banh Mi · Green Goddess Egg Salad · Italian Wedding & Minestrone Soup · Easy Beer Battered Fish Sandwich · 30 Minute Gyro Taco

## How it was built

- Pulled the full recipe catalog from the site's WordPress REST API (283 posts → filtered to 173 dinners)
- Extracted structured data (times, ingredients, instructions, images) from the WPRM recipe blocks
- Tagged quick dinners where published total time ≤40 min (or prep+cook ≤40, or the chef's own title says so, e.g. "25 Minute Stir Fry")
- ~58 recipes don't publish a time — they're included but untagged

## Local use

```bash
git clone https://github.com/pcmccullagh/lagerstrom-cookbook.git
cd lagerstrom-cookbook
open index.html
```

---

*Recipes and images © Brian Lagerstrom. This is a personal-use index; all rights to the recipes belong to their author.*
