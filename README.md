# employing-MQTT-protocol-to-control-relay-and-sensors-via-smartphone-
internet of things third project spring 2024 Amirkabir University of Technology (Tehran Polytechnic)

This project involves developing a Modbus control system for remotely managing relays via MQTT. The system enables a user to monitor and control relay states on a physical device through a smartphone or PC interface, using MQTT for real-time communication.

Features:

Real-Time Relay Status Monitoring: The controller polls each relay every 10 seconds to check and update its state.

Remote Control: Users can toggle relay states via an MQTT client on their smartphone or PC.

MQTT Communication: All control and status messages are exchanged over MQTT, ensuring quick and reliable updates.

Prerequisites:

Hardware: ESP32 (or other compatible microcontroller) with relays for Modbus communication

Software:

Arduino IDE with Modbus and MQTT libraries

MQTT Broker (e.g., Mosquitto)

MQTT client (e.g., MQTT Explorer for PC or a mobile MQTT app)




