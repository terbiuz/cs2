---
name: terbiuz CS2
description: Brutalist market board for CS2 skin data in the TerbiuZ brand colours — violet-black void, one violet signal, white plates, wide Unbounded Black headlines over condensed Oswald labels.
colors:
  ground: "#050407"
  panel: "#0E0A15"
  panel-raised: "#191222"
  bone: "#F3F0F7"
  white: "#FFFFFF"
  ash: "#A49CB3"
  rule: "#2B2238"
  rule-strong: "#3E3250"
  chart-grid: "#191222"
  violet: "#8A2BFF"
  violet-hot: "#B366FF"
  rarity-consumer: "#B0C3D9"
  rarity-industrial: "#5E98D9"
  rarity-milspec: "#4B69FF"
  rarity-restricted: "#8847FF"
  rarity-classified: "#D32CE6"
  rarity-covert: "#EB4B4B"
  rarity-special: "#E4AE39"
typography:
  display:
    fontFamily: "Unbounded, Arial Black, sans-serif"
    fontSize: "5rem"
    fontWeight: 900
    lineHeight: 0.92
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Unbounded, Arial Black, sans-serif"
    fontSize: "2.5rem"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.01em"
  figure:
    fontFamily: "Unbounded, Arial Black, sans-serif"
    fontSize: "2.75rem"
    fontWeight: 900
    lineHeight: 1
  title:
    fontFamily: "Unbounded, Arial Black, sans-serif"
    fontSize: "0.95rem"
    fontWeight: 900
    letterSpacing: "0.02em"
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
    backgroundColor: "{colors.violet}"
    textColor: "{colors.white}"
  button-primary:
    backgroundColor: "{colors.violet}"
    textColor: "{colors.white}"
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
    textColor: "{colors.violet-hot}"
    typography: "{typography.stamp}"
    padding: "0 8px"
  stamp-drop:
    backgroundColor: "transparent"
    textColor: "{colors.ash}"
    typography: "{typography.stamp}"
    padding: "0 8px"
  code-ssp:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ground}"
    typography: "{typography.stamp}"
    padding: "0 5px"
  code-sp:
    backgroundColor: "transparent"
    textColor: "{colors.bone}"
    typography: "{typography.stamp}"
    padding: "0 5px"
  tier-s:
    backgroundColor: "{colors.violet}"
    textColor: "{colors.white}"
    typography: "{typography.stamp}"
    padding: "0 4px"
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

A trading-floor board cut down to its bones: near-black panels on hairline rules, numbers set as headlines, and a single violet signal that says "look here". It is a reference tool for YouTube viewers who arrive from a video, type their skin or tap a preset, and scan supply, wear prices and signals row by row. Density is high and deliberate; every column of data stays on screen, and the type does the shouting so the surfaces never have to.

The world is the user's own brutalist reference dressed in the TerbiuZ channel brand: the brand's wide Unbounded Black for anything that headlines or counts, condensed uppercase Oswald for labels, a quiet humanist sans for data and prose, square corners, no material effects. Colour is information, not decoration. Violet is reserved for what matters now; the brand allows only black, violet and white, so status and direction are told by fill, outline and sign; CS2 rarity colours are confined to small swatches.

Rejected by the user: kitschy gamer aesthetics, a "boring like Excel" grid, the neon crypto-exchange look, and anything that falls apart on a phone.

**Key Characteristics:**
- Violet-black ground with two flat panel tones separated by 1px rules.
- One signal colour (brand violet), used sparingly enough to stay loud; small violet text is always Violet Hot.
- Unbounded Black for titles, section heads, big numbers and tier letters; Oswald uppercase for labels and stamps; Onest for data and prose.
- Square everything: zero radius, no shadows. Only two brand touches: a soft violet glow at the top of the page and hatching on the active preset tile.
- Every data column visible; phones get cards, not hidden fields.

## Colors

The TerbiuZ channel palette (`brand/README.md` in the TerbiuZ project): violet-black neutrals, one violet and white. The interface uses no other hue; the only extra colour on the board is the game's own rarity swatches.

