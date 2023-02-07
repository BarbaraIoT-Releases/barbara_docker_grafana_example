Basic Grafana/Influxdb/Node-RED environment.

Every container has it own persist folder, to be able to keep date between containers updates.
All persist folders declarations must starts with "./persist/", or Barbara OS will reject volume declaration.
