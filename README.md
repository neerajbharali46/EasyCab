# EasyCab 🚖

A clean, responsive cab booking landing page built with vanilla HTML, CSS, and JavaScript. Designed for local cab services to establish an online presence and let customers quickly book rides.

---

## Overview

EasyCab is a static frontend project for a local cab service based in Jorhat, Assam. It provides a polished, single-page experience where users can view available services, submit ride booking interest, and get in touch — no frameworks, no build tools, just clean HTML and CSS.

---

## Features

- **Sticky navigation bar** with scroll-triggered shadow effect
- **Hero section** with pickup and drop location inputs
- **Services grid** showcasing City Rides, Airport Transfers, and Outstation Trips
- **About section** describing the service
- **Contact form** with name, email, and message fields
- **Responsive layout** for mobile and desktop
- **Smooth scroll** between sections

---

## Project Structure

```
EasyCab/
├── EasyCab.html        # Main HTML file
├── EasyCab.css         # All styles
└── README.md           # You are here
```

> The project also references `login.html` (linked via the "Book Now" button) and a cab image (`Gemini_Generated_Image_hgyr39hgyr39hgyr.png`) which are not included in the repository.

---

## Getting Started

No installation or build step needed. Just open the file in a browser:

```bash
# Clone the repo
git clone https://github.com/your-username/easycab.git
cd easycab

# Open directly in browser
open EasyCab.html
```

Or simply drag `EasyCab.html` into any browser window.

---

## Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure and semantics |
| CSS3 | Layout, animations, responsive design |
| Vanilla JavaScript | Scroll effects, navbar behavior, page navigation |
| Google Fonts | Playfair Display, Lato |

---

## Customization

**Colors** — The brand palette is defined inline in the CSS. The two main values to change are:

- `#c25a2d` — Primary rust/orange accent
- `#FAF0CA` — Background cream

**Location** — Update the hardcoded location text in `EasyCab.html`:
```html
<p id="usr-location">Jorhat, IN <a href="location.html">Baruah Chariali</a></p>
```

**Services** — Each service card lives inside `#services-section` and can be edited independently. The card backgrounds are CSS gradients set via `.service-card:nth-child(n)`.

---

## Roadmap

- [ ] Connect pickup/drop inputs to a maps API (Google Maps or OpenStreetMap)
- [ ] Build out `login.html` and the booking flow
- [ ] Add real-time driver tracking
- [ ] Backend integration for the contact form
- [ ] Mobile hamburger menu for small screens

---

## Author

Made by **Neeraj Bharali** — Jorhat, Assam.

---

## License

This project is for personal/portfolio use. Feel free to fork and adapt for your own local business.
