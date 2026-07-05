# Good Tides Only — Website

Source for goodtidesonly.com, a vacation rental site for the 5917 Beach Blvd property in Gulf Shores, AL.

## Deploy
Static HTML/CSS/JS — no build step, no framework. Netlify publish directory is repo root (`/`), build command is empty. Deploys automatically on push to `main`.

## Pages
- `index.html` — homepage
- `the-place.html`
- `history.html`
- `fishing.html`
- `explore.html`
- `our-story.html`
- `itinerary.html`

## Photos & brand assets
- Property photos: hosted on OwnerRez's CDN (`uc.orez.io`) — upload via OwnerRez → Properties → Listing Content → Photos
- Brand assets (mascot, sign): upload via OwnerRez → Account → Files
- Don't embed new images as base64 in HTML — it happened before and roughly doubled page weight
