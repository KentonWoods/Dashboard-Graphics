# Tableau Dashboard Design Assets

Free SVG and PNG backgrounds, icons, and KPI indicators for Tableau dashboards — six complete design themes plus a universal indicator set, ready to drop in.

---

## What this is

If you've ever wanted your Tableau dashboards to look like something other than the default grey-and-blue, this repo is for you.

These assets come from my YouTube channel where I teach Tableau, dashboard design, and data storytelling. A big part of what I cover is how to use Figma to build proper background images for your dashboards — custom layouts, visual structure, consistent branding — all the stuff that separates a polished dashboard from one that just works.

This repo is the companion to that. Six complete design themes, each with a background template and a matching icon set. Plus a separate set of KPI indicator assets — arrows, status badges, card backgrounds, and more — that work across any theme. Take them, use them, adapt them.

---

## What's included

Each theme has two things:

1. **A dashboard background** — 1200×750px, structured as a real dashboard layout with panels, headers, and section zones. Every theme comes in both SVG and PNG. If you want to customize colors or layout, open the SVG in Figma, make your changes, and export. If you want to use it as-is, just grab the PNG and drop it straight into Tableau — no Figma required.

2. **20 matching icons** — Also available as both SVG and PNG. Same style as the background so everything looks like it belongs together. If you need a different size or color, use the SVG in Figma. If the default works for you, the PNG is ready to go.

There's also a standalone set that works across all six themes:

3. **KPI indicators** — 20 assets covering the things you reach for on almost every dashboard: directional arrows in green and red, card backgrounds that signal positive, negative, warning, and neutral status, status badges for goal met/missed, trend pills, and small status dots. Same deal — SVG and PNG both included. These aren't tied to any specific theme color palette, so they fit wherever you need them.

---

## The six themes

### Blue Modern
Strong true blue header, bright blue accent line, light blue-tinted backgrounds, clean white panels. This is the most familiar corporate dashboard look, but done with proper structure and consistent visual hierarchy rather than just Tableau defaults. Works across a wide range of industries and audiences — it's a safe choice that still looks intentional and professional.

### Minimal Executive Modern
Clean whites, soft grays, one restrained teal accent. Lots of breathing room. This one works in almost any professional context — leadership dashboards, board reporting, anything where you want the data to do the talking and the design to stay out of the way.

### Dark Analytic Premium
Deep charcoal background, amber-gold accent, left sidebar navigation, flat metric strip across the top. Done carefully so it doesn't tip into "gaming setup" territory. Good fit for operations teams, technical audiences, or anywhere you want the dashboard to feel modern and high-stakes.

### Editorial Storytelling
Borrowed from magazine and long-form report design. Warm cream background, terracotta accent, layout structured around horizontal rules and reading flow rather than floating cards. Best when the dashboard is meant to tell a story or communicate an institutional message — not just display numbers.

### Soft Card-Based UI
Rounded cards, subtle shadows, violet accent, app-style navigation bar. Current, approachable, works well when you have a lot of controls and KPIs to organize. The kind of dashboard that looks like it belongs in a modern SaaS product.

### Data-Rich Institutional Classic
Deep navy header, tinted left filter panel, traditional grid layout, no rounded corners. Dependable and clean rather than trendy. This is the right call for education, healthcare, public sector, or any environment where trust and readability matter more than visual flash.

---

## KPI indicators

These assets are designed to sit on top of your dashboard — the small things that make KPI cards actually communicate status rather than just display a number.

**Directional arrows** — Up and down triangles in green and red, plus a flat gray dash for no change. Both up-green and down-green are included because direction alone doesn't tell you whether a change is good or bad. A cost going down is green. Revenue going down is red. You pick the right one for the context.

**KPI card backgrounds** — Rounded rectangles with a colored left accent bar, sized to sit behind a KPI value. Positive (light green), negative (light red), warning (light amber), and neutral (light gray). Place one as a floating image in Tableau and layer your text marks on top.

**Status badges** — Filled circles and a triangle with white symbols inside. Green checkmark, red X, amber warning triangle, and a gray neutral dash. Good for goal-met/missed indicators or any pass/fail status column.

**Trend pills** — Pill-shaped badges with a directional arrow inside. Place the pill as a floating image and overlay a Tableau text mark with the actual percentage on top.

**Status dots** — Small 16×16 circles in green, red, amber, and gray. Useful for traffic light status in tabular views or as inline indicators next to a label.

---

## How to use these in Tableau

**If you want to use a theme as-is:** grab the PNG from the backgrounds folder and you're ready to go. No Figma, no editing required.

