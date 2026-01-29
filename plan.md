# Startpage Enhancement Plan

## Goals
- Improve usability, readability, and organization without introducing external files or new technologies.
- Keep everything within a single HTML file using only HTML + CSS (and any existing inline JS).

## Feature TODOs (HTML/CSS-only)
- [ ] Add a fixed quick-jump navigation bar (anchor links) to each section for faster scanning.
- [ ] Introduce a compact, inline search box that filters visible links by text match (style-only placeholder if no JS changes desired).
- [ ] Add a “Today” card with a simple layout for date, day, and a short focus note area.
- [ ] Create a “Top 5” favorites block at the top for the most-used links.
- [ ] Group columns into collapsible sections using `<details>` / `<summary>` for decluttering.
- [ ] Add section icons (emoji or SVG data URIs) to make categories more recognizable at a glance.
- [ ] Provide a subtle grid background pattern via CSS for a paper-like texture.
- [ ] Add visual separators (rules) between column groups to reduce visual noise.
- [ ] Improve link hierarchy with typography (bold for primary, lighter for secondary/rare).
- [ ] Add hover focus styles for keyboard navigation (visible focus rings on links/buttons).
- [ ] Make the layout responsive with a single-column stacking strategy for narrow screens.
- [ ] Add a compact “Notes” panel for quick reminders or short text snippets.
- [ ] Introduce a monochrome badge system for link labels (e.g., “daily”, “weekly”).
- [ ] Add a “Recently Used” placeholder section for manual curation of current focus links.
- [ ] Add a “Reading Queue” list with numbered items for priority articles.
- [ ] Add a subtle footer with version/date updated and a short tip.
- [ ] Use CSS custom properties to allow easy theme tweaks (accent color, spacing).
- [ ] Add print-friendly styling so the page can be printed cleanly.
- [ ] Include a simple grid-based layout option (CSS class) to toggle between list and grid.
- [ ] Provide a theme contrast helper (bolder borders or heavier text) for readability.
