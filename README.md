# dockprom-nodejs

### description
Simple nodejs app with Prometheus and Gragana. First of all, I express my gratitude to the [dockprom](https://github.com/stefanprodan/dockprom) project for creating docker-compose.yml with prometheus and grafana, ready to use.

### usage
1. [Install docker-compose](https://www.vagrantup.com/docs/installation/)  
2. Clone this repository and run `cd dockprom-nodejs && docker-compose up -d`.
![](https://github.com/ganochenkodg/dockprom-nodejs/blob/master/screens/docker-compose.png)
3. Deployed app sends his metrics in [Prometheus](https://prometheus.io/docs/introduction/overview/), for which the dashboard is configured in [Grafana](http://localhost:3000). Credentials for Grafana is admin:admin and dashboard name is MyApp monitoring.
![](https://github.com/ganochenkodg/dockprom-nodejsk/blob/master/screens/grafana.png)
