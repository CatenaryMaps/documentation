## How development should occur / guidelines

### Testing of features

Testing of features should happen in multiple areas. Currently recommended are:
- New York City MTA
- Los Angeles Metro Area
- San Diego
- Calgary
- Vancouver
- Toronto
- San Francisco Bay Area
- Banff, Alberta, Canada
- Montreal
- Paris
- London
- Tokyo

### Code Guidelines
- Attempt to keep data loaded into mapbox layer as minimal as possible, do other feature augmentation outside the mapbox context.

  Example: Keep a translation to miles per hour or km/h in the svelte data window, not in mapbox.
