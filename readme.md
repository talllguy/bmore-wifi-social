# DC WiFi Social

<img src="https://travis-ci.org/benbalter/dc-wifi-social.png">


### A collaborative list of ~~DC~~ **Baltimore** locations that serve up both Internet and Alcohol

*Because coding together is better than coding alone (TM)*

### [The Map](bars.geojson)

## License

CC-BY-SA

## Idea / Fork Source

@benbalter: https://github.com/benbalter/dc-wifi-social

## How to contribute

1. Fork the project
2. Add or edit a location by editing and following the format in `bars.geojson` (hint, it's geoJSON)
3. Submit a pull request

## Validating the geoJSON

When you submit a pull request, it will automatically check to ensure your geoJSON is valid.

If you'd like to check yourself, you can run `./script/cibuild` locally, or pasting the contents of `bars.geojson` into http://geojsonlint.com.

## How to find the lat/long of a location

Pop it into http://geocoder.us/. Boom.
(Or use [geojson.io](http://geojson.io/#map=13/39.3101/-76.6248))

## Why?

Don't ask such questions.
