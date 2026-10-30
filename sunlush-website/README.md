# Sunlush Investment website

One-page site for Sunlush Investment Company Limited, hosted free on GitHub Pages.

- `index.html`: the whole page (English + Kiswahili switch)
- ``: logo, forum photos, icons

## Edit contact details
Open `index.html`, find `const CONTACT = {` near the top, and fill in phone, WhatsApp, email.
Empty values are hidden on the page.

## Custom domain (e.g. sunlush.co.tz)
GitHub: Settings > Pages > Custom domain.
At the domain registrar, add DNS records:
- A  @  185.199.108.153
- A  @  185.199.109.153
- A  @  185.199.110.153
- A  @  185.199.111.153
- CNAME  www  <your-github-username>.github.io
Then tick "Enforce HTTPS".
