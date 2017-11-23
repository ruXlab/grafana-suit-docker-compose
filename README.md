
# Ready to use docker compose script

Includes:

* Prometheus v2.0
* node-exporter v0.15.1
* grafana v4.6.2


#### Bootstap your grafana [optional]

1. Navigate to the http://localhost:3000

2. Login using default login/password: `admin`:`pass`

3. Add data source

  * type: **Prometheus**
  * name: **prometheus**
  * URL: **http://prometheus:9090**
  * access: **proxy**

4. Add basic dashboards

* Select **Import Dashboard** -> put grafana.com dashboard #**[22](https://grafana.com/dashboards/22)**




Originally based on [feinstruktur/blogpost-prometheus](https://github.com/feinstruktur/blogpost-prometheus)
