# Autonomous Waypoint Navigation Drone

**An independently assembled and configured quadcopter built around Pixhawk 2.4.8 and PX4, with successful autonomous waypoint missions.**

![Assembled autonomous quadcopter](media/drone-front.jpg)

## Overview

This project explores GPS-guided autonomous flight through the integration of a carbon-fibre quadcopter airframe, electric propulsion, a Pixhawk flight controller, and an M10N GPS module. I handled the complete build, including assembly, wiring, flight-controller configuration, mission planning, and flight testing.

The drone successfully completed preplanned waypoint missions. This repository documents the hardware, my engineering contribution, and the available project media.

**Project author:** Thiruppathi P  
**Status:** Built and flight-tested; waypoint completion confirmed by the project author.

## Hardware

| Component | Specification |
|---|---|
| Airframe | Carbon fibre, 500 mm wheelbase |
| Flight controller | Pixhawk 2.4.8 |
| Motors | DYS 750 KV |
| Electronic speed controllers | 45 A |
| Propellers | 1145 (11-inch diameter, 4.5-inch pitch) |
| Battery | 6200 mAh, 4S |
| GPS module | M10N |
| Flight firmware | PX4; version not recorded |
| Ground-control tools used | QGroundControl and Mission Planner |

The software names above record the tools used during the project. The exact tasks performed in each application were not separately recorded.

## My contribution

- Assembled the airframe and integrated the propulsion and navigation hardware.
- Completed electrical wiring and component integration.
- Configured the flight controller for the aircraft.
- Planned autonomous waypoint missions.
- Conducted flight testing and completed waypoint missions.

## Project gallery

![Top view showing the quadcopter layout](media/drone-top.jpg)

*Top view of the assembled aircraft, showing its four motors, propellers, arms, and central enclosure.*

### Flight video

[![Preview of the supplied flight video](media/flight-preview.jpg)](media/flight-demo.mp4)

[Open or download the flight video](media/flight-demo.mp4).

The video is included as project media. It is not a flight-log record of waypoint completion.

## Results and documentation scope

The author confirms successful autonomous waypoint missions. Two build photos and one video are included. Flight duration, navigation accuracy, payload capacity, mission distance, and endurance have not been quantified here because supporting measurements were not supplied.

This is a hardware and integration portfolio repository. It does not contain original custom flight-control code, a PX4 firmware build, parameter exports, or mission files. PX4 is the firmware used in the project; it is not claimed as software authored for this repository.

## Repository contents

| Location | Contents |
|---|---|
| `media/` | Two JPEG build photos, a video preview, and the supplied MP4 |
| `docs/project-record.md` | Evidence notes and items that could extend the documentation |
| `docs/repository-details.md` | Suggested GitHub name, description, and topics |

## Viewing this project

Open this README on GitHub to view the photos and follow the video link. After downloading the repository, open the JPEG and MP4 files using an image viewer and video player. No software installation or build step is required.

## Potential documentation additions

- PX4 version and an exported parameter file.
- A mission-plan export and corresponding flight log.
- Wiring diagram and detailed component model numbers.
- Measured flight duration and waypoint-tracking results.

These are documentation opportunities, not claims of additional completed work.
