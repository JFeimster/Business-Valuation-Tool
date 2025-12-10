# Empire Valuation Landing Page

A high-converting, "Gold Standard" landing page for the Empire Flippers Valuation Tool.

## The Vibe
- **Style:** "FinTech Prestige"
- **Colors:** Charcoal (#121212), Matte Black (#1E1E1E), and Empire Gold (#C5A059).
- **Font:** Playfair Display (Headings) + Inter (UI).

## Deployment Instructions
1. **Drag & Drop:** Simply drag this entire folder into [Netlify Drop](https://app.netlify.com/drop) or upload to Vercel.
2. **API Key:** The code is pre-configured with your specific API Key: `vCjGK41...`.
3. **Referral Link:** All CTA buttons link to your specific referral URL: `https://empireflippers.com/?referrer=6I8WK4WSMYC9KGJD`.

## Technical Note on CORS
If you run this locally (`file://`) or on certain strict domains, the Empire Flippers API might block the request due to **CORS (Cross-Origin Resource Sharing)** policy.
- **My Solution:** I included a smart "fallback calculator" in `script.js`. If the real API request is blocked by the browser, the site **automatically** falls back to a 32x profit multiple calculation so the user still gets a result and isn't stuck staring at a loading spinner. The UI remains seamless.

## Customization
- To change the background glow, edit the `bg-efGold/20` class in `index.html`.
- To add more monetization types, add `<option>` tags to the select menu in `index.html`.
