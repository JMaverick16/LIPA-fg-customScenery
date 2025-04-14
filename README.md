# LIPA-fg-customScenery
Add-on scenery package that improves the already-existing work available on TerraSync made by J Maverick 16.
=====================

Overview
-------------------------
This repository contains several additional static objects, improved airport data (tower position and elevation, parking positions, etc.), and OSM2city.py pylons for Aviano Air Base (LIPA), nearby airports, surrounding Italian territory and the driveable Aviano-Piancavallo road.
The aim is to provide the closest to real-life simulation possible based on is available in FlightGear nowadays.
The following improved airports are included: LIPA, LIPI, LIPD, LIDK, LIPG, LIPS, LIDB, LIPB, and LIDA.

Installation instructions
-------------------------
After unzipping the package, select it via the FG launcher in the Add-ons -> Additional scenery folders section.
To see the OSM2city pylons, enable them in-sim on the menu at View -> Rendering Options -> Pylons.
Since December 2020, the AirBase models pack has been included directly in the repository, therefore, no additional installation packs are required.
Since January 2022, all the objects that have been revised inside the TerraSync database have been added in the repo for the correct display of the models.

For the AI Truman carrier, copy over the XML file inside FGData/AI, then activate it via launcher as truman_adriatic or inside the AI dialog once in-sim.

USS Truman AI carrier scenario
-------------------------
A dedicated USS Truman AI scenario spawns the carrier plus its fleet in the southwestern portion of CRIT airspace, about 130NM south of Aviano AB and 46NM east of Rimini (LIPR).
The carrier speed is 0 kts, which enables pilots to avoid having any position offset compared to other pilots and, of course, allows everyone to use it simultaneously.
IMPORTANT: When running this scenario, ensure the original Truman demo is disabled to avoid potential issues.

INFO:
- TACAN: 031X - 109.4 MHz
- Heading: 320
- Location: 130NM south of LIPA, 46NM east of LIPR (44.0N, 13.6E).

Escorts:
- 2x CG-57 USS Lake Champlain (Ticonderoga-class cruiser)
- 5x Oliver Perry (Guided missile frigate)
- 1x LPD-17 San Antonio (Amphibious transport dock)
- 2x MH-60 Helicopter

Licenses
--------

*  The air bases layout and ground networks are licensed under the terms of the GNU GPLv2 or later.
*  The 3D objects and models are licensed under the terms of the GNU GPLv2 or later.
  

:copyright: 2019-2025 J Maverick 16 (3D models placement, airport data, ground network changes, AI Truman)
:copyright: 2020-2021 Marsdolphin (improved ground network)
:copyright: 2020 VIPER (initial ground network)
:copyright: 2020-2021 mada00 (NATO Military Shelter model)
:copyright: 2020-2021 abassign (NATO Military Shelter model)
:copyright: 2019 HB-VANO (OSM2city.py pylons and roads work)
:copyright: 2014 Lester Boffo (original Aviano-Piancavallo road models)
