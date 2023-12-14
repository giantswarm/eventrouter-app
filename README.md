[![CircleCI](https://circleci.com/gh/giantswarm/eventrouter-app.svg?style=shield)](https://circleci.com/gh/giantswarm/eventrouter-app)

# ⛔️DEPRECATED eventrouter-app chart

This is repository is no longer actively maintained or updated.

Instead we recommed using [Grafana-Agent chart](https://github.com/giantswarm/grafana-agent-app)

Giant Swarm offers an Event Router Managed App which can be installed in tenant clusters.
Here we define the eventrouter chart with its templates and default configuration.

## Configuration
By default, the event router logs all events to the containers standard output.

More configuration will come in the future

## Installation
The application doesn't need any dependencies nor config, so it's sufficient to run:

helm install -n loki giantswarm-playground-catalog/eventrouter-app

## Compatibility
Tested on Giant Swarm release 11.3.3 on Azure with Kubernetes 1.16.8

## Credit

* https://github.com/heptiolabs/eventrouter
