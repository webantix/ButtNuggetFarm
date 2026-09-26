# Butt Nugget Farm — website design brief (for Claude Design)

> Fill in every `[[ ]]` placeholder before sending. Delete this line.

## Who we are
Butt Nugget Farm is a small backyard poultry breeder in **Gidgegannup, in the Perth Hills, Western Australia** (about 40 minutes north-east of Perth). We sell **fertile hatching eggs** and **chicks**. We do **not** sell eggs for eating. All copy should describe our eggs as hatching eggs for incubation.

- Website domain: **buttnuggetfarm.com** (singular. Note that buttnuggetfarms.com is an unrelated US farm.)
- Facebook: https://www.facebook.com/profile.php?id=61593547466551 (our main channel for updates and orders)
- Breeds we keep: [[list breeds, e.g. Australorp, Silkie, Pekin, Isa Brown]]
- Chick options: [[straight run / sexed / point of lay?]] at [[age range]]
- Prices: [[hatching eggs $ per half dozen / dozen; chicks $ each]]
- How people order: [[Facebook Messenger / phone / email]]
- Pickup: [[pickup only from Gidgegannup, or meet-ups / posting hatching eggs within WA?]]
- Logo and cover art: **attach both images from the Facebook page**. Brand details are in the Visual identity section below.

## Audience
- Backyard keepers and families in the Perth Hills and metro Perth
- Hobby breeders looking for specific breeds
- People with an incubator who want hatching eggs, including first-timers

Most visitors will come from a Facebook post on their phone. **Design mobile-first.**

## Visual identity (already set, so match it and don't reinvent it)
Our Facebook branding is a **knitted / crocheted wool diorama**. Everything looks hand-knitted: a cream farmhouse with a pastel pink-and-blue tiled roof, a timber chook house, rolling sage-green knitted hills, gum trees, rose, daisy and lavender borders, and yarn chickens (white, black-and-white barred, and red/brown roosters). The farm name sits on a knitted ribbon banner in dusty brown/pink with "Gidgegannup, WA" underneath. The logo is a round badge showing a hen on a nest of eggs, ringed with knitted flowers.

Approximate palette taken from the artwork (refine these against the attached images):
| Role | Colour | Approx. hex |
|---|---|---|
| Background | Oatmeal / cream wool | `#F3ECE0` |
| Primary accent | Dusty rose | `#D48A93` |
| Deep accent / buttons | Rose-brown (banner text) | `#8E4F4A` |
| Secondary | Powder blue | `#A9C4DE` |
| Nature | Sage green | `#A7B98A` |
| Highlight | Lavender | `#A893C8` |
| Text | Warm brown | `#5B3E31` |

Design direction:
- Carry the knitted, handmade feel into the website: soft rounded shapes, subtle knit/stitch textures or stitched borders, ribbon-banner headings, and flower corner accents. Keep it tasteful, and make sure text always sits on a clean, readable surface rather than on busy texture.
- Use the cover image as the hero. It has text baked in and is very wide, so plan how it crops on mobile. Either use the logo badge plus a cropped scene on phones, or ask us for a text-free version.
- Pick a friendly rounded display font for headings that echoes the chunky banner lettering, and a plain, highly readable body font.
- Keep the Facebook blue out of the palette except on the "Message us" button itself.

## Tone
Cosy, cute and handmade to match the artwork, with a bit of humour from the name, but also clearly a well-run, trustworthy small farm that knows its birds. Warm and rural, not corporate.

## Pages / sections
Keep it small. A single long page with anchor navigation is fine.

1. **Hero**: farm name, one-line pitch ("Hatching eggs & chicks from the Perth Hills"), a photo, and two buttons: "See what's available" and "Message us on Facebook".
2. **Available now**: a simple list or cards showing each breed with a photo, what's available (hatching eggs / chicks), price, and a status badge (Available / Coming soon / Sold out). **This must be easy for a non-developer to update**: drive it from one small data file (JSON or similar), not hard-coded HTML.
3. **Our breeds**: short description of each breed (temperament, egg colour, good for beginners?).
4. **How to order & pickup**: step-by-step instructions (message us → confirm → pick up in Gidgegannup), payment methods [[cash / PayID]], and a note that the exact address is given on confirmation.
5. **Hatching tips / FAQ**: storing eggs before setting, incubation time (21 days), what "straight run" means, no guaranteed hatch rates, and how to care for chicks in the first weeks.
6. **About us**: short story of the farm, with family and farm photos.
7. **Footer**: Facebook link, contact, "Gidgegannup, WA", and © year.

## Functional requirements
- Static site with no backend, deployable free on GitHub Pages or Netlify (the repo is `webantix/ButtNuggetFarm`).
- Enquiry form optional; if included, use a no-backend service (e.g. Formspree/Netlify Forms) or just deep-link to Facebook Messenger.
- Fast on rural mobile connections: compressed images, no heavy frameworks.
- Accessible: good contrast, alt text, readable font sizes.
- Australian English throughout (colour, chook, favourite), AUD prices, `lang="en-AU"`.
- Local SEO matters more than usual, because several US farms share our name. Every page title and the hero should say "Gidgegannup" / "Perth Hills, WA" so that we are clearly the Australian one.
- Basic local SEO: title/description mentioning "hatching eggs", "chicks", "Gidgegannup", "Perth Hills", "Perth"; Open Graph tags so links look good when shared on Facebook; LocalBusiness schema.org markup.

## Deliverables I want from you
1. Two or three visual directions (colour palette, typography, a hero mock-up) to choose from.
2. Then the full page design in the chosen direction, at mobile and desktop widths.
3. Placeholder copy written in our tone, which we'll edit.
