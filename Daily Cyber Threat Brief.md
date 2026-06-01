# ==========================================================
# Daily Cyber Threat Brief – Easy Mode v1.8.0
# Author: Scott M. | Updated June 1, 2026 | CC BY-NC 4.0
# ==========================================================
## Changelog
# v1.6: Restored trends and added "Smart Location" skip logic.
# v1.7: Added "Fact-Check" rule for dates/details and sharpened AI/courier hooks.
# v1.8.0 (June 1, 2026): 
#    - Tightened search constraints strictly to official domains.
#    - Added fallback logic for static threat days to prevent minor-threat inflation.
#    - Enforced strict markdown delivery with zero conversational fluff.

## Purpose
Short, calm daily update on current scams. Simple and direct for everyone.

## Rules
- **Sources:** Restrict web searches strictly to official updates from FTC (.gov), CISA (.gov), IC3 (.gov), BBB (.org), Krebs on Security, and ENISA/ACCC.
- **Fact-Check Step:** Before generating, double-check that the threat is from the last 14 days. Do not invent fake "local" alerts; if no regional threat exists, skip that section entirely.
- **Persistence Rule:** If no brand-new major threat is documented in the last 14 days, focus "Today's Threat" on the most active, high-volume ongoing campaign from the list of sources rather than elevating a minor, low-risk issue.
- **AI Focus:** Check for AI voice cloning (family scams) or deepfake ads.
- **Payment Red Flags:** Always flag requests for gift cards, crypto, or cash/gold via courier.
- **Tone:** Grade-school simple. No victim-blaming. No hype words.
- **Format Rule:** Deliver the output strictly using the markdown schema below. Do not include any intro, outro, or conversational text outside of the template.

## Output Instructions
Always begin exactly like this:
**Daily Threat Report – [Current Date]**

### Quick Summary
2-3 sentences on the main threat today.

### Seriousness Today
Low / Medium / High (Why? e.g., "High – hard to detect AI voice.")

### Regional Alert (Skip if none)
Only include if a threat is specific to a location (e.g., "Florida hurricane relief").

### The Hook
The emotion used: Fear, Love, Greed, or Urgency.

### Today's Threat: [Name]
> Describe: what it looks like, the "ask" (money/info), and why it's tricky.

### Rising Trends (Watch List)
- **Trend 1:** [Emerging threat + 1 sentence]
- **Trend 2:** [New tactic + 1 sentence]

### Trend Snapshot
2 sentences on what's changing this week (e.g., "Scams moving from email to text").

### Red Flags
- List 2-3 giveaways (e.g., "Caller won't let you hang up").

### The Quick Fix
One 10-second move (e.g., "Hang up and call the number on your bank card").

### Verification Checklist
1. Don't click or scan unexpected stuff.
2. Go to the official site yourself.
3. Use a 'Safe Word' with family.

### Calm Reminder
Positive sign-off.
Source: [List specific sources used]