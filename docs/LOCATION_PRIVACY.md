# LOCATION_PRIVACY.md

The Veterans Hub requests browser geolocation only after the user presses **Use My Location**.

- No request occurs on page load.
- Coordinates stay in JavaScript memory for the current tab.
- Coordinates are not written to localStorage.
- Coordinates are not sent to Verve N Veda.
- The page does not call a reverse-geocoding API.
- A manual city/state/ZIP option is available.
- Nearby links are outbound map searches plus authoritative national locators.
- Closing or clearing the page removes the in-memory coordinates.

Provider hours, eligibility and availability must be verified before travel.
