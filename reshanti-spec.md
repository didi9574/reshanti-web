# Reshanti — desktop build spec
Source: Figma file `Z6XvDXP0ZZ1n04N0rmuiZa`, page `DESIGN SYSTEM`.
Frames: Color `333:263` · Button-WEB `333:294` · Button-PHONE `338:583` ·
FONT-WEB `333:355` · Navbar-WEB `333:390` · cards-WEB `333:470` · table `422:1412`.

## Layout
Page 1440 · content 1080 · side padding 180. Section padding 88px.

## Type (desktop)
| role | font | size/lh |
|---|---|---|
| H1 | Fraunces Regular | 34/40, tracking -0.34 |
| H2 | Source Serif 4 Regular | 15/20 |
| H3 | Source Sans 3 Medium | 14/18 |
| H4 | Source Sans 3 Medium | 13/16 |
| H5 | Source Sans 3 Medium | 12/14 |
| body S / M / L / XL | Source Sans 3 Regular | 13/20 · 14/22 · 15/24 · 16/24 |
| body fancy XL | Fraunces Light | 15/28 |
| card H1 | Fraunces 72pt SemiBold | 16/24 |
| card H2 | Source Sans 3 Medium | 15/24 |
| card body | Source Serif 4 Regular | 14/24 |
| nav on / off | Source Sans 3 Reg / Med | 13/20 |
| button navbar | Source Sans 3 Medium | 14/18 |
| button | Source Sans 3 Medium | 16/24 |
| number / number-lg | Source Serif 4 Regular | 15/24 · 24/28 |

## Buttons — radius 8, border 0.8px
- M: h48, 12/36, text 16/24 · S: h44, 8/36, text 14/18
- nav: h44, 12/24, text 14/18 · hero: h44, 8/32, text 14/20
- pill: radius 100, 16/48, text 16/24
- green `#1E6B5C` → hover `#3EAE9B` (text `#FAFAFA`)
- coral `#E08868` → hover `#EC8C38`
- outline green border+text `#1F8C5C` → fills on hover
- outline orange border+text `#EC8C38` → fills on hover

## Navbar
Wrap 1080 × 88. Absolute: logo x0 · pill list x292 y20 · actions x891 (gap 4).
Bar: `rgba(245,235,221,.46)` + `blur(4px)`, bottom border 0.8px `--hairline`.
Pill list bg `#F5EBDD`, radius 30, padding 4. Link 8/16, radius 24, `--shadow-pill`.
Inactive Source Sans 3 Medium 13/20 `#C99A56`; active bg white, Regular, `#603314`.

## Teacher card — 263 × 539
radius 16, padding 24/12, gap 12, bg white, border 0.8px `--hairline`.
Photo h326 radius 12. RYT badge 32×17 radius 12 bg `#F8F3ED` text `#3EAE9B` 10/12.
"First Session Free" 107×24 radius 20 bg `#DCEFEA` text `#21342E` 10/12.
Meta 13/20 `#656565`. Price Source Serif 4 15/24 `#21342E`, `/session` 12/16 `#65877C`.
Button: outline green S, width 130.

## Single / Weekly cards — 532 wide
radius 20, padding 32/48, outer gap 32, inner gap 24.
Head block 60×436: tag Source Serif 4 14/24 at top, title card-H1 at +28.
List Source Sans 3 15/24 `#21342E`, padding-left 22.5.
Single: bg `#FFF4EA`, no border, outline-green button.
Weekly: bg white, border 1px `--hairline-dark`, `--shadow-mint`, coral button.
Tag colours: single `#1F8C5C` · weekly `#E08868`.

## FAQ row — 1080 × 76
radius 12. Default bg white, hover/open `#F8F3ED`.
Question Source Serif 4 15/20 `#121212` at x32 y16. Answer Source Sans 3 14/22 `#65877C`.
Plus: Fraunces 34/40 tracking -0.34, `#E08868` → `#EC8C38`, at x1028, 56px box.

## Footer — 1440 × 386, inner 1080 × 296
bg `#21342E`. Grid 3fr 1fr 1fr 1fr, column-gap 28.
Brand Fraunces 18/24 `#F5EBDD`; desc Source Sans 3 13/20 `#A19F9F` w349.
Col heads Source Serif 4 12/16 `#C99A56`; links Source Sans 3 14/22 `#F8F3ED` gap 8.
Bottom rule + text `#958073`, Source Serif 4 12/16. Social 24px icons gap 12.

## Motion rules
Reveal at 15% into viewport, fires once, never on scroll-up.
Nothing travels more than 24px. Fade + small lift only.
Hero breath + final-CTA glow are the only loops (plus play-button pulse).
Testimonial highlight: sweeps 1100ms, staggered per card, stays.
Colours `rgba(188,255,237,.40)` mint, `rgba(224,136,104,.30)` warm.

## Section backgrounds
hero gradient-mint · benefits/teachers `--surface-page` · how gradient-warm ·
testimonials/ways `--surface-page` · comparison white · recruit/faq `--surface-page` ·
final gradient-warm · footer `#21342E`.

## Still unspecified (ask before building)
- Teacher-recruitment block: no component in the design system file.
- Hero frame geometry: estimated from the flattened mockup.
- Vertical rhythm between sections: estimated.
