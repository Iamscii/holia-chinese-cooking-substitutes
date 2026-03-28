# Holia — Chinese Ingredient Substitutes Data

Open-source substitution data for Chinese cooking ingredients.

Part of [Holia](https://holia.com), a Chinese cooking app that adapts every recipe to your stove, pans, and experience level.

## What is this?

A structured dataset of Chinese cooking ingredient substitutes, ranked by flavor match:

- **◈ Closest Match** — Nearly identical results
- - **◇ Similar** — Works well, slight flavor difference
  - - **△ Different But Works** — Emergency substitute, noticeable flavor change
    - 
    Each substitute includes ratio, flavor notes, and compensation adjustments.

## Ingredients Covered

| Ingredient | Chinese | Best Substitute |
|-----------|---------|-----------------|
| Shaoxing Wine | 绍兴酒/料酒 | Dry Sherry (1:1) |
| Doubanjiang | 豆瓣酱 | Gochujang (1:1, reduce salt 25%) |
| Sichuan Peppercorn | 花椒 | Sichuan Peppercorn Oil |
| Oyster Sauce | 蚝油 | Mushroom Oyster Sauce (1:1) |
| Dark Soy Sauce | 老抽 | Soy Sauce + Molasses |
| Light Soy Sauce | 生抽 | Japanese Soy Sauce (1:1) |
| Chinese Black Vinegar | 陈醋 | Balsamic Vinegar (3/4 amount) |
| Douchi | 豆豉 | Black Bean Garlic Sauce |
| Dried Chili Peppers | 干辣椒 | Chile de Arbol (1:1) |
| Chinese Five-Spice | 五香粉 | DIY Blend |
| Cornstarch | 玉米淀粉 | Potato Starch (1:1) |
| Pixian Douban | 郫县豆瓣 | Regular Doubanjiang (1:1) |

## Data Format

See `substitutes.json` for the full structured dataset.

## About Holia

[Holia](https://holia.com) is a Chinese cooking app for iOS that:

- **Adapts to your kitchen** — Electric stove, non-stick pan, gas burner — the method changes with your setup
- - **Shows what right looks like** — Visual references at each step, not just text instructions
  - - **Prevents common mistakes** — Flags errors before they ruin the dish
    - - **Handles substitutions** — Tells you what's essential and what's replaceable
     
      - Free on iOS: https://apps.apple.com/app/id6760192205
     
      - ## License
     
      - Data is available under CC BY 4.0. Attribution: Holia (https://holia.com)