**If you want to customize first:** open the SVG in Figma, swap colors or adjust the layout to fit your project, then export as PNG at 2x resolution.

Either way, the Tableau workflow is the same:

1. In Tableau, go to **Format → Shading → Worksheet** and set the PNG as the background, or use a floating image object that covers the full dashboard canvas
2. Build your sheets on top, positioning them to land inside the panel zones

For icons, same idea — use the PNG if the default style works, or open the SVG in Figma to resize or recolor before exporting.

If you haven't used background images in Tableau before, I cover the full process on the channel.

---

## File structure

Each theme has its own folder. Inside, you'll find a `PNG` subfolder and an `SVG` subfolder. Both contain the dashboard background and the full icon set for that theme. The KPI indicators follow the same structure in their own folder.

```
blue-modern/
  PNG/
    blue-modern.png
    back.png
    calendar.png
    clear_filters.png
    close.png
    collapse.png
    csv.png
    download.png
    expand.png
    filter.png
    help.png
    home.png
    info.png
    last_updated.png
    pdf.png
    print.png
    refresh.png
    reset.png
    search.png
    share.png
    spreadsheet.png
  SVG/
    blue-modern.svg
    back.svg
    calendar.svg
    clear_filters.svg
    close.svg
    collapse.svg
    csv.svg
    download.svg
    expand.svg
    filter.svg
    help.svg
    home.svg
    info.svg
    last_updated.svg
    pdf.svg
    print.svg
    refresh.svg
    reset.svg
    search.svg
    share.svg
    spreadsheet.svg

minimal-executive-modern/
  PNG/
    [background + same 20 icons]
  SVG/
    [background + same 20 icons]

dark-analytic-premium/
  PNG/
    [background + same 20 icons]
  SVG/
    [background + same 20 icons]

editorial-storytelling/
  PNG/
    [background + same 20 icons]
  SVG/
    [background + same 20 icons]

soft-card-ui/
  PNG/
    [background + same 20 icons]
  SVG/
    [background + same 20 icons]

institutional-classic/
  PNG/
    [background + same 20 icons]
  SVG/
    [background + same 20 icons]

kpi-indicators/
  PNG/
    arrow-up-green.png
    arrow-down-green.png
    arrow-up-red.png
    arrow-down-red.png
    no-change-gray.png
    kpi-bg-positive.png
    kpi-bg-negative.png
    kpi-bg-neutral.png
    kpi-bg-warning.png
    badge-check-green.png
    badge-x-red.png
    badge-warning-amber.png
    badge-neutral-gray.png
    trend-up-green.png
    trend-down-red.png
    trend-flat-gray.png
    dot-green.png
    dot-red.png
    dot-amber.png
    dot-gray.png
  SVG/
    arrow-up-green.svg
    arrow-down-green.svg
    arrow-up-red.svg
    arrow-down-red.svg
    no-change-gray.svg
    kpi-bg-positive.svg
    kpi-bg-negative.svg
    kpi-bg-neutral.svg
    kpi-bg-warning.svg
    badge-check-green.svg
    badge-x-red.svg
    badge-warning-amber.svg
    badge-neutral-gray.svg
    trend-up-green.svg
    trend-down-red.svg
    trend-flat-gray.svg
    dot-green.svg
    dot-red.svg
    dot-amber.svg
    dot-gray.svg
```

---

## A note on colors and branding

Every background here uses a placeholder color scheme that fits the theme. If you want to customize it, pull the SVG into Figma and swap the accent color to match your organization's brand. The structure does the heavy lifting — the colors are easy to change.

The icon stroke colors are set to match each theme's accent. If you change the accent color in the background, just do a global find-and-replace on the hex value in the icon SVGs and they'll update instantly. Or if you're working from the PNGs and need a color change, swap back to the SVG for that step.

---

## License

Free to use for personal and commercial projects. No attribution required, though it's always appreciated.

If you use these on something you're proud of, I'd genuinely love to see it.

---

## The YouTube channel

If you want to go deeper on Tableau design, dashboard UX, or data storytelling, that's what the channel is for. I cover everything from the basics to the kind of design thinking that most Tableau tutorials skip entirely.

New videos on a regular schedule. No fluff, no clickbait — just practical stuff for people who take their work seriously.

**[Subscribe on YouTube →](https://www.youtube.com/@WoodsAnalytics)**

---

*Questions, issues, or suggestions — open an issue or email me at woodsdataanalytics@gmail.com.*

*Connect on LinkedIn: [linkedin.com/in/kentonwoods](https://www.linkedin.com/in/kentonwoods/)*
