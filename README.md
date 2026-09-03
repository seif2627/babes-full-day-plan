# Babes Full Day Plan

Phone-first itinerary for Thursday, September 3, 2026.

## Live site

GitHub Pages publishes the `main` branch at:

- https://seif2627.github.io/babes-full-day-plan/

## Design

This project deliberately preserves the visual language of the original ChatGPT Site:

- navy `#101c2c`
- paper `#f7f4ec`
- lime `#cffa62`
- coral `#ff725e`
- sky `#87d7ff`
- oversized hero typography
- sticky two-plan selector
- colour-coded movement timeline
- rounded cards and receipt-style budget sections

## Current itinerary rules

- Two plans only, both meeting at 10:00 a.m.
- No scheduled breakfast.
- Square One is a 20-minute washroom / water / coffee stop.
- Mini Indy: 3 Thursday-discount laps per person.
- Plan A: hidden spots, waterfront sunset, PATH, late snack/chill, late GO 29 from Kipling.
- Plan B: Odyssey IMAX, then the 10:34 p.m. train from Union.
- The route section has two locally stored OpenStreetMap basemap images with locally generated SVG route overlays, plus a swipeable stop strip. It downloads no map tiles at runtime, so it cannot fail into a giant blank/world map.
- Walking legs use Google Maps. Time-sensitive GO/TTC legs link to the operator planner with the planned departure visibly printed on the site, because Google Maps universal URLs cannot reliably encode a future transit departure time.

## Offline use

The page registers a small service worker and caches the core site assets after the first successful visit. Open the site once while online before leaving.

## Verification snapshot

Research was rechecked early September 3, 2026 against active pre-September-5 schedules and current operating pages. Live boards and same-day operations always override the static plan.

Key sources:

- GO schedules: https://www.gotransit.com/en/see-schedules/pdf-schedules
- GO live schedules: https://www.gotransit.com/en/see-schedules
- TTC advisories: https://www.ttc.ca/service-advisories
- Environment Canada Toronto: https://weather.gc.ca/en/location/index.html?coords=43.643%2C-79.378
- Mississauga Mini Indy: https://mississaugaminiindy.ca/prices-and-packages
- Museum of Toronto: https://museumoftoronto.com/visit-us/
- 401 Richmond: https://401richmond.com/visit/
- The Well: https://thewelltoronto.com/directory/
- Toronto PATH: https://www.toronto.ca/explore-enjoy/visitor-toronto/path-torontos-downtown-pedestrian-walkway/
- Longo's Maple Leaf Square: https://www.longos.com/store-details/Longos%20Maple%20Leaf%20Square
- Cineplex Scotiabank Theatre Toronto: https://www.cineplex.com/theatre/scotiabank-theatre-toronto

## Notes

Prices are CAD. Restaurant prices use current online-menu benchmarks and can differ from dine-in pricing. Tipping is optional and is not included in the site budget. No private payment/credit-score note is stored in this public repository.
