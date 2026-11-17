# Campus Events — static UI prototype

A responsive front-end concept for discovering university events. Built with **HTML, CSS, and vanilla JavaScript**.

> **Status:** Front-end prototype with sample event content. It is **not** a deployed campus event management system or a REST API.

## What works

- Browse a set of example event cards.
- Search event names with text input.
- Filter cards by the provided category selector.
- Click an RSVP button to change its on-page state and display a confirmation message.

## Run locally

Open `index.html` in a browser, or serve the folder with a static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Repository layout

- `index.html` — sample cards, navigation, and page markup
- `styles.css` — page styling and responsive layouts
- `script.js` — text/category filtering and local RSVP UI behavior

## Known limitations

There is **no backend, database, authentication, event creation API, persistent RSVP record, or email delivery** in this repository. The RSVP confirmation is illustrative only; it does not send email. Displayed event counts and listings are sample content. Some visual controls are mockups rather than complete workflows.

A production implementation would need an event API, authenticated organizations, persistent RSVP state, accessibility verification, and reliable event data.
