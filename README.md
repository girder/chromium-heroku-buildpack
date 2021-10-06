# chromium-heroku-buildpack
A buildpack to install chromium on Heroku

## Usage

This buildpack is available on the Heroku buildpack registry via the `girder/chromium` shorthand identifier.

### Configuration

You can set the Chromium revision to use by setting a config var on your Heroku app with the key `CHROMIUM_REVISION`. If you do not set this config var, the most recent revision will be downloaded and used.
