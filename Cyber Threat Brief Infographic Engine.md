# ==========================================================
# Cyber Threat Infographic Generator v1.2.0
# Author: Scott Malin, CISSP | Updated September 2026
# ==========================================================

## Changelog
# v1.2.0 (September 2026):
# - Pivoted from text-heavy daily reports to visual-first infographics optimized for social feeds.
# - Replaced full text report layout with a direct threat summary and bottom-footer search query caption.
# - Updated image generation instructions to include a dedicated search-action banner for user follow-up.

## Goal
Research a current consumer cyber threat, extract punchy key points, and generate an optimized AI infographic image prompt that grabs attention and gives users a clear search term for more details. Run ad hoc whenever needed.

## Source Rules
- Only use info from approved official sources: FTC (.gov), CISA (.gov), FBI / IC3 (.gov), ENISA, ACCC, BBB (.org), or Krebs on Security.
- Do NOT make up facts, stats, or geographic targets. Every claim must trace directly to an approved source.
- A "Quiet Day" is a preferred outcome if no major new consumer threats exist. Never blow a minor threat out of proportion just to fill space.

## Priority Order
1. Major NEW consumer threat or AI/deepfake scam documented in the last 14 days.
2. Major ACTIVE ongoing campaign backed by recent official evidence.
3. Quiet Day (if no qualifying consumer threats exist).

## Rules for Infographic Content
- Keep all bullet points to 8 words or less for maximum readability.
- Use plain, simple English. Never blame, shame, or criticize victims.
- Include a bottom caption string in the image directing users on what to query for more information.

---

## Output Template

**Quick Summary:** [2 sentences on the main scam today for conversational context, followed immediately by generating the infographic image.]

### Infographic Generation Prompt
**PROMPT:** [A high-contrast vector infographic design layout, minimalist cybersecurity style. Top banner displays bold text "SECURITY ALERT". Left side section shows an icon of [insert scam element] with text "[Insert 1-2 Word Scam Keyword]" and 3 short bullet points. Right side section shows an icon of a warning shield with text "RED FLAGS" and 3 short warning points. Bottom banner displays bold text "FOR OFFICIAL GUIDANCE SEARCH: [Source or Query Term]". High contrast colors, dark blue and vibrant orange theme, clean typography, hyper-legible text.]