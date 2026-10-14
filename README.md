# E-wedding-Invitation
A cinematic single-page wedding invitation with opening doors, falling petals, a live countdown and background music. Pure HTML, CSS and JavaScript.
# 💍 Lady & Lord: Wedding Invitation

A cinematic, single-page digital wedding invitation for **15th June 2027**, built with plain HTML, CSS and JavaScript. No frameworks, no build step, no dependencies.

🔗 **Live site:** https://your-site-name.netlify.app

## Highlights

- **Opening-doors entrance:** a pair of burgundy-and-gold reception hall doors swing open in 3D (CSS `perspective` and `rotateY`) with a light burst, revealing the invitation.
- **Falling rose petals:** 22 randomized petals, each with its own size, speed and delay, generated with JavaScript.
- **Live countdown:** days, hours, minutes and seconds to the ceremony, updating every second.
- **Scroll-reveal sections:** content fades in as you scroll, using the `IntersectionObserver` API.
- **Background music:** a toggle button with an animated equalizer; playback stops automatically after 60 seconds.
- **Quranic prayer section:** Arabic calligraphy (Amiri) with right-to-left text handling and an English translation.
- **Venue section:** with a one-tap link to Google Maps.
- **RSVP form:** name, contact, attendance and a note for the couple.
- **Hand-drawn SVG decoration:** chandelier, floral corners, monogram wreath and arch frame, all inline SVG.
- **Accessible motion:** respects `prefers-reduced-motion`.
- **Responsive:** fluid typography with `clamp()`, built to work from phones to desktops.

## Design

| | |
|---|---|
| **Palette** | Ivory, burgundy, rose, sage and gold |
| **Fonts** | Cormorant Garamond, Playfair Display, Parisienne, Amiri (Google Fonts) |

## Project structure

```
├── index.html
└── audio/
    └── joel-sunny-luminary.mp3
```

All styles and scripts live inside `index.html`.

## Run locally

1. Clone the repo:
   `git clone https://github.com/your-username/your-repo-name.git`
2. Open `index.html` in your browser.

## Customize

- **Names and monogram:** edit the `<h1 class="names">`, the `.monogram` text and the door crest.
- **Date and countdown:** change the date in the page and the `target` value in the script.
- **Venue and map link:** update the venue name and the Google Maps URL.
- **Music:** replace the file in `audio/` and update the `<source>` path.

## Deployment

Hosted on [Netlify](https://www.netlify.com/).

## Credits

Designed and developed by Zay.
Music: "Luminary" by Joel Sunny. Fonts: Google Fonts.

## License

© 2026 Zay. All rights reserved.
