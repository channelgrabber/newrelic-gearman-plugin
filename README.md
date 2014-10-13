## Gearman Agent Installation

1. Download to the location you want to run the gearman agent from
2. Copy `config/newrelic_plugin.yml.dist` to `config/newrelic_plugin.yml`
3. Edit `config/newrelic_plugin.yml` and replace "YOUR_LICENSE_KEY_HERE" with your New Relic license key
4. Configure the servers to monitor under the servers collection in the config file
5. Run `./newrelic_gearman_agent`
