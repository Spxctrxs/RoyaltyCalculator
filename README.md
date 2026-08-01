# RoyaltyCalculator

Basic Music Royalties Calculator (Distribution only)

## Overview
RoyaltyCalculator is a single-page web app for estimating music royalty earnings across major streaming platforms. It is designed for quick, visual planning rather than legal, accounting, or contract-level payout calculations.

The project is implemented as a self-contained HTML file with embedded CSS and JavaScript. It includes a polished dark UI, dynamic pricing inputs, regional multipliers, charting, and exportable royalty statement cards.

## What the app does
- Calculates estimated gross and net earnings based on stream counts and per-stream payout rates
- Supports two modes:
  - Per platform input mode
  - Total streams mode
- Applies regional multiplier adjustments for:
  - Global
  - North America
  - Europe / UK
  - Latin America
  - Asia-Pacific
  - Africa & MENA
- Includes an optional label fee deduction of 25%
- Displays an earnings breakdown chart
- Generates a downloadable statement card as a PNG image
- Shows a scrolling ticker of platform rates for quick reference

## Included platforms
The calculator currently includes estimated rates for the following platforms:
- Spotify
- Apple Music
- Amazon Music
- YouTube Music
- TikTok
- Tidal
- Deezer
- SoundCloud
- Pandora
- iHeartRadio
- Anghami

> Note: The payout rates are illustrative estimates for distribution planning and can vary by contract, territory, and distributor terms.

## Project structure
- [RC.html](RC.html) — the full application UI, styling, and JavaScript logic
- [README.md](README.md) — project overview and usage notes
- [LICENSE](LICENSE) — custom attribution-based license for reuse and redistribution

## How to use
1. Open [RC.html](RC.html) in a web browser.
2. Enter the track title and artist name.
3. Choose a region from the dropdown.
4. Switch between per-platform or total-streams mode.
5. Enter stream counts and review the estimated gross/net earnings.
6. Use the export button to download the statement card as an image.

## Tech stack
- HTML5
- CSS3
- JavaScript
- Tailwind CSS (via CDN)
- Chart.js
- Font Awesome
- html2canvas

## Notes
- This project is intended for educational and planning use.
- It does not connect to real royalty databases or distributor APIs.
- All figures should be treated as estimates only.

## Future ideas
Possible enhancements include:
- Adding more platforms and payout models
- Supporting custom user-defined rates
- Saving calculations locally
- Exporting reports as CSV or PDF
- Adding a backend for persistent project history
