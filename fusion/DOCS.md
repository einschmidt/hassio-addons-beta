# Home Assistant Add-on: Fusion

A lightweight, self-hosted friendly RSS reader

## Installation

Add this repository to your [Hass.io](https://home-assistant.io/hassio/) instance:

`https://github.com/einschmidt/hassio-addons`

If you have trouble you can follow the [official docs](https://home-assistant.io/hassio/installing_third_party_addons/).

Then install the "Fusion" add-on.

## Configuration

**Note**: _Remember to restart the add-on when the configuration is changed._

### Option: `log_level`

The `log_level` option controls the level of log output by the addon and can
be changed to be more or less verbose, which might be useful when you are
dealing with an unknown issue. Possible values are:

- `trace`: Show every detail, like all called internal functions.
- `debug`: Shows detailed debug information.
- `info`: Normal (usually) interesting events.
- `warning`: Exceptional occurrences that are not errors.
- `error`: Runtime errors that do not require immediate action.
- `fatal`: Something went terribly wrong. Add-on becomes unusable.

Please note that each level automatically includes log messages from a
more severe level, e.g., `debug` also shows `info` messages. By default,
the `log_level` is set to `info`, which is the recommended setting unless
you are troubleshooting.
