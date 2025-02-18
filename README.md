# Project: Integrating CODESYS with Node-RED, InfluxDB, and Grafana via MQTT

## Description
This project demonstrates the integration of CODESYS with Node-RED, InfluxDB, and Grafana using the MQTT protocol. Data flows from CODESYS to Node-RED for processing, storage in InfluxDB, and visualization in Grafana.

## Requirements
- **CODESYS**: PLC development environment.
- **Node-RED**: Visual programming tool. [Documentation](https://nodered.org/docs/)
- **InfluxDB**: Time-series database.
- **Grafana**: Data visualization platform. [Documentation](https://grafana.com/docs/)
- **MQTT Broker**: e.g., Mosquitto.

## Installation and Configuration
### 1. CODESYS
- **MQTT Configuration:** Set up the MQTT client to publish data.
- **Sample Code:** Available in the current repository.

### 2. Node-RED
- **Installation:** Follow the [official guide](https://nodered.org/docs/getting-started/).
- **Importing Flows:** Import from [MQTT-INFLUXDB-CODESYS-GRAFANA](https://github.com/controlbytePL/MQTT-INFLUXDB-CODESYS-GRAFANA).
- **MQTT Configuration:** Subscribe to CODESYS topics.
- **Data Processing:** Parse JSON and store in InfluxDB.

### 3. InfluxDB
- **Installation:** Follow [InfluxDB installation](https://docs.influxdata.com/influxdb/v1.8/introduction/install/).
- **Configuration:** Create a database for Node-RED data.

### 4. Grafana
- **Installation:** Follow the [installation guide](https://grafana.com/docs/grafana/latest/installation/).
- **Data Source:** Connect to InfluxDB.
- **Dashboard:** Import from [grafanamqtt](https://github.com/controlbytePL/grafanamqtt).

## Running on Windows
1. **Node-RED:** Run `node-red` in the command prompt.
2. **Mosquitto:** Start the service.
3. **InfluxDB:** Start the service.

## Repository Links
- [MQTT-INFLUXDB-CODESYS-GRAFANA](https://github.com/controlbytePL/MQTT-INFLUXDB-CODESYS-GRAFANA)
- [grafanamqtt](https://github.com/controlbytePL/grafanamqtt)
- [CMD-Python-commands](https://github.com/controlbytePL/CMD-Python-commands)

## Notes
- Ensure services are running and configured properly.
- Adjust configurations as needed.

## License
This project is licensed under the MIT License.

