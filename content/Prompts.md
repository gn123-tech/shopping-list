~~Check the current and upcoming grocery flyers for Super C, Metro, IGA, and Maxi in Quebec City.~~ 

~~Look for whole, unprocessed, single-ingredient foods that are great to buy and stock up on (meat, poultry, fish, seafood, cheese, fresh fruits, fresh vegetables, and raw nuts — absolutely no processed items, prepared meals, or junk food).~~

~~For every item listed, you MUST include:~~
1. ~~The exact name of the item.~~
2. ~~The exact price.~~
3. ~~The exact unit of measurement or package quantity (e.g., price per lb, price per kg, or price per fixed weight package like $X.XX per 400g / 2 lb bag).~~

~~Organize and separate your answer into two clear sections:~~
1. ~~What I can buy TODAY: Deals active right now in the current flyer cycle, including exact prices and unit quantities.~~
2. ~~What I can buy in the NEXT flyer cycle: Upcoming deals starting in the new cycle, including exact prices and unit quantities.~~

npx quartz sync

---

Check the current and upcoming grocery flyers for Super C, Metro, IGA, and Maxi in Quebec City. Look for whole, unprocessed, single-ingredient foods and clean-label healthy pantry essentials that are great to buy and stock up on across the following categories:

- Meat, poultry, fish, seafood, and cheese
    
- Fresh fruits and fresh vegetables
    
- Raw nuts
    
- Clean-label pantry and snack essentials (**strictly single-ingredient or minimalist clean ingredients**: 100% nut butters with no added oils/sugars, organic unfortified whole-grain flours, clean canned tomatoes and legumes with no chemical additives, 100% whole rolled/steel-cut oats, pure cold-pressed extra virgin olive oil, and high-cacao 90%+ dark chocolate).
    

_Absolutely no heavily processed items, prepared frozen meals, or junk food._

For every item listed, you MUST include:

1. The exact name of the item.
    
2. The exact price.
    
3. The exact unit of measurement or package quantity (e.g., price per lb, price per kg, or price per fixed weight package like $X.XX per 400g / 796ml tin / 2 lb bag).
    

Organize and separate your answer into two clear sections:

1. **What I can buy TODAY:** Deals active right now in the current flyer cycle, including exact prices and unit quantities.
    
2. **What I can buy in the NEXT flyer cycle:** Upcoming deals starting in the new cycle, including exact prices and unit quantities.

---


You are managing a personal grocery stock-up price tracker for whole, unprocessed, single-ingredient foods (meat, poultry, fish, seafood, cheese, fresh fruits, fresh vegetables, and raw nuts) in Quebec City.

Please update  the tracking table using the provided new items and flyer data. Follow these strict rules:

1. **Category Separation:** Do not mix items across categories (e.g., keep Red Meat separate from Poultry, Vegetables, Fruits, Dairy & Cheese, and Fish & Seafood). 
2. **Lowest Price Tracking (History Rule):** Compare new item prices against existing table entries. If an item is already present, ALWAYS keep the absolute lowest sale price in the table and update the corresponding store if this week's price is lower. If an item is brand new, add it.
3. **Deduplication:** Remove exact duplicates or overlapping entries, but ensure distinct items (such as beef vs. pork) are never incorrectly merged into a single row.
4. **Data Completeness:** Ensure every item includes:
   - The exact name of the item.
   - The store with the lowest price.
   - The exact sale price with unit of measurement/quantity.
   - The regular price (if available).
5. **Formatting:** Format the final output cleanly as a Markdown table optimized for Obsidian.

Here is the new data to process:
[Insert Category Name Here] - Grocery Stock-Up Tracker
[Paste your raw item list here]

---

You are an expert grocery analyst and nutritional auditor.

Access and scrape the active HTML product listing directly from IGA live website

  

Target location: Quebec City (postal code G1B).

Zero-Hallucination & Verification Rules (CRITICAL)

- DO NOT generate, approximate, guess, or extrapolate prices based on historical training data or typical grocery averages.
- Every price and package size must come directly from live text extracted from the website for the current promotional period (G1B area).
- If an item's exact price or unit size cannot be verified from the live page data, you MUST mark it as "[Unverified in online catalog - check store tag]" rather than estimating a dollar amount.

Nutritional Philosophy & Scope

Extract only whole, unprocessed, single-ingredient foods and clean-label pantry essentials:

- Eligible Categories: Single-ingredient butcher meat, wild/fresh seafood, whole poultry, plain rennet/culture block cheese, fresh raw vegetables and fruits, raw/dry-roasted unsalted nuts and seeds, 100% pure nut butters (no added oils/sugars), unfortified whole rolled/steel-cut grains, additive-free canned tomatoes/legumes, cold-pressed extra virgin olive oil, and 90%+ dark chocolate.
- Strictly Excluded / Flagged: Ultra-processed items, industrial seed/canola oils, artificial sweeteners, added sugars/syrups, chemical preservatives, starches/binders, and imitation/surimi products.

Audit of User-Provided List

You must evaluate and classify every single item listed here:

  

fondue beef meat, osso buco, straberries, peanut butter, tomato soup aylmer, fernandiere sausages

  

For each item:

1. If Clean & Verified: List its exact product name (FR/EN), exact verified live price, and unit (per lb, per kg, or fixed package weight).

- If Ultra-Processed / Additive-Heavy (e.g., canned condensed soup, sauced/cured ribs, imitation surimi flakes):Provide an Obsidian callout (> [!warning]) identifying the specific offending ingredients (e.g., modified corn starch, glucose-fructose, sorbitol, vegetable oils).
- Provide an Obsidian tip callout (> [!tip]) proposing a single-ingredient clean swap available at Super C, with its live verified price and packaging format.

Missing Opportunities

Identify at least 4 to 6 additional whole-food deals currently discounted on the page that meet the clean-label criteria and were missed in my list above.

Output Format (Obsidian Markdown)

Output the entire response inside a single Markdown codeblock with Obsidian-native syntax:

- Actionable grocery items formatted as interactive tasks: [ ] Item — **$Price** / unit
- Warnings and swaps formatted as > [!warning] and > [!tip] callouts.
- Organized under two top-level headings:

1. ## 1. What I Can Buy TODAY (Current Flyer Cycle)
2. ## 2. What I Can Buy in the NEXT Flyer Cycle (List preview deals if available on the site, or indicate the preview release date and watchlist categories).