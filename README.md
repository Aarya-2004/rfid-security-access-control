# rfid-security-access-control

## Overview
An Arduino-based RFID authentication system designed for secure access control. It verifies RFID tags and controls a door lock mechanism using a relay.

## Features
- RFID-based authentication
- Relay-controlled electromagnetic lock
- LED and buzzer feedback
- Serial monitoring for logging

## Tech Stack
- Arduino (Embedded C/C++)
- RC522 RFID Module
- Relay Module

## How It Works
The system reads RFID tag data and compares it with stored authorized IDs. If matched, access is granted and the lock is activated.

## Future Improvements
- Add database for multiple users
- Wi-Fi logging system
- Mobile app integration
