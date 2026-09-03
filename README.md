# LOOK UP

LOOK UP helps people answer a simple question:

> Can I see the next rocket launch from where I am?

## Current features
- Live upcoming launch data
- Browser geolocation
- Launch-pad distance and bearing
- Daylight/twilight estimation
- Ranked watchlist of upcoming launches
- Coarse Likely / Possible / Unlikely viewing assessment

## Important limitation
Current visibility rankings are based on launch-site distance and local solar altitude.
They do **not** yet include mission-specific ascent trajectory, weather, terrain, or cloud cover.

## Deployment
This repository is configured for Netlify as a static site.

Build command: none  
Publish directory: `.`

## Roadmap
1. Trajectory-aware predictions
2. Weather/cloud integration
3. Real previous-sighting photo galleries
4. Saved locations and launch alerts
5. Custom domain
