<p align="center">
    <br>
    <a href="https://bless-bexus.es">
        <img src="docs/Logo BLESS.png" width="150" alt="BLESS Logo"/>
    </a>
</p>
<h1 align="center">Power Control Unit</h1>
<p align="center">
A custom PCB designed to distribute and regulate a single 28 V DC input into multiple power rails for embedded hardware systems.
</p>
<p align="center">
    <img src="https://img.shields.io/badge/Status-In%20development-green" alt="Status">
    <img src="https://img.shields.io/badge/Software-KiCad-blue" alt="KiCad">
    <br>
    <a href="https://rexusbexus.net/">
        <img src="https://img.shields.io/badge/Program-REXUS%2FBEXUS-yellow" alt="REXUS/BEXUS Program">
    </a>
</p>

---

### Overview

The main goal of this PCB is to provide a compact and reliable power distribution stage for embedded systems that require several regulated voltage rails from a single DC input.

The board takes a nominal 28 V DC input and generates the regulated power rails required by the system:

- 3.3 V for logic, microcontrollers and digital sensors.
- 5 V for auxiliary electronics and interface modules.
- 12 V for higher-power loads such as heaters or dedicated subsystems.

This PCB centralizes power conversion, protection and distribution, making the overall system easier to integrate, debug and maintain.

### Purpose

This board is designed to simplify power management in systems where multiple voltage levels are required from a single supply line.

It is especially useful in applications that need:

- Centralized power distribution.
- Regulated low-voltage rails.
- Separation between logic, auxiliary and high-power loads.
- Protection against electrical faults.
- Cleaner wiring between subsystems.
- Easier integration with the rest of the electronics.

### Main Features

- Single 28 V DC input.
- Regulated 3.3 V output rail.
- Regulated 5 V output rail.
- Regulated 12 V output rail.
- TRACO POWER DC/DC converters.
- Input protection stage.
- Reverse-polarity protection.
- Fuse protection.
- Decoupling and filtering capacitors.
- Dedicated outputs for different subsystem power rails.
- Custom KiCad symbols, footprints and 3D models.

---

<h3 align="center">Contributing</h3>
<p align="center">
·
    <a href="./CODE_OF_CONDUCT.md">Code of Conduct</a>
    ·
    <a href="./CONTRIBUTING.md">Contributing Guide</a>
    ·
</p>
<p align="center">We welcome collaboration from the aerospace and hardware community. For major changes or data inquiries, please open an issue first.</p>
<h3 align="center">License</h3>
<pre align="center">Copyright © 2025-2026 The BLESS Project Team<br><br>This Source Code Form is subject to the terms of the Mozilla Public<br>License, v. 2.0. If a copy of the MPL was not distributed with this<br>file, You can obtain one at http://mozilla.org/MPL/2.0/.</pre>
<h3 align="center">Credits & Team</h3>
<p align="center">Supported by the REXUS/BEXUS Program and our generous sponsors.</p>
<p align="center">
    <a href="https://github.com/BLESS-BEXUS/Power-Control-Unit-System-PCB/graphs/contributors">
        <img src="https://contrib.rocks/image?repo=BLESS-BEXUS/Power-Control-Unit-System-PCB" width="50"/>
    </a>
</p>
