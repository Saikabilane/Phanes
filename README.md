# Phanes — Nearby Hospital Locator

Phanes is a lightweight, browser-based hospital locator that uses the device's location and an interactive map to help users identify nearby healthcare facilities. The interface presents the nearest location along with available address and phone details when returned by the underlying lookup.

## Features
- Requests the user's location through the browser Geolocation API.
- Displays the current position on a Leaflet map using OpenStreetMap tiles.
- Uses map/routing libraries to support location and route visualization.
- Shows a compact information panel for the selected nearby facility.
- Responsive HTML/CSS interface with a dedicated Phanes logo.

## Project files
- `index.htm` — page structure, map setup, geolocation flow and interface logic.
- `style.css` — page and map styling.
- `phanesLogo.png`, `locator.png` — visual assets.

## Run locally
1. Clone this repository.
2. Open `index.htm` in a browser, or serve the folder with a local static web server.
3. Allow location access when prompted.

A secure context (HTTPS or localhost) is generally required for browser geolocation. The page loads Leaflet, Leaflet Routing Machine, Google Places and fonts from external services, so an internet connection is required. If Google Places functionality is used, configure a valid Google Maps Platform API key and restrict it appropriately.

## Notes
Location accuracy and the availability of nearby facilities depend on the device, browser permissions, and the services/data used by the page. This project is a locator aid, not an emergency-response service. In an emergency, contact local emergency services directly.

## License
No license file is currently included. Ask the repository owner before reusing or redistributing the code or assets.
