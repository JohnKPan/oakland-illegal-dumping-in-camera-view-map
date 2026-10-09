# Oakland illegal dumping vs. ALPR cameras

**Map:** https://johnkpan.github.io/oakland-illegal-dumping-in-camera-view-map/

An interactive map of illegal-dumping reports filed in Oakland, California over the last 60 days,
drawn against the automated license plate reader (ALPR) cameras mapped on OpenStreetMap. It shows
which dump sites fall inside a camera's field of view, which are near one, and which reports say
the reporter saw the person dumping.

The page is a single self-contained file (`index.html`). It is rebuilt from the latest data and
replaced here from time to time; the code that builds it lives in a separate repository.

## Reading it

- Report times are when a ticket was filed, not when the dumping happened.
- Camera positions and directions are crowd-sourced on OpenStreetMap (the data DeFlock maps).
  Field of view and range are not recorded, so they are sliders on the page. Flock's spec sheet
  gives its Falcon camera about 15 ft of width at 65 ft (roughly 13° and 20 m); the page defaults
  are wider.
- 311 locations are often snapped to an intersection or an address. Where a SeeClickFix report
  exists, the map uses the reporter's pin instead.

## Sources

- [Oakland 311 service requests](https://data.oaklandca.gov/Infrastructure/Service-requests-received-by-the-Oakland-Call-Cent/quth-gb8e) (City of Oakland open data)
- [SeeClickFix](https://seeclickfix.com/oakland) reports, the system behind OAK 311
- ALPR cameras, streets, shoreline and water from [OpenStreetMap](https://www.openstreetmap.org/copyright)
- City limits from [US Census TIGERweb](https://tigerweb.geo.census.gov/)

## Licence

- SeeClickFix report content is licensed [CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/).
  This map is shared under the same licence: credit the sources, non-commercial use only, and
  share adaptations under the same terms.
- Camera and street data © OpenStreetMap contributors, available under the
  [Open Database Licence (ODbL)](https://opendatacommons.org/licenses/odbl/).
