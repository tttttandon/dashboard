# dashboard

# Tandon Champion — Fort Worth Dashboard

A weather dashboard built from scratch in HTML, CSS, and JavaScript for
WRIT 40363. It loads weather data from a JSON file with fetch() and has a
dark-mode toggle that remembers the reader's choice.

**Live site:** https://username.github.io/dashboard

## Built with

- Semantic HTML5
- CSS with design tokens (custom properties), including a dark theme
- JavaScript: fetch() with .then()/.catch(), and localStorage
- Git and GitHub Pages

## Notes

The weather values in `data/weather.json` are sample data I typed, not a
live report, so they do not reflect today's conditions. If the data file
fails to load, the widget shows a plain message instead of going blank.
The theme choice is saved in the reader's own browser with localStorage.