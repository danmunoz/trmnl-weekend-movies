# Weekend Movie Picker

![Weekend Movie Picker screenshot](docs/trmnl-wknd-mv.png)

TRMNL plugin for showing a simple set of weekend theatrical movie picks by region.

It highlights one primary weekend pick plus alternate theatrical releases using TMDB data.

## Configuration

Users can configure the plugin with these options in TRMNL:

- `Region`: Chooses the theatrical market to evaluate. Current options are Australia, Austria, Belgium, Brazil, Canada, Chile, Colombia, Denmark, Finland, France, Germany, Hong Kong, India, Ireland, Italy, Japan, Mexico, Netherlands, New Zealand, Norway, Philippines, Portugal, Singapore, South Africa, South Korea, Spain, Sweden, Switzerland, Taiwan, Thailand, United Arab Emirates, United Kingdom, and United States.
- `Genres`: Optional multi-select filter for the theatrical slate. Supports `All`, Action, Adventure, Animation, Comedy, Crime, Documentary, Drama, Family, Fantasy, History, Horror, Music, Mystery, Romance, Science Fiction, Thriller, War, and Western.

## Notes

- Refresh interval: every 360 minutes.
- Data source: TMDB. This product uses the TMDB API but is not endorsed or certified by TMDB.
