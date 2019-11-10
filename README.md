# node-red-bme280
Node-Red flow to read from BME280 environmental sensor and send data to Nooode API Gateway

1. Connect BME280 to Pi 
![Alt text](BME280-Module-Setup.png?raw=true "Setup")

2. Import the flow into Node-Red (node-red-flow.json)

3. Edit HTTP Request Node to you API Gateway Endpoint. If your API Gateway is created from BME280-influxDB Starter, HTTP Request URL should be https://{your public host name}.s1.zetez.com/node/bme280

4. Set Time Interval to read BME280.


