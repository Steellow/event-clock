# Yearly Events - Project Instructions

## Critical Rules

- **NEVER change the localStorage key** (`yearly-events-v3`). Changing it will wipe user data. If a migration is needed, keep the old key reading for backwards compatibility and write to the same key.
- The app is a single `index.html` file with no build step. Keep it that way.
- Never open the page in the browser after making changes — the user already has it open.

## Architecture

- Single HTML file with embedded CSS and JS
- SVG-based clock visualization on the left, panel (form + list) on the right
- Events stored in localStorage as `{events, nextId, colorIdx}`
- Date format: `dd.mm` (dot = day first) or `mm/dd` (slash = month first)
- Colors auto-assign from a 10-color palette, changeable via popover on list items