# Project: חומרי לימוד — ניר עוז-ארי

## What this is
A personal teacher portal for Nir Oz-Ari, centralizing interactive learning materials
for all subjects taught. Each subject has its own hub page. Content is built for
middle school students, Hebrew speakers, no assumed prior knowledge.

## Site structure
index.html              — teacher portal (3 subject cards: של"ח | אנגלית | העשרה)
shelach.html            — של"ח hub: 5 workshop cards, accent #f97316
shelach-nofadam.html    — סדנה: נופאדם (6 lessons, accordion)
shelach-mifhaz.html     — סדנה: המהפך הציוני במישור החוף (6 lessons, accordion)
shelach-har.html        — סדנה: ההר כערש האומה (6 lessons, accordion)
shelach-teva.html       — סדנה: מפגש טבע בארץ ישראל (6 lessons, accordion)
shelach-tarbuyot.html   — סדנה: מפגש תרבויות בארץ ישראל (6 lessons, accordion)
english.html            — אנגלית hub (stub, "בקרוב"), accent #38bdf8
enrichment.html         — העשרה hub (→ אבולוציה + future topics), accent #4ade80
evolution-hub.html      — אבולוציה module hub (was: index.html), 4 module cards
evolution.html          — Module 1: אבולוציה (7 stages)
coevolution.html        — Module 2: מירוץ החימוש בטבע (5 stages)
humanevolution.html     — Module 3: אבולוציה אנושית (5 stages)
controversies.html      — Module 4: ויכוחים ואתגרים (5 stages)
humanhand.jpg           — Gemini-generated: human hand bones (Module 1)
whalehand2.jpg          — Gemini-generated: whale flipper bones (Module 1)
fossils.jpg             — Gemini-generated: 8 labeled fossil types (Module 1, Stage 5)
DNA.jpg                 — Gemini-generated: DNA double helix (Module 1, Stage 5)

## Navigation chain
index.html → shelach.html / english.html / enrichment.html
shelach.html → shelach-nofadam / shelach-mifhaz / shelach-har / shelach-teva / shelach-tarbuyot
  each workshop page: accordion of 6 lessons, each with מצגות לשיעור + פעילויות ובחנים
  lesson content: future HTML presentations + interactive activities (all "בקרוב" for now)
enrichment.html → evolution-hub.html
evolution-hub.html → evolution.html / coevolution.html / humanevolution.html / controversies.html

## Design system
Font:         Alef (Google Fonts)
Theme:        Dark, modern, focused
Background:   #0d1117
Direction:    RTL, Hebrew

Subject accents (portal level):
  של"ח:    #f97316 (orange)
  אנגלית:  #38bdf8 (sky blue)
  העשרה:   #4ade80 (green)

Module accents (evolution hub level):
  Module 1: #4ade80 (green)
  Module 2: #f59e0b (amber)
  Module 3: #60a5fa (blue)
  Module 4: #a78bfa (purple)

Portal card style: background/header image per card (not emojis)
Image sources: Pixnio preferred (Wikimedia blocks server-side fetches)
⚠️  Portal card images pending — user to supply Pixnio URLs

## Presentation mode — מצגת למורה
- "מצגת למורה" button on hero screen of each module (modules 2–4 pending)
- Fullscreen overlay, dark theme, module accent color
- Layout: photo slides = image left / text right; icon slides = stacked column
- Content reveals one item at a time on click / arrow key (PowerPoint-style)
- Arrow ← goes back to previous slide (all items shown); ESC exits
- Each slide: stage label, title, bullet points, optional summary (centered green), activity box, question prompt
- Summary field renders as centered accent-colored conclusion line (not a bullet)
- Images saved as ev-*.* in project root (ev-deeptime.png, ev-fossil.jpg, ev-finches.jpg, ev-cheetah.png, ev-skulls.png, ev-lab.png, ev-darwin.jpg)
- Modules 2–4 presentation: TODO

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
Presentation: ✅ 7 slides, click-to-reveal, side-by-side photo layout

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
- No generic emojis as decorative icons — use real photos
- Module 1: locally saved images (relative paths)
- Module 2+: real photos linked directly from Wikimedia Commons, Pixnio, Giphy etc.
- No Gemini-generated animal images for Module 2+
- Wikimedia blocks server-side fetches (403) — always verify URLs in browser, or use Pixnio
- Always request direct link from user if URL cannot be verified

## Git
Repo: https://github.com/niroari/evolution
Evolution modules (1–4) live on Vercel (auto-deploy from GitHub main branch)
Portal + של"ח pages (index, shelach, shelach-*, english, enrichment, evolution-hub) built offline — not yet pushed
