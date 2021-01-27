# IoTDocker
Docker Compose file for IoT projects

Analytics & Monitoring software bundled up into convenient docker containers.

**It contains:**

* InfluxDB mapped to http://localhost:8086
* Chronograf UI mapped to http://localhost:8888
* Grafana UI mapped to http://localhost:3001
* NodeRed UI mapped to http://localhost:1880
* Mosquitto MQTT Broker mapped to http://localhost:1883

**How to use it ?**

1. Clone the repo or just get the file
2. Go to the repo folder
3. Use command `docker-compose up -d`

or in portainer

1. Go to stack tab
2. Add a new stack
3. Choose Git repository
4. Fill fields
