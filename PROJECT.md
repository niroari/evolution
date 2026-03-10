# Project: לומדות אבולוציה

## What this is
Interactive self-learning modules teaching middle school students about evolution,
with no assumed prior knowledge. Each module is a standalone HTML file.

## Target audience
Middle school students, low-to-medium academic level, Hebrew speakers.

## File structure
index.html            — hub/landing page (4 module cards, "שיעור 1–4" labels,
                        animated background DNA emoji, glassmorphism cards)
evolution.html        — Module 1: אבולוציה (7 stages)
coevolution.html      — Module 2: מירוץ החימוש בטבע (5 stages)
humanevolution.html   — Module 3: אבולוציה אנושית (5 stages)
controversies.html    — Module 4: ויכוחים ואתגרים (5 stages)
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
Module 4:     accent #a78bfa (purple)
Direction:    RTL, Hebrew

## Module 1 — אבולוציה ✅ (live on Vercel)
1. מבוא          ✅ hook question + vote + correct/wrong feedback + bone images
2. ברירה טבעית   ✅ beetle survival game (4 rounds, timer, bar chart)
                    + dynamic outcome text (green wins / red wins / tie)
                    + locked placeholder shown until game ends
3. תורשה         ✅ heredity lab (beetle mixer, mutations)
4. הזמן הגדול    ✅ scale cards + 8-event timeline (dots clickable, non-linear nav) + scale bar
5. ראיות         ✅ 4 click-to-reveal evidence cards + YouTube video link per card
6. דוגמאות       ✅ 4-card gallery slider + YouTube video link per card (centered)
7. בוחן          ✅ 6-question MCQ + Google Forms + YouTube link button
                    (name=1688849251, class=1737489614, score=2011009170)

## Module 2 — מירוץ החימוש בטבע ✅ (live on Vercel)
1. מבוא          ✅ cheetah/deer vote + arms race cycle diagram
2. טורף ונטרף    ✅ 3 predator-prey cards with real Wikimedia photos
3. הסוואה וחיקוי ✅ stick insect reveal game + octopus GIF + monarch/viceroy pair
4. שיתוף פעולה   ✅ bee orchid, fig wasp, birds+fruit cards
5. בוחן          ✅ 5 MCQ + Google Forms + YouTube link button
                    (name=1662845623, class=1846907217, score=1990643179)

## Module 3 — אבולוציה אנושית ✅ (live on Vercel)
1. מבוא          ✅ vote + chimp photo + DNA comparison cards (98.8% / 85% / 60%)
2. עץ המשפחה    ✅ interactive 4-node timeline (Australopithecus → habilis → erectus → sapiens)
3. מה הפך אותנו לאנושיים? ✅ cave art image + 4 cards (שפה, אש, כלים, שיתוף פעולה)
4. ניאנדרתלים    ✅ reconstruction photo (Pixnio) + 3 cards + DNA surprise box (2–4%)
5. בוחן          ✅ 6 MCQ + Google Forms + YouTube link button (EN, enrichment)
                    (name=1753846366, class=240948921, score=923537609)

## Module 4 — ויכוחים ואתגרים ✅ (live on Vercel)
1. מבוא          ✅ vote + 97% scientist consensus reveal + module disclaimer
2. "רק תיאוריה"  ✅ everyday vs. scientific "theory" + examples (gravity, germ theory etc.)
3. דת ומדע       ✅ Catholic / Jewish / Islamic positions + "how vs. why" framing
4. שאלות פתוחות  ✅ 4 open questions (origin of life, eye, evolution rate, junk DNA)
5. בוחן          ✅ 5 MCQ + Google Forms
                    (name=698754440, class=730348424, score=1540593400)

## YouTube videos
- All videos use link buttons (not iframes) — some videos block embedding (Error 153)
- Module 1 quiz: https://www.youtube.com/watch?v=TLt5xPefG74
- Module 1 Stage 5 (ראיות) per-card videos:
  - מאובנים: https://www.youtube.com/watch?v=bRuSmxJo_iA
  - DNA: https://www.youtube.com/watch?v=zwibgNGe4aY
  - מבנים שאריתיים: https://www.youtube.com/watch?v=UHbcjzkjG0o
  - אבולוציה בזמן אמת: https://www.youtube.com/watch?v=V9ZFMoh3hJk
- Module 1 Stage 6 (דוגמאות) per-card videos:
  - כלבים: https://www.youtube.com/watch?v=9Y5Fwp7i-0E
  - ציפורי דרווין: https://www.youtube.com/watch?v=s64Y8sVYfFY&t=10s
  - לוויתן: https://www.youtube.com/watch?v=_OSRKtT_9vw
  - חיידקים: https://www.youtube.com/watch?v=V9ZFMoh3hJk
- Module 2: https://www.youtube.com/watch?v=_zGy_tr_tY4
- Module 3: https://www.youtube.com/watch?v=DZv8VyIQ7YU (EN, enrichment note shown)
- Module 4: no video yet

## Images policy
- Module 1: locally saved images (relative paths)
- Module 2+: real photos linked directly from Wikimedia Commons, Pixnio, Giphy etc.
- No Gemini-generated animal images for Module 2+
- Always verify image URLs before using — request direct link from user if fetch fails

## Git
Repo: https://github.com/niroari/evolution
All 4 modules live on Vercel (auto-deploy from GitHub main branch)
