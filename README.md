# APPSC Aptitude Study Companion

Responsive static study website covering lessons discussed through 16 October 2026. Open index.html directly; no build, login or dependencies required.

## Publication on GitHub Pages
Create public repository `appsc-aptitude`, upload these files to `main`, then Settings → Pages → Deploy from a branch → main → /(root) → Save.

## Content and maintenance
11 sections: number system; HCF/LCM; fractions; powers/roots; BODMAS; ratio/proportion; percentages; mean/median/mode; profit/loss/discount; interest; calculation shortcuts. Each includes concepts, Telugu summary, worked examples and practice with answers.

Canonical content is embedded in index.html so the page also works offline. topics.json is an editable copy. When updating, keep both in sync. Add new lessons after they are taught; do not label planned topics as completed. Preserve examples, explain shortcut conditions, check numerical answers and update the visible date. Do not include private personal information.

Progress uses browser localStorage only. No analytics or external runtime dependencies. Examples are teaching material, not authenticated previous exam questions. Refer to the applicable official syllabus for examination requirements.

## Continuing in ChatGPT
Ask: “Update rightfreelancer7/appsc-aptitude with the aptitude lesson we just discussed.” Commit updated content to the published branch; GitHub Pages redeploys it. Updates happen when requested in an active conversation, not by background monitoring of chats.
