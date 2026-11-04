---
name: terbiuz CS2
description: Brutalist market board for CS2 skin data — near-black, one acid-lime signal, condensed uppercase headlines.
colors:
  ground: "#0A0A0A"
  panel: "#131313"
  panel-raised: "#1B1B1B"
  bone: "#F2F2EE"
  ash: "#9A9A94"
  rule: "#262626"
  rule-strong: "#3A3A3A"
  chart-grid: "#1F1F1F"
  acid-lime: "#D4FF3A"
  ember-down: "#FF6A45"
  removed-orange: "#FF9F1C"
  armory-violet: "#A58BFF"
  rarity-consumer: "#B0C3D9"
  rarity-industrial: "#5E98D9"
  rarity-milspec: "#4B69FF"
  rarity-restricted: "#8847FF"
  rarity-classified: "#D32CE6"
  rarity-covert: "#EB4B4B"
  rarity-special: "#E4AE39"
typography:
  display:
    fontFamily: "Oswald, Arial Narrow, sans-serif"
    fontSize: "5.5rem"
    fontWeight: 700
    lineHeight: 0.86
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Oswald, Arial Narrow, sans-serif"
    fontSize: "3.5rem"
    fontWeight: 700
    lineHeight: 0.9
  figure:
    fontFamily: "Oswald, Arial Narrow, sans-serif"
    fontSize: "3.25rem"
    fontWeight: 700
    lineHeight: 0.95
  title:
    fontFamily: "Oswald, Arial Narrow, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 600
    letterSpacing: "0.03em"
  body:
    fontFamily: "Onest, Segoe UI, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  data:
    fontFamily: "Onest, Segoe UI, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    fontFeature: "tnum"
  label:
    fontFamily: "Oswald, Arial Narrow, sans-serif"
    fontSize: "13px"
    fontWeight: 500
    letterSpacing: "0.05em"
  stamp:
    fontFamily: "Oswald, Arial Narrow, sans-serif"
    fontSize: "12px"
    fontWeight: 600
    lineHeight: "22px"
    letterSpacing: "0.06em"
rounded:
  none: "0px"
spacing:
  xs: "6px"
  sm: "8px"
  md: "12px"
  lg: "20px"
  xl: "28px"
  section: "64px"
components:
  search-field:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.bone}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: "0 20px"
    height: "66px"
  preset-tile:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.bone}"
    typography: "{typography.figure}"
    rounded: "{rounded.none}"
    padding: "18px 20px 16px"
  preset-tile-active:
    backgroundColor: "{colors.acid-lime}"
    textColor: "{colors.ground}"
  button-primary:
    backgroundColor: "{colors.acid-lime}"
    textColor: "{colors.ground}"
    rounded: "{rounded.none}"
    padding: "0 22px"
    height: "56px"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.bone}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0 16px"
    height: "42px"
  button-outline-hover:
    backgroundColor: "{colors.bone}"
    textColor: "{colors.ground}"
  select:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.bone}"
    rounded: "{rounded.none}"
    padding: "0 10px"
    height: "42px"
  stamp-fixed:
    backgroundColor: "transparent"
    textColor: "{colors.acid-lime}"
    typography: "{typography.stamp}"
    padding: "0 8px"
  stamp-drop:
    backgroundColor: "transparent"
    textColor: "{colors.ash}"
    typography: "{typography.stamp}"
    padding: "0 8px"
  code-ssp:
    backgroundColor: "{colors.bone}"
    textColor: "{colors.ground}"
    typography: "{typography.stamp}"
    padding: "0 5px"
  code-sp:
    backgroundColor: "transparent"
    textColor: "{colors.bone}"
    typography: "{typography.stamp}"
    padding: "0 5px"
  signal-strong:
    backgroundColor: "{colors.acid-lime}"
    textColor: "{colors.ground}"
    typography: "{typography.stamp}"
    padding: "3px 8px"
  reason-list:
    textColor: "{colors.ash}"
    typography: "{typography.label}"
    width: "13rem"
  table-row:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.bone}"
    typography: "{typography.data}"
    padding: "0 5px"
    height: "48px"
  table-row-hover:
    backgroundColor: "{colors.panel-raised}"
---

# Design System: terbiuz CS2

## Overview

**Creative North Star: "The Market Board"**

A trading-floor board cut down to its bones: near-black panels on hairline rules, numbers set as headlines, and a single acid-lime signal that says "look here". It is a reference tool for YouTube viewers who arrive from a video, type their skin or tap a preset, and scan supply, wear prices and signals row by row. Density is high and deliberate; every column of data stays on screen, and the type does the shouting so the surfaces never have to.

The world is the user's own brutalist reference: condensed uppercase grotesque for anything that names or counts, a quiet humanist sans for data and prose, square corners, no material effects. Colour is information, not decoration. Lime is reserved for what matters now; orange, violet and red each carry one meaning; CS2 rarity colours are confined to small swatches.

