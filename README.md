
# Ready to use docker compose script

Includes:

* Prometheus v2.2.0
* node-exporter v0.15.2
* grafana v5.0.1
                 

# How to run it

1) Make sure you have [docker](https://docs.docker.com/install/) and [docker-compose](https://docs.docker.com/compose/install/) installed
2) Clone repo: 
  `git clone git@github.com:ruXlab/grafana-suite-docker-compose.git`
3) Run compose in the folder
   `docker-compose up`

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
