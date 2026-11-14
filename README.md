# tax-calc-styles

Style playground for [weekendcraft/tax-calculator](https://github.com/weekendcraft/tax-calculator) — the exact same calculator app (logic untouched, markup emoji-free) rendered in five distinct visual directions so we can compare before picking one for the main app.

**Live:** https://weekendcraft.github.io/tax-calc-styles/ (switch styles from the bottom bar, or `?theme=swiss` in the URL)

| Theme | Direction |
|---|---|
| Ledger | Editorial / financial print — paper, hairline rules, serif, oxblood |
| Swiss | International typographic — white, black + one red, zero radius, mono numerals |
| Studio | Warm minimal — soft paper, olive-sand neutrals, terracotta accent |
| Terminal | Dark phosphor console — mono everything, green UI, amber headline numbers |
| Brutal | Neo-brutalist — cream, fat black frames, hard offset shadows, yellow |

Structure: `base.css` holds layout + the styling contract (CSS variables); each `themes/*.css` sets the variables and restyles the same markup. The calculator logic is byte-identical to the main repo.
