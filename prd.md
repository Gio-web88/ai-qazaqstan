# PRD — AI·Qazaqstan Website

**Version:** 1.0
**Date:** August 2026
**Status:** Draft
**Owner:** [Your name]

---

## 1. Overview

AI·Qazaqstan is a public website promoting AI training and literacy across Kazakhstan for **all generations** — schoolchildren, students, working professionals, and seniors. The site inspires people to learn about AI, demonstrates practical applications relevant to Kazakh life, and stimulates open community discussion about AI's role in the country's future.

## 2. Problem Statement

Kazakhstan is investing heavily in its digital future (Digital Kazakhstan strategy, smart city programs, growing IT sector), but AI literacy among the general population is uneven. Existing AI education targets mostly IT professionals and students, leaving children, non-technical workers, and seniors behind. There is no accessible, multilingual, generation-inclusive entry point for AI learning and public discussion.

## 3. Goals & Objectives

| Goal | Objective |
|---|---|
| Inspire AI learning | Provide clear, age-appropriate learning paths for 4 generational segments |
| Show practical value | Showcase real AI applications in Kazakhstan-relevant sectors |
| Stimulate discussion | Host discussion topics, topic submission, and monthly meetups |
| Reach everyone | Support Kazakh, Russian, and English; accessible design for all ages |

### Success Metrics (first 6 months)
- 10,000 unique visitors
- 500 newsletter subscribers
- 100 discussion topic submissions
- 20 workshop/event registrations per event
- Traffic from at least 10 of Kazakhstan's 17 regions

## 4. Target Audience

1. **Kids & Teens (7–17):** learn via games, school projects, creative AI tools
2. **Students (18–25):** courses, careers, pathways into the IT sector
3. **Professionals (25–60):** applied AI in agriculture, finance, energy, healthcare, education
4. **Seniors (60+):** everyday AI tools, online safety, scam awareness

Secondary: teachers, libraries, regional government programs, Astana Hub community.

## 5. Scope — v1 Features

### 5.1 Hero Section
- Headline "AI for every generation in Kazakhstan" with Kazakh-language subtitle
- CTAs: "Start learning" and "Join the discussion"
- Key stats (learning paths, regions, languages)

### 5.2 Why AI Matters
- Narrative connecting AI to Kazakhstan's digital strategy
- Benefits card: workplace confidence, scam/deepfake awareness, careers, civic voice

### 5.3 Learning Paths (4 cards)
- One card per generation with age range, description, and link to track

### 5.4 Practical Applications Showcase (interactive tabs)
- Sectors: Agriculture, Language (Kazakh/Russian/English), Smart Cities, Healthcare, Small Business
- Each panel: explanation + a concrete "Try it" example localized to Kazakhstan

### 5.5 Discussion Hub
- Featured topics with comment counts and meetup dates
- "Join discussion" action per topic
- Topic submission form (name optional + topic text)
- Monthly online meetups promotion

### 5.6 Events & Workshops
- List of upcoming free trainings (date, title, city/venue, in-person/online/hybrid)

### 5.7 Footer
- Newsletter signup, navigation, contact info, social links

### 5.8 Language Support
- EN / ҚАЗ / РУС toggle (v1: visual placeholder; v2: full translations)

## 6. Design Requirements

- **Palette:** Kazakh flag turquoise (#0EA8C4), gold (#F5B800), steppe-night navy (#0B1F2A), sand (#F7F3EA)
- **Typography:** Unbounded (display), Inter (body), IBM Plex Mono (labels)
- Mobile-first, responsive down to 360px
- Large readable text and high contrast for older users
- Smooth scrolling, subtle scroll-reveal animations, `prefers-reduced-motion` respected
- Sticky navigation with mobile hamburger menu

## 7. Technical Requirements

- **v1:** Single self-contained HTML file (embedded CSS/JS, no external dependencies except Google Fonts)
- Static hosting (Netlify / GitHub Pages / Vercel), target domain: `ai-qazaqstan.kz`
- No backend in v1: forms give in-page confirmation only
- Page load < 2s on 3G; Lighthouse accessibility score ≥ 90

## 8. Out of Scope (v1)

- Real user accounts, authentication
- Persistent forum/comments backend
- Payment or course delivery platform
- Full ҚАЗ/РУС translations (v2)
- CMS/admin panel

## 9. Future Roadmap (v2+)

1. Full Kazakh and Russian translations
2. Backend for discussion forum, topic submissions, and newsletter (e.g., Supabase + email provider)
3. Event registration with calendar integration
4. Actual course content / partnerships with local universities and Astana Hub
5. Regional ambassador program pages
6. Analytics (privacy-respecting, e.g., Plausible)

## 10. Risks & Mitigations

| Risk | Mitigation |
|---|---|
| Low engagement from seniors | Partner with regional libraries; hybrid events; large-text UI |
| Language barrier limits reach | Prioritize ҚАЗ/РУС translations in v2 |
| Forms with no backend feel fake | Clear v1 messaging; connect forms to a form service (e.g., Formspree) early |
| Content becomes outdated | Monthly content review cadence for events and topics |

## 11. Milestones

| Milestone | Target |
|---|---|
| v1 static site live on shared URL | Week 1 |
| Custom domain + form backend | Week 3 |
| ҚАЗ/РУС translations | Week 6 |
| First online meetup hosted | Week 8 |
| Discussion forum backend | Week 12 |
