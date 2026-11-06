# K Explore – Event Management Website

A responsive event management website where users can explore upcoming events, view details, and register. Built for the **K Explore – Web Designing** task using plain **HTML5, CSS3 and JavaScript** (no frameworks).

**Live site:** `<paste your deployed link>`
**Repository:** `<paste your GitHub link>`

## Features

- Hero section with animated gradient and live stats
- Event cards (name, date, venue, image, short description, category tag)
- Search by name/venue/description, category filter chips, and sorting
- Event detail modal with full description and a live countdown timer
- Registration form (name, email, phone, selected event) with JavaScript validation
- Confirmation message with a unique reference ID after submit
- Duplicate-registration check (same email + same event)
- "My Registrations" panel with cancel option
- **Bonus:** dark/light mode (remembers choice), countdown timers, animations, Local Storage registration management
- Fully responsive for mobile, tablet and desktop (CSS Grid, flexbox, media queries)

## Validation rules

| Field | Rule |
|-------|------|
| Name | Required, letters/spaces/.'- only, 2–50 characters |
| Email | Required, must match a standard email pattern |
| Phone | Required, valid 10-digit Indian mobile number (starts 6–9, optional +91) |

## Implementation notes

- **HTML:** semantic structure (`header`, `main`, `section`, `article`, `footer`), labelled form fields.
- **CSS:** CSS variables drive the light/dark themes; Grid `auto-fill` makes the card layout responsive; keyframe animations and transitions for hover/entry effects.
- **JavaScript:** events are stored in an array and rendered dynamically; filtering, search and sorting run on every input; `localStorage` stores theme and registrations; user input is escaped before being inserted into the page.

## Run locally

Open `index.html` in a browser. No build step needed.

## Deploy

- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root.
- **Netlify / Vercel:** import the repo, no build command, publish directory is the root.

## Author

Dev Kumar Meher
