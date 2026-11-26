# spoaxio.in — Spoaxio Software website

Single-page static site (HTML/CSS/JS, no build step), hosted on GitHub Pages at https://spoaxio.in

## Edit quickly (all in `index.html`)
- **Contact details & keys** — the `SITE` object near the top of `<body>` (phone, WhatsApp, email, CallMeBot key).
- **Services / packages** — the `SERVICES` array in the script at the bottom.
- **Projects** — the `PROJECTS` array; screenshots live in `assets/projects/` (960×600 jpg).
- **WhatsApp chat quick messages** — the `WA_QUICK` array.

## Enquiry form → WhatsApp
1. Save the CallMeBot number in your phone (see callmebot.com for the current number) and send it: `I allow callmebot to send me messages`
2. Paste the API key you receive into `SITE.callmebotKey`.
Without a key, the form opens WhatsApp with the enquiry pre-filled. An email copy goes to `SITE.formEmail` via FormSubmit (confirm their activation email once).

## Domain
`CNAME` contains `spoaxio.in`. DNS at the registrar:
- A records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- CNAME for `www`: alwitiri.github.io
