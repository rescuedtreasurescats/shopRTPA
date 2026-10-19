# Paws for a Cause — Rescued Treasures

The starting shop template for **shoprtpa.com**, featuring rescue apparel, cat-and-dog designs, and sweet treats. Products and ordering details will be added later.

## Current status

This is a collection preview. Ordering is not open. Keep GitHub Pages disabled until Sue approves publishing the template.

The existing design, wording, collection filters, FAQ sections, and image assets have been preserved from the confirmed template. Search engine indexing remains disabled while the shop is in preparation.

## Files

- `index.html`: the page, styles, collection filters, and FAQ content.
- `assets/rtpa-logo.png`: Rescued Treasures Pet Adoptions logo.
- `assets/rescue-pals-v1.png`: generated concept image of a cat and dog.
- `assets/rescue-cookies-v1.png`: generated concept image of cookies.
- `CNAME`: the intended GitHub Pages custom domain, `shoprtpa.com`.
- `.nojekyll`: serves the static files without Jekyll processing.

No build step, application server, database, or installation is required. The site uses Google Fonts with sans-serif fallbacks. All image assets are local to this repository.

## Adding products later

Replace concept cards and images with approved products, accurate descriptions, prices where appropriate, and verified ordering links. Update the ordering FAQ and coming-soon wording when ordering opens. Concept images are not photographs of RTPA animals or confirmed vendor inventory.

## Publishing later

The intended host is GitHub Pages, with DNS managed in Cloudflare. Publish from the selected repository branch and its root folder, set the Pages custom domain to `shoprtpa.com`, then enforce HTTPS after GitHub issues the certificate. The existing GitHub verification TXT record in Cloudflare must remain in place.

Do not commit credentials, banking or tax information, or internal volunteer data.
