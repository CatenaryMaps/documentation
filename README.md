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

- Keep code file under 500 lines, and attempt to move functions into their own files
- Do not wrap functions inside callbacks, keep them global. Otherwise, it leads to excess heap allocation and de-allocation.
- Use tailwind before writing using own CSS styles
- Split components up