### Primary
- **Violet** (violet): the only signal colour. Fills the active preset tile (with the brand hatching), the S tier box, the primary hub action, the source-filter chip and text selection. Outlines the search field, the A tier box and the "no longer drops" stamp; draws the supply bars and the selected source row's underline. Text on violet is always White (5.4:1). Never small text on its own: on Ground it is only 3.8:1.
- **Violet Hot** (violet-hot): every small violet text on dark (the sorted column head, the A tier letter, the "no longer drops" stamp, the count-line number, rising price figures, «+» signs) plus the search icon, focus rings and the text caret. 6.1:1 on Ground.

### Neutral
- **Ground** (ground, brand void): page background and text on white plates. A soft violet glow (radial, 30% violet) sits at the top right of each page.
- **Panel** (panel, brand ink): tables, tiles, search, selects, the sticky name column.
- **Panel Raised** (panel-raised, brand ink-2): row and tile hover, the selected source row, supply bar tracks (chart-grid).
- **White** (white): plates (the SSP code, the "recently removed" stamp, the outline button's hover fill) and text on violet.
- **Bone** (bone): primary text, falling price figures, «−» signs, the «Неликвид» label and the Armory stamp. White softened toward the brand violet so dense tables do not glare.
- **Ash** (ash, brand mist): secondary text, column heads, captions, price moves under 3%, the "drops" stamp text.
- **Rule** (rule, brand line): hairline dividers and panel borders. **Rule Strong** (rule-strong): select borders, header underline, drop stamp border, inspect button border, scrollbar thumb.

### Tertiary
- **CS2 rarity set** (rarity-consumer through rarity-special): the game's own rarity colours, shown only as 10px square swatches beside a skin name.

### Named Rules
**The One Signal Rule.** Violet marks only what matters now. A table row carries at most one or two violet fills (the S tier boxes); stamps and codes in a row are outlines or white plates, never violet fills.

**The No Extra Hue Rule.** The brand has no red, orange or green, so meaning comes from fill, outline and signs. Status stamps: "no longer drops" a violet outline with Violet Hot text, "recently removed" a White plate with Ground text, Armory a Bone outline, "drops" a Rule Strong outline with Ash text. Price direction is carried by the sign; colour only says how notable a move is: Ash under 3%, Violet Hot for a rise, Bone for a fall.

**The Swatch-Only Rarity Rule.** CS2 rarity colours appear only as 10px squares. Never tint text, rows or borders with them.

## Typography

**Display Font:** Unbounded Black 900 (with Arial Black, sans-serif), the TerbiuZ brand face
**Label Font:** Oswald (with Arial Narrow, sans-serif)
**Body Font:** Onest (with Segoe UI, system-ui, sans-serif)

**Character:** Unbounded is the brand's voice: wide, black, uppercase, shouting the title, the section heads and the counts, as on the channel's banner and thumbnails. Oswald is the board's labeller: tall and condensed, so column heads, captions and stamps fit a dense table. Onest is the clerk: calm, legible at 14px, with tabular figures so price columns align.

### Hierarchy
- **Display** (Unbounded 900, up to 5rem, line-height 0.92, -0.01em, uppercase): the page title only. Beside the 34rem search it scales with the window so «ИНВЕСТИЦИИ», its longest word, always fits its column (clamp 2.6–5rem); 4.5rem when the masthead stacks; 2–4.5rem on phones by width. The hub title runs 2.2–4.5rem.
- **Headline** (Unbounded 900, 2.5rem, line-height 1, uppercase, balanced wrap): section heads (cases, method) and the hub project title (2.25rem). 1.6rem on phones (hub 1.5rem), so it never outranks the title.
- **Figure** (Unbounded 900, 2.75rem, line-height 1): preset-tile counts. 2rem on phones.
- **Title** (Unbounded 900, 0.95rem, 0.02em, uppercase): method sub-heads.
- **Tier letter** (Unbounded 900, 12.5px): S/A/B/C inside the 22px tier box.
- **Body** (Onest 400, 15px, line-height 1.5): prose, leads, filters; the hub runs 16–17px. Leads cap at 70ch.
- **Data** (Onest 400, 14px, tabular numbers): table cells; skin names at 600 15px.
- **Label** (Oswald 500, 13px, 0.05em, uppercase): nav, column heads, preset captions (14px).
- **Stamp** (Oswald 600, 12px, 0.06em, uppercase): status stamps, SSP/SP codes, signal labels.

### Named Rules
**The Three-Voice Rule.** Unbounded headlines and counts, Oswald labels, Onest reports. No fourth family. Unbounded never goes into column heads, stamps or toolbar buttons: at their sizes it is about 1.6× wider than Oswald and pushes the table past the screen. Neither display face sets running prose.

## Layout

A single centred column capped at 1800px (112.5rem) for the reference board, with 20px side gutters that grow to 40px at 1700px and above. The hub uses a narrower 72rem cap: it holds one card, and wide whitespace there reads as emptiness, not calm.

The first viewport stacks: nav row (48px), title with the snapshot line beside a 66px search field, four preset tiles across the width, filter row, legend, then the table head with first rows visible at 1440×900. Sections below are separated by 64px of space.

The skins table keeps all 15 columns. When the window is narrower than the table, it scrolls horizontally inside its panel with the skin-name column pinned. At 760px and below, rows become cards: the name and status span the full width, values sit in a three-column grid with their labels above, and empty wear prices are dropped. Presets reflow to a 2×2 grid; selects pair up two per row. At 1100px and below, the masthead and the cases/method split stack to one column. The cases table never hides a column; on phones it scrolls sideways with the source name held at a 10.5rem minimum.

There is no supply-versus-price chart: it mixed every rarity and weapon type on one log-log field and repeated what the «дешевле похожих» reason already says, so the board leads straight from the table to the case table and the method.

## Elevation & Depth

Flat. Depth comes only from tonal steps (Ground → Panel → Panel Raised) and 1px rules. There are no elevation shadows. `box-shadow` appears in two structural roles only: a 1px rule on the right edge of the pinned name column, and a 2px inset violet underline on the selected source row.

### Named Rules
**The Flat Board Rule.** No shadows for lift, no blur. The only gradients are the two brand touches: the page-top violet glow and the hatching on the active preset tile. If something needs to stand out, it changes tone or turns violet.

## Shapes

Square corners everywhere (0px radius): tiles, fields, buttons, stamps. Borders are 1px; the search field alone takes a 2px violet border, marking it as the page's main entry point. Nothing on the board is round.

## Components

### Buttons
- **Shape:** square (0px).
- **Primary** (hub "Open the table"): violet fill, White text, Unbounded 900 14px uppercase (a brand plate), 56px tall, 0 22px padding, trailing arrow drawn as inline SVG.
- **Outline** (reset filters): transparent with a 1px Bone border, Oswald 600 14px uppercase, 42px tall; hover inverts to Bone fill with Ground text.
- **Focus:** 2px Violet Hot outline, 2–3px offset.

### Chips
- **Source filter chip:** violet fill, White text, Oswald 600 uppercase, 42px, with an inline close cross. Appears only while a case/collection filter is active.
- **Hub fact chips:** 1px Rule Strong outline, Bone text, Oswald 500 13px uppercase. All outlined; violet belongs to the action beside them.

### Cards / Containers
- **Corner Style:** square.
- **Background:** Panel; hover to Panel Raised.
- **Shadow Strategy:** none (see Elevation & Depth).
- **Border:** 1px Rule; the hub project card's border turns violet on hover.
- **Internal Padding:** 18–28px; tables sit flush to their panel border so row fills reach the edge.

### Inputs / Fields
- **Search:** Panel fill, 2px violet border, 66px tall, Violet Hot magnifier icon, 18px text (16px on phones).
- **Selects:** Panel fill, 1px Rule Strong border, 42px, square.
- **Focus:** 2px Violet Hot outline.

### Navigation
- 48px row with a 1px bottom rule. Oswald 500 13px uppercase in Ash; the TerbiuZ wordmark (white TERBIU and the violet stencil Z, inlined from `brand/logo/terbiuz-wordmark.svg`) at 15px high, linking to the hub. Hover lifts links to Bone. The optional "whole market" link hides on phones.

### Preset Tiles (signature)
Four tiles acting as filter toggles (`aria-pressed`), each a big Unbounded count over an Oswald uppercase caption. Inactive: Panel with a 1px Rule border. Active: brand violet under the brand hatching (white lines at 16%, 135°, 24px step) with White text. This is the board's signature and the loudest violet on the page.

### Status Stamps and Rarity Codes
- **Stamps:** uppercase tags with a 6.8rem minimum width so a column of them aligns. "No longer drops" is a violet outline with Violet Hot text; "recently removed" a White plate with Ground text; Armory a Bone outline; "drops" Rule Strong with Ash text.
- **Codes:** SSP is a White plate with Ground text; SP is a Bone outline.
- **Tiers:** each score cell is a 22px tier box plus the score (0–100, the skin's rank) in tabular figures. S is a violet fill with White text; A a violet outline with a Violet Hot letter; B a Rule Strong outline with Bone text; C a Rule outline with Ash text and an Ash score. Other labels are text: «Нет данных» and «Только сувенир» Ash, «Неликвид» Bone. «Только сувенир» breaks onto two lines so the label column keeps its width. The legend repeats the four boxes.
- **Pluses and minuses:** one «Плюсы и минусы» column after the two signals. Each factor appears at most once, in a fixed order: supply against similar skins, new copies (case price; for knives and gloves also Covert trade-ups), price against similar skins, number of sales, price against the skin's usual 90-day level (a deep dip is a plus «на N% дешевле обычного», a rise of 3% or more a minus «уже на N% дороже обычного»), and a closing minus when a long-term tier was capped at B. Status is never repeated there because it has its own column. Onest 12px Ash; each line starts with a bold sign, Violet Hot «+» or Bone «−». A skin with nothing notable reads «ничего не выделяется» without a sign. The column is 13rem wide (11rem below 1760px).

### Data Table
Panel background, rows of at least 48px divided by 1px Rule (two to five reasons grow most rows to 62–109px; the longest, five long reasons, reaches 171px), Panel Raised on hover. Column heads are sort buttons in Oswald 500 uppercase Ash; the sorted column turns Violet Hot with a direction caret. Supply carries a 44×6px log-scale bar in violet on a Chart Grid track. The 7- and 30-day figures follow the No Extra Hue Rule. «Продаж» (count of CSFloat sales) and «Ликвидность» (sales as a share of supply) sit side by side. The name column is 18rem (17.5rem below 1760px); long knife names wrap, a phase in brackets stays on one line, and the SSP or SP code follows the last word. A 30px square inspect button with an eye icon sits at the right of every name cell, centred across the name and case lines: Rule Strong outline and Ash icon, Bone on hover. It is a `steam://` preview link that opens the skin in CS2, so it lives in the pinned name column instead of a column of its own (a separate column pushed the table past 1694px), and touch-screen cards drop it because the link needs Steam on a computer. The legend explains it. At 1694px and wider every column fits without sideways scrolling.

## Do's and Don'ts

### Do:
- **Do** keep violet to the active preset, S and A tier boxes, the primary action, the search border, focus and selection, and use Violet Hot for any small violet text.
- **Do** set titles, section heads, big counts and tier letters in Unbounded 900 uppercase, labels in Oswald, and data in Onest with tabular figures.
- **Do** keep every table column available: pin the name and scroll sideways on narrow desktops, use labelled cards on phones.
- **Do** state missing data in the cell («нет данных», «—») rather than hiding the row or column.
- **Do** keep transitions to 0.15s ease-out colour changes and drop them under reduced motion.

### Don't:
- **Don't** fill stamps or rarity codes with violet; a row with three violet blocks has lost its signal.
- **Don't** use rounded corners or drop shadows, or add glows and gradients beyond the page-top glow and the preset hatching.
- **Don't** bring back lime, red or orange: the site follows the TerbiuZ brand palette, and the brand book is the source of truth for its colours.
- **Don't** drift toward kitschy gamer styling, a plain spreadsheet look, or a neon crypto-exchange terminal.
- **Don't** colour text, rows or borders with CS2 rarity colours; they live in 10px swatches.
- **Don't** let a section headline outrank the page title on phones.
