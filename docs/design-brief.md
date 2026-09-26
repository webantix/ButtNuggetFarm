# Butt Nugget Farm — website design brief (for Claude Design)

> Fill in every `[[ ]]` placeholder before sending. Delete this line.

## Who we are
Butt Nugget Farm is a small backyard poultry breeder in **Gidgegannup, in the Perth Hills, Western Australia** (about 40 minutes north-east of Perth). We sell **fertile hatching eggs** and **chicks**. We do **not** sell eggs for eating. All copy should describe our eggs as hatching eggs for incubation.

- Facebook: https://www.facebook.com/profile.php?id=61593547466551 (our main channel for updates and orders)
- Breeds we keep: [[list breeds, e.g. Australorp, Silkie, Pekin, Isa Brown]]
- Chick options: [[straight run / sexed / point of lay?]] at [[age range]]
- Prices: [[hatching eggs $ per half dozen / dozen; chicks $ each]]
- How people order: [[Facebook Messenger / phone / email]]
- Pickup: [[pickup only from Gidgegannup, or meet-ups / posting hatching eggs within WA?]]
- Logo / colours: [[attach the Facebook profile and cover images; list any brand colours]]

## Audience
- Backyard keepers and families in the Perth Hills and metro Perth
- Hobby breeders looking for specific breeds
- People with an incubator who want hatching eggs, including first-timers

Most visitors will come from a Facebook post on their phone. **Design mobile-first.**

## Tone
Playful, because the name is a joke and we're happy with that, but also clearly a well-run, trustworthy small farm. Warm, rural and hand-made. Not corporate, and not cutesy clip-art.

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
- Basic local SEO: title/description mentioning "hatching eggs", "chicks", "Gidgegannup", "Perth Hills", "Perth"; Open Graph tags so links look good when shared on Facebook; LocalBusiness schema.org markup.

## Deliverables I want from you
1. Two or three visual directions (colour palette, typography, a hero mock-up) to choose from.
2. Then the full page design in the chosen direction, at mobile and desktop widths.
3. Placeholder copy written in our tone, which we'll edit.
