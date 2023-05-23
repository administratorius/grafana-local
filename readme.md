# Local Grafana

Based on https://github.com/joe-elliott/grafana-local

These docker-compose and associated config files can be used to start Grafana application for 

There are two stacks at present.  Each stack starts up the listed applications on the ports shown below.

- [Cortex](./cortex)
  - Grafana:    http://localhost:3000
  - Cortex:     http://localhost:9009

After running `docker-compose up` navigate to http://localhost:3000 and use Grafana to visualize the metrics/logs that are being stored.  

Use a dummy exporter to customize the metrics to be scraped.