Rejected by the user: kitschy gamer aesthetics, a "boring like Excel" grid, the neon crypto-exchange look, and anything that falls apart on a phone.

**Key Characteristics:**
- Near-black ground with two flat panel tones separated by 1px rules.
- One signal colour (acid lime), used sparingly enough to stay loud.
- Oswald uppercase for titles, big numbers, labels, stamps; Onest for data and prose.
- Square everything: zero radius, no shadows, no gradients.
- Every data column visible; phones get cards, not hidden fields.

## Colors

A near-monochrome dark board with one acid accent and three single-meaning status hues.

### Primary
- **Acid Lime** (acid-lime): the only signal colour. Fills the active preset tile, «Сильный» signal labels, the primary hub action, the source-filter chip and text selection. Outlines the search field and the "no longer drops" stamp. Marks the sorted column head, the brand word and focus rings. Text on lime is always Ground.

### Secondary
- **Ember Down** (ember-down): falling price trends and the «Неликвид» label. Text only, never a fill.
- **Removed Orange** (removed-orange): the "recently removed" stamp outline.
- **Armory Violet** (armory-violet): the Armory stamp outline.

### Tertiary
- **CS2 rarity set** (rarity-consumer through rarity-special): the game's own rarity colours, shown only as 10px square swatches beside a skin name.

### Neutral
- **Ground** (ground): page background and text on lime.
- **Panel** (panel): tables, tiles, search, selects, the sticky name column.
- **Panel Raised** (panel-raised): row and tile hover, the selected source row.
- **Bone** (bone): primary text, SSP code fill, outline-button border.
- **Ash** (ash): secondary text, column heads, captions, inactive stamps.
- **Rule** (rule): hairline dividers and panel borders. **Rule Strong** (rule-strong): select borders, header underline, drop stamp border, scrollbar thumb.
- **Chart Grid** (chart-grid): supply bar tracks.

### Named Rules
**The One Signal Rule.** Lime marks only what matters now. A table row carries at most one or two lime fills (the «Сильный» labels); stamps and codes in a row are outlines or bone, never lime fills.

**The One Meaning Rule.** Orange, violet and red each mean exactly one thing (recently removed, Armory, falling or illiquid). Do not reuse them as decoration or for unrelated states.

**The Swatch-Only Rarity Rule.** CS2 rarity colours appear only as 10px squares. Never tint text, rows or borders with them.

## Typography

**Display Font:** Oswald (with Arial Narrow, sans-serif)
**Body Font:** Onest (with Segoe UI, system-ui, sans-serif)

**Character:** Oswald is the board's voice: tall, condensed, uppercase, shouting the title and the counts. Onest is the clerk: calm, legible at 14px, with tabular figures so price columns align.

### Hierarchy
- **Display** (Oswald 700, 5.5rem, line-height 0.86, uppercase): the page title only. 3.4rem on phones.
- **Headline** (Oswald 700, 3.5rem, line-height 0.9, uppercase): section heads (supply vs price, cases, method). 2.4rem on phones, so it never outranks the title.
- **Figure** (Oswald 700, 3.25rem, line-height 0.95): preset-tile counts. 2.4rem on phones.
- **Title** (Oswald 600, 1.25rem, 0.03em, uppercase): method sub-heads.
- **Body** (Onest 400, 15px, line-height 1.5): prose, leads, filters; the hub runs 16–17px. Leads cap at 70ch.
- **Data** (Onest 400, 14px, tabular numbers): table cells; skin names at 600 15px.
- **Label** (Oswald 500, 13px, 0.05em, uppercase): nav, column heads, preset captions (14px).
- **Stamp** (Oswald 600, 12px, 0.06em, uppercase): status stamps, SSP/SP codes, signal labels.

### Named Rules
**The Two-Voice Rule.** Oswald names and counts; Onest reports. No third family, and Oswald never sets running prose.

## Layout

A single centred column capped at 1800px (112.5rem) for the reference board, with 20px side gutters that grow to 40px at 1700px and above. The hub uses a narrower 72rem cap: it holds one card, and wide whitespace there reads as emptiness, not calm.

The first viewport stacks: nav row (48px), title with the snapshot line beside a 66px search field, four preset tiles across the width, filter row, legend, then the table head with first rows visible at 1440×900. Sections below are separated by 64px of space.

The skins table keeps all 14 columns. When the window is narrower than the table, it scrolls horizontally inside its panel with the skin-name column pinned. At 760px and below, rows become cards: the name and status span the full width, values sit in a three-column grid with their labels above, and empty wear prices are dropped. Presets reflow to a 2×2 grid; selects pair up two per row. At 1100px and below, the masthead and the cases/method split stack to one column. The cases table never hides a column; on phones it scrolls sideways with the source name held at a 10.5rem minimum.

There is no supply-versus-price chart: it mixed every rarity and weapon type on one log-log field and repeated what the «дешевле похожих» reason already says, so the board leads straight from the table to the case table and the method.

## Elevation & Depth

