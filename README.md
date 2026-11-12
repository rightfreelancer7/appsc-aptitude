# APPSC Aptitude Study Companion

Responsive static study website covering the cumulative lessons discussed in the APPSC aptitude conversation. Open index.html directly; no build, login or dependencies required.

## Publication on GitHub Pages
Create public repository `appsc-aptitude`, upload these files to `main`, then Settings → Pages → Deploy from a branch → main → /(root) → Save.

## Content and maintenance
15 sections: number system; HCF/LCM; fractions; powers/roots; BODMAS; ratio/proportion; percentages; mean/median/mode; profit/loss/discount; interest; calculation shortcuts; time/work; pipes/cisterns; speed/time/distance; trains/boats. Each includes concepts, Telugu summary, worked examples and practice with answers.

Canonical content is embedded in index.html so the page also works offline. topics.json is an editable copy. When updating, keep both in sync. Add new lessons after they are taught; do not label planned topics as completed. Preserve examples, explain shortcut conditions, check numerical answers and preserve the user’s simplified homepage. Do not include private personal information.

Progress uses browser localStorage only. No analytics or external runtime dependencies. Examples are teaching material, not authenticated previous exam questions. Refer to the applicable official syllabus for examination requirements.

## Continuing in ChatGPT
Standing instruction: update the webpage in the same turn whenever a new aptitude lesson is taught. No repeated request is needed. Commit synchronized index.html and topics.json to the published branch. Check deployment when accessible; report any blocker rather than silently omitting the update. This applies during active lessons; it is not background monitoring of other chats.
