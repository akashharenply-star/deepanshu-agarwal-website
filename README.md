# Er. Deepanshu Agarwal: personal website (landing page)

One page, no build step, no framework. Open `index.html` in a browser to preview.

## Files
- `index.html`: the whole page (HTML, CSS and a small script).
- `images/ply-to-profit-cover.jpg`: book cover.
- `images/er-deepanshu-agarwal.jpg`: portrait (4:5 crop).

## Must do before going live
1. **WhatsApp number.** In `index.html`, search for `WA_NUMBER` (near the bottom). Replace `91XXXXXXXXXX` with country code plus number, digits only, e.g. `919876543210`. Until this is set, the "Join on WhatsApp" button does nothing and shows a setup note.
2. **Test the sign-up.** Type a name, tap the button, and check WhatsApp opens with: "Hi, I am <name>, and I want to join your webinar on Ply to Profit."
3. **Check the Amazon links.** Search for `amzn.in` (buy link: `09Oc5tLg`, product-question link: `0019wxyO`) and open both.
4. **Social preview image.** Once the domain is live, uncomment and fill the `og:image` line in the `<head>` with the full URL of the cover.

## Common edits
- **Webinar day/time:** search for `Join the next webinar`; add the fixed day and time in the paragraph below the heading.
- **Text:** all copy is plain HTML. Names must always read **Er. Deepanshu Agarwal** (spelling D-E-E-P-A-N-S-H-U).
- **Colours and fonts:** the `:root{...}` block at the top of the `<style>` section.
- **Images:** replace the files in `images/` with the same file names.
- **Do not add** Haren Ply links or mentions: the page deliberately does not lead visitors to Haren Ply yet.

## Making it live (domain: deepanshuagarwal.com)
Easiest options, all free for a page like this:
- **Netlify Drop** (app.netlify.com/drop): drag the whole folder in, then add the custom domain.
- **Vercel / Cloudflare Pages / GitHub Pages:** upload the folder as a static site.
- Then, at the domain registrar, point the domain's DNS to the host as the host instructs. HTTPS is added automatically.

Fonts load from Google Fonts, so the live page needs internet access (normal for any website).
