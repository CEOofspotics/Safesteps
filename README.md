Overview
SafeSteps is an innovative smart shoe made to improve the safety of women. It  detects a Morse code SOS pattern, sends an SOS emergency alert from the user's GPS position to the closest authorities or an emergency contact for reliable fast help in risky situations.

SOS Detection
The SOS can be detected using a Morse code pattern with a touch sensor: three short taps, three long taps, three short taps.
GPS Location: Captures real-time location data using a GPS module.
Emergency Alerts: Sends SMS alerts with the user's location via a SIM800L module.
Discreet and Reliable: It enables users to signal for help without drawing attention to themselves.
How It Works
The user taps the touch sensor in the SOS Morse code pattern.
The ESP32 processes the pattern and validates it as an SOS signal.
The GPS module fetches the user's current location.
The SIM800L module will send an SMS containing a location to predefined emergency contacts or local authorities.
