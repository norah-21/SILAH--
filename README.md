# SILAH--
SILAH is a proposed smart wristband and Digital Twin system to keep Umrah pilgrims connected within Masjid Al-Haram. This repository contains the project concept, proposed system design, and implementation plan.
1-
SILAH aims to help pilgrims stay connected and find their group members inside masjid Al-Harm.

The Problem 
Millions of pilgrims visit Masjid Al-Haram, making it easy for families and groups to become separated in crowded areas. Traditional GPS systems lack the indoor accuracy needed to identify specific floors, gates, and locations, making reunification difficult.

The Proposed Solution
SILAH connects pilgrims through smart wristbands that provide vibration alerts when group members separate or reunite. Using Digital Twin technology, the system enables precise indoor positioning, identifies floors and nearby gates, and provides walking directions، Location sharing is customizable for families, children, and group leaders to ensure safe and organized reunification.
2-
Workflow
The flow diagram below illustrates how SILAH monitors group members,sends separation alerts,and guides them toward reunification.
<img width="987" height="1934" alt="Blank diagram" src="https://github.com/user-attachments/assets/9b8fe7d7-c5f3-4617-a8a5-95ad32d83a18" />

3-
4-Proposed Hardware Components
1- ESP32 Microcontroller
Acts as the main controller of the smart bracelet. It processes incoming data, manages
connected components, and controls the bracelet's operations.
2-GPS/GNSS Module
Provides the user's geographical location outdoors, helping the system track pilgrims and
assist in locating them when needed.
3-Bluetooth Low Energy (BLE)
Enables wireless communication with nearby devices and supports proximity detection and
indoor positioning when used with compatible beacons.
4-Accelerometer Sensor
Detects movement and changes in motion, helping the system identify whether the user is
moving or stationary.
5-Emergency Button
Allows the wearer to manually request assistance by triggering an emergency alert that can
be sent to the connected application or monitoring system.
6-Vibration Motor
Provides physical alerts through vibration, notifying the wearer when an important
notification or warning is received.
7-Rechargeable Battery
Supplies the electrical power needed to operate the bracelet's electronic components and
supports portable use throughout the day.
8-Charging Circuit
Manages the battery charging process and provides the necessary charging and protection
functions for safe operation.
9-Indoor BLE Beacons
Fixed devices installed at known locations inside buildings to help estimate the wearer's
position and identify nearby areas or floors
10-Touchscreen Display
Displays alerts and group member information, allowing the wearer to select a member and view navigation guidance directly on the bracelet.
11-BLE Gateways
Network-connected devices installed throughout the coverage area to relay data and alerts between the bracelets and the central system, even when group members are beyond direct Bluetooth range.

