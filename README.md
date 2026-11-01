# Athena Solutions website

Plain HTML and CSS: no build step, no JavaScript. Open `index.html` in a browser to view it.

| Page | Purpose |
|---|---|
| `index.html` | Home: what we build, Mann, how we work |
| `mann.html` | Mann product page, crisis numbers, provider sign-up |
| `about.html` | Mission, values, team |
| `contact.html` | Email and what to include |
| `privacy.html` | Mann privacy policy. The Play Store and App Store require a public URL for it. |

## Before going live
- [ ] `privacy.html`: fill in every highlighted item, get a legal review, then delete the "Draft for review" box.
- [ ] Check the team bio in `about.html`, and add anyone else.
- [ ] Recheck the crisis numbers (1166, 100, 102) against `mha-backend/src/modules/crisis/crisisResources.ts`.
- [ ] Swap the "coming soon" badges in `mann.html` for store links when Mann is published.

## Deploy (free)
Any static host works. With **Cloudflare Pages**: push this folder to a GitHub repo, then go to
Cloudflare → Workers & Pages → Create → Pages → connect the repo. Leave the build command empty and
set the output directory to `/`. Then add your custom domain.
