Visual TruView Extension for New Relic
=================

### About
For enterprises who have hybrid cloud applications, the TruView plugin in New Relic provides application and network infrastructure performance data from inside the enterprise data-center.

By deploying the plugin alongside your TruView, you can leverage the simplicity and availability of New Relic to make your network performance more accessible.

### Instructions for running the TruView Example Agent

By default, the agent is set up to use a demo user with a sample data set. This is to help get you off the ground more quickly! Try playing around with which metrics are reported to New Relic in the `fluke_agent` file.

1. Go to <a href="https://github.com/FlukeNetworks/flukenetworks_truview_plugin" target="_blank">TruView plugin page</a> and find the latest archive.
1. Download and extract the source
1. Run `bundle install`
1. Copy `config/template_newrelic_plugin.yml` to `config/newrelic_plugin.yml`
1. Edit `config/newrelic_plugin.yml` and replace "YOUR_LICENSE_KEY_HERE" with your New Relic license key. You can find this in your profile on New Relic.
1. Execute `./fluke_agent`
1. Go back to the Extensions list, after a brief period you will see an entry for the TruView extension
1. Customize your dashboard. Our default dashboards highlight application and site response times and usage, but you can play around with which metrics are reported and shown

### Using your own TruView

Once you've satisfied your curiosity with our sample agent and data set, you can easily connect to your own TruView appliance:

2. Complete above steps to get the TruView plugin
2. Edit `config/newrelic_plugin.yml` and replace the existing `agent_name`, `hostname`, `user`, and `password` as appropriate for your server.
