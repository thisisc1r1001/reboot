# ReBoot: Give old tech a second life

Built by **Aaditya** for **BrandIT 3.0** (IEEE WIE MUJ) · Domain 08: Community & Social Impact

**Live site:** https://YOUR-SITE.netlify.app

## The problem

Many students cannot afford a working laptop or phone, while plenty of working devices sit unused in drawers or end up as e-waste. Existing e-waste drives collect old tech, but few repair it and hand it back to a student who needs it.

## The solution

ReBoot connects the two sides:

1. **Donate:** a donor pledges a device.
2. **Wipe:** volunteers erase all personal data.
3. **Refurbish:** the device is repaired, updated and tested.
4. **Hand over:** a student who requested a device receives it.

## Features

- Landing page with an animated boot sequence
- "I have a device" donate form and "I need a device" request form
- Live pledge counter and recent pledges board
- FAQ section
- Responsive layout, keyboard focus states, and reduced-motion support
- Honeypot spam protection on forms

## Tech stack

- HTML5, CSS3 and vanilla JavaScript (single file, no build step)
- Netlify for hosting and Netlify Forms for submissions
- Browser `localStorage` for the demo pledge board
- Google Fonts: Bricolage Grotesque and IBM Plex Sans

## Run it locally

No installation is needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/reboot.git
   cd reboot
   ```
2. Open `index.html` in any modern browser.

Optional: serve it locally with
```bash
npx serve .
```

## Deploy

**Netlify:** drag the project folder onto https://app.netlify.com/drop, or import the repo from GitHub (leave the build command empty and set the publish directory to `.`).

**Vercel:** import the repo and click Deploy. Forms will display, but Vercel has no built-in form storage.

## Notes and limitations

- The pledge board and counter read from the visitor's own browser storage, so they are demo data and are not shared between visitors.
- Real form submissions are collected only when deployed on Netlify (see the Forms tab in the dashboard).

## Future scope

Shared database for pledges, volunteer portal, device matching and status tracking, and partnerships with colleges, NGOs and local repair shops.

## Author

Aaditya, solo participant, BrandIT 3.0
