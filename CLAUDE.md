# CLAUDE.md — anxiety_landing_page

## Project Overview
Hebrew RTL landing page for lead generation around the coaching exercise:
**"השער דרך הגוף"** — understanding anxiety through body sensations and the inner voice behind it.

**Coach:** גל זלצמן | מאמן אישי מוסמך
**WhatsApp:** +972528330884

## Goals
- Give the user a short 6-step interactive exercise
- Capture contact details to send personalized results
- Generate leads for personal/group coaching

## Tone & Content Rules
- Calm, warm, professional, grounded, coaching-oriented
- NOT medical, NOT diagnostic, NOT therapeutic promises
- Use wording like "התבוננות אישית ראשונית"
- No fear-based anxiety visuals
- Always include disclaimer: "התרגיל אינו אבחון או טיפול."

## Visual Direction
- Mobile-first, fully responsive
- RTL Hebrew (`dir="rtl"`, `lang="he"`)
- Beige/cream background (`#FAF7F2` range)
- Soft sage green accents (`#8FAF8F` range)
- Rounded cards, soft shadows
- Premium calm coaching/wellness feel

## Assets
- `logo_coach.jpeg` — coach logo, placed top-right in header
- `me_results.png` — coach photo, used in lead-capture section

## Tech Stack
- Single `index.html` with inline CSS and JS
- No backend, no packages
- Form submission is simulated (shows thank-you screen)
- Answers stored in JS variables only

## Structure
1. Header (logo + name)
2. Hero (title, subtitle, CTA button, disclaimer)
3. Intro card ("השער דרך הגוף")
4. Interactive exercise (6 steps, one at a time, progress bar)
5. Educational explanation section
6. Lead capture form (name, phone, optional email) + me_results.png
7. Thank-you screen
8. WhatsApp CTA

## Do Not
- Do not commit anything unless explicitly asked
- Do not add medical/therapeutic claims
- Do not overcomplicate the tech stack
- Do not use fear-based imagery or language
