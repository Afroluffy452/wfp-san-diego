# WFP San Diego website

Two static pages, no build step. Upload this folder to any static host.

- `index.html` - home page
- `calendar.html` - events calendar

## Before launch
1. **Links** - in `index.html`, edit the `LINKS` list near the bottom (sign-up, Discord, booking). They point to caworkingfamilies.org until replaced. `calendar.html` has the same placeholder in its "Join the Party" button and footer.
2. **Contact form** - submissions are emailed through FormSubmit (formsubmit.co) to the address in `FORM_TO` in `index.html`. The first submission sends an activation email to that inbox.
3. **Calendar** - `calendar.html` asks Mobilize for live events on each load and falls back to the saved list in the file. Add non-Mobilize events to the `CUSTOM` list near the bottom.
4. **Fonts** - headlines use Bebas Neue (the brand guideline substitute). Swap in PF Venue Condensed if you have a web license.
