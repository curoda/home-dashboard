# Home Dashboard

A single-page, self-hosted web dashboard that shows **weather, calendar events, a shopping list, and an hourly forecast** – perfect for a wall-mounted tablet or Raspberry Pi display. The entire app is front-end (HTML + CSS + JS); no server or build step required.

---

![Screenshot](sun%20favicon1.png)

---

## Quick Start

```bash
# 1 · Clone or download
git clone https://github.com/curoda/home-dashboard.git
cd home-dashboard

# 2 · Open the file
#    Double-click index.html, or serve it from any static host.

# 3 · Configure (click the ⚙ gear icon)
#    • Location (or enable “Use browser location”)
#    • OpenWeatherMap API key
#    • Optional iCal URLs for calendars
#    • Optional Todoist token for the shopping-list widget
#    • Dark-mode hours & refresh intervals
```
Settings are saved to `localStorage`, so they persist across reloads.

## Features

- Live current weather & “feels like” temperature (OpenWeatherMap)
- Five-day hourly forecast
- Multiple calendar feeds (iCal links or Google Calendar)
- Shopping list pulled from **Todoist**
- Dark-mode schedule & kiosk-mode toggle
- Entirely client-side – drop it on any static host

## Customising

Open `index.html` in your editor:

- **Styling** – tweak utility classes or add custom CSS.
- **Widgets** – copy a `.widget` `<section>` block and wire up a new data source.
