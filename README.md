# ChannelGrabber Gearman NewRelic Plugin

## Overview

This plugin will provide metrics from one or more [Gearman](http://gearman.org/) servers to NewRelic. Metrics are provided for the number of queued jobs, number of workers and number of running jobs for the whole server and for each queue.

## Prerequisites

- Ruby
- Bundler
- A NewRelic account

## Gearman Agent Installation

1. Download to the location you want to run the Gearman agent from
2. Run `bundle install` in the folder you downloaded the agent to
2. Copy `config/newrelic_plugin.yml.dist` to `config/newrelic_plugin.yml`
3. Edit `config/newrelic_plugin.yml` and replace "YOUR_LICENSE_KEY_HERE" with your New Relic license key
4. Configure the servers to monitor under the servers collection in the config file
5. Run `./newrelic_gearman_agent`
