# OHP Hammer Time — ohp hammer time syndicate llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `ohphammertimesyndicatellc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/ohphammertimesyndicatellc.mjs`).
> To change the content, edit that file and run `node build.mjs ohphammertimesyndicatellc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@ohphammertimesyndicatellc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Renovation / $Trades / $Not an offer) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
OHP Hammer Time Syndicate LLC, a Florida limited liability company (document number L22000249905), renovates residential property: assessing properties and establishing what the work genuinely costs before anything is committed, managing renovation through appropriately licensed trades with permits pulled where required, documenting the work and certification so it transfers with the property, and returning finished homes to the market. This website describes what the company does. It is informational only and is not an offer to sell, or a solicitation of an offer to buy, any security, membership interest or investment of any kind. Site: ohphammertimesyndicatellc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
