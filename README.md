# Gateway X website

- `index.html` — the Gateway X website: who it's for, what we bring, how it works, ways to work together, results, events, FAQ, and a working "Bring your idea" application form.
- `presentation.html` — the MGMT 7640 Block Week team presentation and Herd OS demo (used for the video).

**Go live:** Settings → Pages → Deploy from branch `main`, folder `/(root)`. Site: https://wonshon-cmd.github.io/gatewayx/

**Logo:** upload the Gateway X logo as `logo.png` in this folder; it replaces the text logo automatically on both pages.

**Forms:** the application and "Notify me" forms send through FormSubmit to the address in `FORM_ENDPOINT` (near the bottom of `index.html`). The first submission triggers a one-time activation email to that address.

**Before launch, Gateway X should confirm:** event names and schedule, the work-together options (service package, network partner, success fee), milestone-based capital, and the promises in the FAQ. Results use public, founder-reported figures only.

**Booking and events (in `index.html`, near the bottom):**
- `SESSIONS`: the sessions offered at the end of "Bring your idea" (free and paid). Paste a Calendly or similar link into `bookingUrl` to send people there instead of the built-in time picker.
- `ZOOM_LINK`: paste the real Zoom link and it appears after someone signs up for an online event. Left empty, the site says the link is coming by email.
- `CAMPUSES` and `TOUR`: sample venues for in-person events. Replace them with confirmed locations.

**Company logos:** upload `aux-insights-logo.png` and `growthassistant-logo.png` to this folder and they replace the AUX / GA badges in Results automatically.