Flat. Depth comes only from tonal steps (Ground → Panel → Panel Raised) and 1px rules. There are no elevation shadows. `box-shadow` appears in two structural roles only: a 1px rule on the right edge of the pinned name column, and a 2px inset lime underline on the selected source row.

### Named Rules
**The Flat Board Rule.** No shadows for lift, no gradients, no blur, no glow. If something needs to stand out, it changes tone or turns lime.

## Shapes

Square corners everywhere (0px radius): tiles, fields, buttons, stamps. Borders are 1px; the search field alone takes a 2px lime border, marking it as the page's main entry point. Nothing on the board is round.

## Components

### Buttons
- **Shape:** square (0px).
- **Primary** (hub "Open the reference"): lime fill, Ground text, Oswald 600 17px uppercase, 56px tall, 0 22px padding, trailing arrow drawn as inline SVG.
- **Outline** (reset filters): transparent with a 1px Bone border, Oswald 600 14px uppercase, 42px tall; hover inverts to Bone fill with Ground text.
- **Focus:** 2px lime outline, 2–3px offset.

### Chips
- **Source filter chip:** lime fill, Ground text, Oswald 600 uppercase, 42px, with an inline close cross. Appears only while a case/collection filter is active.
- **Hub fact chips:** 1px Rule Strong outline, Bone text, Oswald 500 13px uppercase. All outlined; lime belongs to the action beside them.

### Cards / Containers
- **Corner Style:** square.
- **Background:** Panel; hover to Panel Raised.
- **Shadow Strategy:** none (see Elevation & Depth).
- **Border:** 1px Rule; the hub project card's border turns lime on hover.
- **Internal Padding:** 18–28px; tables sit flush to their panel border so row fills reach the edge.

### Inputs / Fields
- **Search:** Panel fill, 2px lime border, 66px tall, lime magnifier icon, 18px text (16px on phones).
- **Selects:** Panel fill, 1px Rule Strong border, 42px, square.
- **Focus:** 2px lime outline.

### Navigation
- 48px row with a 1px bottom rule. Oswald 500 13px uppercase in Ash; the brand word «terbiuz» in lime at 15px. Hover lifts links to Bone. The optional "whole market" link hides on phones.

### Preset Tiles (signature)
Four tiles acting as filter toggles (`aria-pressed`), each a big Oswald count over an uppercase caption. Inactive: Panel with a 1px Rule border. Active: solid lime with Ground text. This is the board's signature and the loudest lime on the page.

### Status Stamps and Rarity Codes
- **Stamps:** outlined uppercase tags with a 6.8rem minimum width so a column of them aligns. "No longer drops" is lime-outlined; "recently removed" orange; Armory violet; "drops" Rule Strong with Ash text.
- **Codes:** SSP is a Bone-filled tag with Ground text; SP is a Bone outline.
- **Signals:** «Сильный» lime fill; «Средний» Bone text; «Слабый» and «Нет данных» Ash; «Неликвид» Ember Down text.
- **Pluses and minuses:** one «Плюсы и минусы» column after the two signals. Each factor appears at most once, in a fixed order: supply against the same rarity, price against similar skins, number of sales, 7-day trend. Status is never repeated there because it has its own column. Onest 12px Ash; each line starts with a bold sign, lime «+» or Ember «−». A skin with nothing notable reads «ничего не выделяется» without a sign. The column is 13rem wide (11rem below 1760px).

### Data Table
Panel background, rows of at least 48px divided by 1px Rule (two or three reasons grow a row to 62–93px), Panel Raised on hover. Column heads are sort buttons in Oswald 500 uppercase Ash; the sorted column turns lime with a direction caret. Supply carries a 44×6px log-scale bar in lime on a Chart Grid track. «Продаж» (count of CSFloat sales) and «Ликвидность» (sales as a share of supply) sit side by side. The name column is 18rem (17.5rem below 1760px); long knife names wrap and the SSP or SP code follows the last word. At 1694px and wider every column fits without sideways scrolling.

## Do's and Don'ts

### Do:
- **Do** keep lime to the active preset, «Сильный» labels, the primary action, the search border, focus and selection.
- **Do** set titles, section heads and big counts in Oswald 700 uppercase, and data in Onest with tabular figures.
- **Do** keep every table column available: pin the name and scroll sideways on narrow desktops, use labelled cards on phones.
- **Do** state missing data in the cell («нет данных», «—») rather than hiding the row or column.
- **Do** keep transitions to 0.15s ease-out colour changes and drop them under reduced motion.

### Don't:
- **Don't** fill stamps or rarity codes with lime; a row with three lime blocks has lost its signal.
- **Don't** use rounded corners, drop shadows, gradients or glows.
- **Don't** drift toward kitschy gamer styling, a plain spreadsheet look, or a neon crypto-exchange terminal.
- **Don't** colour text, rows or borders with CS2 rarity colours; they live in 10px swatches.
- **Don't** let a section headline outrank the page title on phones.
