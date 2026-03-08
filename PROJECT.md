# Project: לומדה אבולוציה

## What this is
An interactive self-learning module teaching middle school students about evolution,
with no assumed prior knowledge. Built as a standalone HTML file.

## Target audience
Middle school students, low-to-medium academic level, Hebrew speakers.

## File structure
evolution.html     — the full module (single file, all CSS + JS inline)
humanhand.jpg      — Gemini-generated image: human hand bones
whalehand.jpg      — Gemini-generated image: whale flipper bones
fossils.jpg        — Gemini-generated image: 8 labeled fossil types (used in Stage 5)
DNA.jpg            — Gemini-generated image: DNA double helix (used in Stage 5)
Images are saved locally in the project folder (not linked from external URLs).

## Design system
Font:       Alef (Google Fonts)
Theme:      Dark, modern, focused
Background: #0d1117
Accent:     #4ade80 (green — life/nature theme)
Direction:  RTL, Hebrew

## Stage structure (7 stages)
1. מבוא          ✅ hook question + vote + bone images (humanhand.jpg, whalehand.jpg)
2. ברירה טבעית   ✅ definition + concept cards + beetle survival game (4 rounds, timer, history chart)
3. תורשה         ✅ definition + concept cards + heredity lab (beetle mixer, mutations)
4. הזמן הגדול    ✅ scale cards + 8-event clickable timeline + final scale bar
5. ראיות         ✅ 4 click-to-reveal evidence cards (fossils, DNA, vestigial, real-time evolution)
6. דוגמאות       ✅ 4-card gallery slider (dogs, Darwin's finches, whale, bacteria)
7. בוחן          ✅ 6-question multiple choice quiz, shuffled answers, score screen

## Pending
- Teacher submission feature: students submit name + score to Google Classroom at end of quiz.
  Planned approach: Google Forms pre-fill URL (teacher creates form, shares edit link,
  field IDs extracted and baked into HTML). Waiting for teacher to create the form.

## Images
- Use Gemini to generate illustrations when needed, or search for free scientific images
- Save locally in project folder, reference with relative paths
- Add scientific source credit in captions where relevant
