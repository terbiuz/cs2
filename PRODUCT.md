# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Viewers of the terbiuz YouTube channel who open the site from a link in a video about investing in CS2 skins. They want to compare skins quickly and understand which ones are scarce, liquid and moving in price before deciding what to look at more closely.

## Product Purpose

One place that lists every CS2 skin (2,126 finishes: weapons, knives, gloves) with the facts that matter for holding skins as an investment: how many copies exist (supply found by CSFloat FloatDB), the CSFloat reference price for each wear and for StatTrak, which case or collection the skin comes from and whether that source still drops, liquidity (sales divided by supply), the Skinport price trend over 7 and 30 days against 90 days, and transparent long-term and short-term labels, each with its plus and minus reasons written out. Supply is compared within one rarity; price is compared with skins of the same rarity and weapon type (knives and gloves: the same model), wear against wear. Success: a viewer finds the skins worth a closer look in a minute and understands why.

## Positioning

It joins supply counts with the drop status of the skin's source, so a viewer sees which skins can no longer be minted, and every label is a published formula over that data rather than an opinion.

## Operating Context

- Hub page at https://terbiuz.github.io/cs2/ lists the channel's CS2 projects; this tool lives at https://terbiuz.github.io/cs2/investments-analysis/.
- Viewers arrive from a YouTube description link, so the first screen must make sense without the video.
- The page is a static snapshot: data was collected on 3 November 2026 and is refreshed by replacing the JSON files in `investments-analysis/data/`.

## Capabilities and Constraints

- Static HTML, CSS and JavaScript on GitHub Pages; no build step, no third-party scripts; data in `data/skins.json` (about 1.1 MB), `data/sources.json`, `data/trends.json`.
- Interface language is Russian; skin, case and collection names stay in English as in the game; the term «supply» stays in English by the owner's choice; rarities use the Russian game names (Тайное, Засекреченное, Запрещённое, Армейское, Промышленное, Ширпотреб); prices are in USD.
- Features to keep: search, filters (weapon type, case or collection, drop status, rarity, signal), StatTrak price toggle, sortable table of all skins, case and collection table that filters the skin table and explains why drop status matters, summary figures, method explanation. The supply-versus-price scatter plot was removed at the owner's request on 3 November 2026: viewers could not act on it.
- Drop statuses: drops weekly, Armory, recently removed, no longer drops.
- Supply is still missing for some skins (373 of 2,126 on 3 November 2026: mostly cheap collection skins, some Mil-Spec case skins and the vanilla knives); the page counts them from the data and says so rather than hiding it.
- Must show data sources (CSFloat, Skinport, community drop-pool tracking), the snapshot date, a not-financial-advice note, and that the site is not affiliated with Valve, CSFloat or Skinport.

## Brand Commitments

The channel name is terbiuz. There is no existing logo, color palette or typeface to follow.

## Evidence on Hand

Real data only: the three JSON files above. There are no testimonials, user counts, performance claims or track record; do not invent any.

## Product Principles

1. Data honesty first: every number shows where it came from, how fresh it is and where it is missing.
2. Labels are sorting rules, not advice; the formula behind them is always one click away.
3. Comparison over prediction: make it fast to scan, filter and compare 2,000+ rows.
4. Built for a viewer arriving cold from a video: the first screen explains what the page is and how to read it.
