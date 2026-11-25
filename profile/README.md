# Aule

**An open-source AI tutor for children, made in Lima, Peru.**

Aule combines voice tutoring, exercises and a model of what each student knows.
Families can use the browser tutor today. We are also developing a dedicated
e-ink device and its firmware; the mobile family app is planned.

## Start here

- **Use Aule:** [open the browser tutor](https://playground.meetaule.com/session/) or [learn about the product](https://meetaule.com).
- **Run your own tutor:** follow the [server setup](https://github.com/meet-aule/aule-sw#running-it-yourself).
- **Build or contribute to the device:** start with the [hardware guide](https://github.com/meet-aule/aule-hw#readme) and [firmware guide](https://github.com/meet-aule/aule-fw#readme).

## Repositories

| Repository | Purpose | Status |
|---|---|---|
| [aule-sw](https://github.com/meet-aule/aule-sw) | Voice tutor, browser interface, family and device APIs, learning model and operations | Implemented; active development |
| [aule-hw](https://github.com/meet-aule/aule-hw) | ESP32-S3 board, e-ink display, audio, microphone mute and printable dock | Hardware prototype |
| [aule-fw](https://github.com/meet-aule/aule-fw) | Firmware based on [xiaozhi-esp32](https://github.com/78/xiaozhi-esp32), board support and device integration | In development |
| [aule-app](https://github.com/meet-aule/aule-app) | Mobile family app for device setup, progress and privacy controls | Planned |

Each repository's README describes its setup, implemented features and validation
limits. Hardware bring-up and full device integration still need validation.

## Device design

<p align="center">
  <img src="https://raw.githubusercontent.com/meet-aule/aule-hw/main/hardware/enclosure/view.png" alt="Design render of Aule's prototype e-ink device and desk dock" width="420">
</p>

The hardware repository contains the [board and fabrication files](https://github.com/meet-aule/aule-hw/tree/main/hardware),
[bill of materials](https://github.com/meet-aule/aule-hw/blob/main/bom/README.md)
and [enclosure and assembly guide](https://github.com/meet-aule/aule-hw/blob/main/hardware/enclosure/README.md).

## Contribute

Build reports, reproducible bug reports and small, focused pull requests are
welcome in English or Spanish. Read the [contribution guide](https://github.com/meet-aule/.github/blob/main/CONTRIBUTING.md)
and open issues in the repository responsible for that component.

## Safety and privacy

Parental consent, safety checks that fail closed and a hardware microphone mute
are part of Aule's design. Children's data must not be used to train models.
Report security or privacy problems privately to **admin@meetaule.com**; see the
[security policy](https://github.com/meet-aule/.github/blob/main/SECURITY.md).
Never include a child's data, recordings or credentials in a public issue.

[meetaule.com](https://meetaule.com) · [Server documentation](https://github.com/meet-aule/aule-sw#readme)
