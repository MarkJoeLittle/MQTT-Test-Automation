# MQTT-Test-Automation
Automation for testing mqtt
I needed a way to test a few features via automation that had originally been manual tests. I created this basic automation script to test the relevant functionality.
I used these scripts in industry so what I posted here is heavily redacted. These scripts are used to test an over the air update via mqtt and check whether the system info is correct after an update.
The over the air update goes through several checks to ensure the process is completed correctly, the script checks each step.
The system info has many details to compare and each one is examined to ensure it is accurate.
A specific format is used for message handling, for coding and decoding the messaging but this can be altered for whatever is determined for the given system.

