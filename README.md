Fluke Networks TruView Extension for New Relic
=================

### Instructions for running the TruView Agent

1. Go to <a href="https://github.com/newrelic-platform/flukenetworks_truview_extension" target="_blank">TruView plugin page</a> and find the latest archive.
1. Download and extract the source
1. Run `bundle install`
1. Copy `config/template_newrelic_plugin.yml` to `config/newrelic_plugin.yml`
1. Edit `config/newrelic_plugin.yml` and replace "YOUR_LICENSE_KEY_HERE" with your New Relic license key
1. Edit `fluke_agent` and replace "YOUR_GUID_HERE" with your New Relic plugin guid
1. Execute `./fluke_agent`
1. Go back to the Extensions list, after a brief period you will see an entry for the TruView extension

### Using your own TruView
2. Complete above steps to get the TruView plugin
2. Edit `config/newrelic_plugin.yml` and replace the existing `agent_name`, `hostname`, `user`, and `password` as appropriate for your server.
