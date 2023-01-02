
![Logo](https://user-images.githubusercontent.com/64506580/159311466-f720a877-6c76-403a-904d-134addbd6a86.png)


# Node-red, InfluxDB, Grafana (NIG) Stack

Gain the ability to analyze and monitor telemetry data by deploying the TIG stack within minutes using [Docker](https://docs.docker.com/engine/install/) and [Docker Compose](https://docs.docker.com/compose/install/).




## ⚡️ Getting Started

Clone the project

```bash
git clone 
```

Navigate to the project directory

```bash
cd nig-stack
```

Change the environment variables define in `.env` that are used to setup and deploy the stack
```bash
├── .env         <---
├── docker-compose.yml
├── entrypoint.sh
└── ...
```

Start the services
```bash
docker-compose up -d
```
## Docker Images Used (Official & Verified)

[**node-red**](https://hub.docker.com/r/nodered/node-red) / latest

[**InfluxDB**](https://hub.docker.com/_/influxdb) / latest

[**Grafana-OSS**](https://hub.docker.com/r/grafana/grafana-oss) / `8.4.3`



## Contributing

Contributions are always welcome!

