# 🧮 MeridiConvert

**A free all-in-one unit converter, graph-paper drafting, graphing calculator and calculation toolbox — in your browser.**
尺・坪・合も使える、広告なし・登録なしの無料単位変換・グラフ電卓・計算の道具箱。

👉 **[Open MeridiConvert](https://meridibrand.com/convert/)**

## What's inside / できること
| Tab | Contents |
|---|---|
| 🧮 Units / 単位変換 | 11 categories, ~150 units incl. traditional Japanese units (尺・坪・升), expressions, favorites, history |
| 📐 Graph paper / 方眼紙の作図 | Click points to get area (m² / 坪 / 畳), perimeter, side lengths and angles; volume with thickness; PNG export |
| 📏 Shapes / 図形の計算 | 10 plane + 7 solid shapes, triangle solver, slopes (% / 寸勾配 / degrees / 1:n) |
| 🔢 Numbers / 数の道具 | Scientific calculator, number bases, ratios & tax, scale, dates & working days, Japanese era |
| 🛠 On-site / 現場の計算 | Paper sizes, price per 坪 ⇔ m², lumber, concrete, tiles, stairs, electricity cost, paint & wallpaper |
| 📈 Graph / グラフ 🆕 | Up to 5 expressions, sliders, polar, parametric, sequences, regions, implicit equations (x² + y² = 9), area, tangent, f′ & ∫f, curve fitting, table of values, 32 examples |

Every tool has a 🔰 example button, 🔗 share link and 🖨 print view.

## 📈 Graph tab highlights / グラフのタブ
- Type it the usual way: `2x+1`, `3(x+1)`, `x^2` (shown as x²), full-width characters OK — parsed without `eval`
- `x = 2` vertical lines, `y > x` shaded regions, `x² + y² = 9` drawn as-is
- Polar `r = 2cos(3θ)`, parametric `(cos t, sin 2t)` with ▶ moving-dot animation, sequences `a_n = 3^(n−1)` with Σ
- Letters like `a`, `b`, `k` become sliders automatically (▶ to animate)
- Intersections, peaks & valleys, zeros, y-intercepts; shaded area, tangent & slope
- Paste data → linear / quadratic / exponential fits compared by R²
- ⌨️ Phone keypad (², ³, √, π, θ, ≤ …); on phones the graph sits on top
- 32 everyday & math examples: shipping, electricity, stopping distance, taxi, price per 坪, time zones, loans, compound interest, a thrown ball…

## Notes / ご注意
- Results are approximate guides. Please double-check before using them for construction, contracts or anything important.
  計算結果は目安です。工事や契約など大事な場面では、必ずご確認ください。
- Prices and rates in the graph examples (shipping, electricity, taxi, etc.) are examples only. / グラフの例の料金・単価は「例」です。
- Not a replacement for an exam calculator. / 試験で使える電卓の代わりではありません。
- Public holidays are not included in the working-day calculator. / 営業日の計算に祝日は含まれていません。

## Privacy
No ads, no sign-up, no tracking cookies. Everything runs in your browser (a share link only goes to whoever you send it to). We only count page views with [GoatCounter](https://www.goatcounter.com/).

## Support
☕ [Buy Me a Coffee](https://buymeacoffee.com/meridius) · 💬 [Feedback](https://github.com/meridi-support/meridi-square/discussions)

## Other tools by Meridi Brand
📅 [MeridiMeet](https://meridibrand.com/meet/) · 🐾 [MeridiLingo](https://meridibrand.com/lingo/) · 💻 [MeridiSync](https://meridistore.booth.pm/items/8790105) · 🌌 [MeridiStars](https://meridibrand.com/stars/) · 🪨 [MeridiGround](https://meridibrand.com/ground/) · 🌊 [MeridiDepths](https://meridibrand.com/depths/) · 🎮 [MeridiPlay](https://meridibrand.com/play/) · 🧰 [Meridi Tools](https://meridibrand.com/tools/)

## Changelog
### 🧮 v1.1.0 — 2026-11-17
- 📈 New 6th tab: **Graph**
- Up to 5 colour-coded expressions; parsed without `eval`, with friendly error hints (Japanese / English)
- Vertical lines (`x = 2`), shaded regions (`y > x`, `y ≤ x²`; dashed = edge not included, solid = included)
- Implicit equations drawn as-is (`x² + y² = 9`, `2x + 3y = 6`, heart, ellipse)
- Polar (`r = 2cos(3θ)`), parametric (`(cos t, sin 2t)`), ▶ moving-dot animation
- Sequences (`a_n = 3^(n−1)`) with first terms and Σ
- Automatic sliders for letters like a, b, k (▶ to animate, adjustable range & step)
- Key points: intersections, peaks & valleys, zeros, y-intercepts (tap to jump)
- Shaded area (vs. x-axis or between two curves), tangent & slope (tap a curve to move it)
- f′(x) and ∫f graphs overlaid
- Data: paste a table, compare linear / quadratic / exponential fits by R², insert the fit as an expression
- Table of values (start / step / rows)
- ⌨️ Phone keypad, with an option to keep the phone keyboard hidden
- Squares & cubes typed as `x^2`, shown as x² in a textbook-style preview
- 🔰 32 examples in 4 groups of 8 (Basics / Shapes / Everyday / Money, motion & data)
- 📷 PNG export (includes expressions, slider values, area & slope)
- 📱 Two columns on PC; graph on top and controls below on phones & tablets
- 🔗 Share, 🖨 Print, 🌐 language and ☀️ theme now work on the Graph tab (share links open straight to the graph)
- Links between 🛠 ⚡ Power & cost and 📈 Graph ("See it as a graph →" / "Open in Site & DIY")
- Electricity example aligned with On-site (flat 31 yen/kWh) plus a separate tiered-rate example
- Version button with info & changelog added at the top right
- Checked with known answers: ∫₀³x² = 9, area between x² and x+2 = 4.5, ∫₀^π sin x = 2, slope of x³ at 2 = 12, ball (15 m/s, 45°) ≈ 23.0 m, stopping distance at 60 km/h ≈ 32.7 m, 1 + 3 + … + 3⁷ = 3,280

### 🧮 v1.0.0 — 2026-11-13
- First release with 5 tabs
- 🧮 Units: 11 categories, ~150 units incl. traditional Japanese units (尺・坪・升), expressions, favorites, history, significant figures
- 📐 Graph paper: area (m² / 坪 / 畳), perimeter, side lengths, angles, volume with thickness, compass, PNG export, keyboard controls
- 📏 Shapes: 10 plane + 7 solid shapes, triangle solver, slopes (% / 寸勾配 / degrees / 1:n)
- 🔢 Numbers: scientific calculator, number bases, ratios & tax, scale, dates & working days, Japanese era
- 🛠 On-site: paper sizes, price per 坪 ⇔ m², lumber, concrete, tiles, stairs, electricity cost, paint & wallpaper
- 🔰 Example buttons, 🔗 share links, 🖨 print view, Japanese / English

## License
MIT © 2026 Meridi Brand
