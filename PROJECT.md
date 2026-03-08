# Project: לומדות אבולוציה

## What this is
Interactive self-learning modules teaching middle school students about evolution,
with no assumed prior knowledge. Each module is a standalone HTML file.

## Target audience
Middle school students, low-to-medium academic level, Hebrew speakers.

## File structure
index.html            — hub/landing page (3 active module cards)
evolution.html        — Module 1: אבולוציה (7 stages)
coevolution.html      — Module 2: מירוץ החימוש בטבע (5 stages)
humanevolution.html   — Module 3: אבולוציה אנושית (5 stages)
humanhand.jpg         — Gemini-generated: human hand bones (Module 1)
whalehand2.jpg        — Gemini-generated: whale flipper bones (Module 1)
fossils.jpg           — Gemini-generated: 8 labeled fossil types (Module 1, Stage 5)
DNA.jpg               — Gemini-generated: DNA double helix (Module 1, Stage 5)

## Design system
Font:         Alef (Google Fonts)
Theme:        Dark, modern, focused
Background:   #0d1117
Module 1:     accent #4ade80 (green)
Module 2:     accent #f59e0b (amber)
Module 3:     accent #60a5fa (blue)
Direction:    RTL, Hebrew

## Module 1 — אבולוציה ✅ (live on Vercel)
1. מבוא          ✅ hook question + vote + bone images
2. ברירה טבעית   ✅ beetle survival game (4 rounds, timer, bar chart)
3. תורשה         ✅ heredity lab (beetle mixer, mutations)
4. הזמן הגדול    ✅ scale cards + 8-event timeline + scale bar
5. ראיות         ✅ 4 click-to-reveal evidence cards
6. דוגמאות       ✅ 4-card gallery slider
7. בוחן          ✅ 6-question MCQ + Google Forms submission
                    (name + class + score; entry IDs: 1688849251 / 1737489614 / 2011009170)

## Module 2 — מירוץ החימוש בטבע ✅ (complete locally, not pushed yet)
1. מבוא          ✅ cheetah/deer vote + arms race cycle diagram
2. טורף ונטרף    ✅ 3 predator-prey cards with real Wikimedia photos
3. הסוואה וחיקוי ✅ stick insect reveal game + octopus GIF + monarch/viceroy pair
4. שיתוף פעולה   ✅ bee orchid, fig wasp, birds+fruit cards
5. בוחן          ✅ 5 MCQ + Google Forms submission
                    (name=1662845623, class=1846907217, score=1990643179)

## Module 3 — אבולוציה אנושית ✅ (complete locally, not pushed yet)
1. מבוא          ✅ vote "מה ההבדל בינינו לבין שימפנזה?" + chimp photo + DNA comparison cards
2. עץ המשפחה    ✅ interactive 4-node timeline (Australopithecus → habilis → erectus → sapiens)
3. מה הפך אותנו לאנושיים? ✅ cave art image + 4 cards (שפה, אש, כלים, שיתוף פעולה)
4. ניאנדרתלים    ✅ reconstruction photo + 3 cards + DNA surprise box (2–4%)
5. בוחן          ✅ 6 MCQ + Google Forms submission
                    (name=1753846366, class=240948921, score=923537609)

## Planned modules (ideas)
- Module 4: ויכוחים ואתגרים (controversies in evolution)
- More ideas TBD

## Images policy
- Module 1: locally saved images (relative paths)
- Module 2+: real photos linked directly from Wikimedia Commons, Pixnio, Giphy etc.
- No Gemini-generated animal images for Module 2+
- Always verify image URLs before using (request direct link from user if unsure)

## Git
Repo: https://github.com/niroari/evolution
Push only when user confirms (modules 2 and 3 not yet pushed)
