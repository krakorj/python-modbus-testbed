# Modbus server testbed

Python modbus TCP server simulator used for testing of a Modbus client.

## Configuration

* port: 5020
* endianning: byteorder = Endian.little, wordorder = little

## References

* https://www.simplymodbus.ca/TCPclient.htm
* https://pymodbus.readthedocs.io/en/latest/source/example/modbus_payload_server.html
* https://jacekhryniewicz.wixsite.com/website/modbus-simulator-of-tracerco-nucleonic-p

## TODOs

* Docker setup to be able to change simulator TCP port and endianning
* ...