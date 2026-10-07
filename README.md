# fresher.club

Static landing page. Plain HTML, CSS and a little JavaScript. No build step, no tracking, no external fonts.

## Deploy on GitHub Pages
1. Push these files to the `main` branch of a new repository.
2. Settings > Pages > Deploy from a branch > `main`, folder `/ (root)`. The `CNAME` file already holds `fresher.club`.
3. At your registrar add four A records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153, and a CNAME for `www` pointing to `YOUR-GITHUB-USERNAME.github.io`. Optional AAAA records: 2606:50c0:8000::153 to 2606:50c0:8003::153. Check GitHub's current Pages docs.
4. When the certificate is issued, tick Enforce HTTPS.

## Make the waitlist real
Create hello@fresher.club (Google Workspace, Zoho Mail free tier or Cloudflare Email Routing) and add the MX records. The forms post to FormSubmit. Submit one test entry and click the activation link it emails you. Until then, or if the request fails, the page opens a pre-filled email instead.

## Verify before you pitch
- Check every statistic against its primary source: AISHE 2021-22, India Skills Report 2025 (a test of volunteers), PLFS youth unemployment (~15%, from press coverage; check the MoSPI bulletin), TCS FY27 hiring (Moneycontrol), Stanford 19% (US data, descriptive not causal).
- Market figures (Ken Research, GI Reports Hub, Tracxn) are research-firm estimates with differing scope.
- The business model, comparison table, roadmap, 90-day plan, scorecard and sample skill profile are drafted assumptions or illustrations. Edit them to match your real plan, and add no testimonials, logos or traction until they are real.
- Have a lawyer review the commitments and the data line, and add privacy and terms pages before collecting data at scale.

## Editing
All copy and styles live in `index.html`. Colours are CSS variables at the top of the stylesheet.
