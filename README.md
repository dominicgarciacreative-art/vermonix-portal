# Vermonix — wholesale partner desk

A single-page dashboard for a fictional perfume house's wholesale business:
channel revenue, partner sell-through, a map of Philippine retail partners,
stock cover, and price-floor compliance cases.

**Everything in it is invented.** No real company, partner, person or figure.

- Open to anyone with the link. Pick any partner from the *View* menu to see
  the dashboard that partner would get.
- An admin code unlocks compliance cases and adding partners. The check runs
  in the page, so it is a latch, not a lock — there is no server here and
  nothing in this repo is confidential.
- No build step, no dependencies to install. `index.html` is the whole thing;
  Chart.js loads from a CDN and the map is drawn from coastline data inlined
  in the page, so there are no map tiles to fetch.

Figures are in Philippine pesos.
