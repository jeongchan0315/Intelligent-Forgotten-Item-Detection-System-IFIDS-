# Intelligent-Forgotten-Item-Detection-System-IFIDS-

## Project Overview
IFIDS (Intelligent Forgotten Item Detection System) is a departure detection system that helps users reduce instances of leaving essential items behind. Primarily based on an Arduino Uno, RFID tags, and HuskeyLens computer vision, the system will detect whether the user has forgotten an item and alert them. The final product will also be able to determine the time of day to see whether a certain item is necessary. The goal of the IFIDS is to create an affordable solution to a small but meaningful problem in everyday life. This is a beginner-friendly passion project that will slowly develop over time.

## Problem Statement
In everyday life, people are constantly forgetting minor details that are reportedly only small inconveniences. However, these memory lapses tend to lead to stress build-up, ultimately reducing cognitive skills.

## Design Objective
The IFIDS will remind users of items they have forgotten and help them leave the establishment without memory lapses, thereby reducing stress. Additionally, the IFIDS also exists to improve upon existing products.

## IFIDS Prototype One, Proof of Concept
- July 15
### Completed Work
- Integrated HuskeyLens and LCD (1602A) using I2C bus
- Included facial recognition to identify users
- Integrated MFCR522 RFID Reader module to the LCD and HuskeyLens
### Prototype Behavior
- Detects a user using a HuskeyLens
- Upon detecting a registered User, a Missing statement will appear under the User's name, waiting for item detection
- Confirms whether or not items are present
- Displays "Good to go" if all items are present. Otherwise identifies what is currently missing
### Problems Overcome
- Learned how to wire multiple Arduino modules and parts
- Debugged HuskeyLens multiple times
- Verified I2C addresses due to address errors
- Learned to use I2C modules to optimize the number of pins used
### Possible Future Improvements
- Adding a magnetic reed switch for door exit sensor
- Add a buzzer to make alerts more apparent
- Expand item database
- Look into an independent power supply (likely a battery)

## References
- Godman, H. (2025, April 1). *How to stop stressing over minor memory lapses.* Harvard Health Publishing. https://www.health.harvard.edu/mind-and-mood/how-to-stop-stressing-over-minor-memory-lapses
- Arduino. (n.d.). Liquid crystal displays (LCD) with Arduino. Arduino Documentation. https://docs.arduino.cc/learn/electronics/lcd-displays/
