# The Royal Jail Restro

Single-page restaurant website. Static HTML, CSS and JavaScript only, with no build step.

## Edit content
Open `index.html` and find the `SITE` object near the bottom of the file. Name, address, phone, hours, menu and prices, gallery and map links are all in there.
Replace or add photos in `/images` and update the paths in `SITE.gallery` and the `IMG` object.

## Deploy
Import this repository in Vercel. Framework preset: **Other**, no build command, output directory blank.

## Notes
- `const ONCE=false` in the gate script: set to `true` to show the jail-gate intro once per visit.
- Reservation form opens WhatsApp with a pre-filled message.
