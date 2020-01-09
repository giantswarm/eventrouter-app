[![CircleCI](https://circleci.com/gh/giantswarm/eventrouter-app.svg?style=shield)](https://circleci.com/gh/giantswarm/eventrouter-app)

# eventrouter-app chart

Giant Swarm offers an Event Router Managed App which can be installed in tenant clusters.
Here we define the eventrouter chart with its templates and default configuration.


## Configuration
By default, the event router logs all events to the containers standard output.

More configuration will come in the future

## Installation
The application doesn't need any dependencies nor config, so it's sufficient to run:

helm install -n loki giantswarm-playground-catalog/eventrouter-app

## Compatibility
Tested on Giant Swarm release 9.0.0 on Azure with Kubernetes 1.15.5

## Credit

* https://github.com/heptiolabs/eventrouter
