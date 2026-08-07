<p align="center">
 
</p>

<h1 align="center">Hamersaw</h1>
<p align="center"><b>1lb Antweight Combat Robot — Vertical Spinner</b></p>

<p align="center">
  <a href="https://github.com/lidmasina123/1lb-combat-robot-/graphs/contributors"><img src="https://img.shields.io/github/contributors/lidmasina123/1lb-combat-robot-.svg?style=for-the-badge" alt="Contributors"></a>
  <a href="https://github.com/lidmasina123/1lb-combat-robot-/network/members"><img src="https://img.shields.io/github/forks/lidmasina123/1lb-combat-robot-.svg?style=for-the-badge" alt="Forks"></a>
  <a href="https://github.com/lidmasina123/1lb-combat-robot-/stargazers"><img src="https://img.shields.io/github/stars/lidmasina123/1lb-combat-robot-.svg?style=for-the-badge" alt="Stargazers"></a>
  <a href="https://github.com/lidmasina123/1lb-combat-robot-/issues"><img src="https://img.shields.io/github/issues/lidmasina123/1lb-combat-robot-.svg?style=for-the-badge" alt="Issues"></a>
  <a href="https://github.com/lidmasina123/1lb-combat-robot-/blob/main/LICENSE"><img src="https://img.shields.io/github/license/lidmasina123/1lb-combat-robot-.svg?style=for-the-badge" alt="License"></a>
</p>

A 1lb (antweight) combat robot built around a giant Hardox-steel vertical spinner. Instead of wheels, Hamersaw drives on a pair of brushless-actuated nylon-and-silicone feet — so instead of the usual antweight buzz-and-nudge, it walks up to opponents and hits them with a hardened steel bar spinning fast enough to end the fight in one pass.

[**Explore the docs »**](https://github.com/lidmasina123/1lb-combat-robot-)

[Build Journal](JOURNAL.md) · [Report Bug](https://github.com/lidmasina123/1lb-combat-robot-/issues) · [Request Feature](https://github.com/lidmasina123/1lb-combat-robot-/issues)

---

**Table of Contents**

1. [About The Project](#about-the-project)
   - [Key Features](#key-features)
   - [Built With](#built-with)
2. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Repo Contents](#repo-contents)
3. [Build & Assembly](#build--assembly)
4. [System Overview](#system-overview)
5. [Roadmap](#roadmap)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

---

## About The Project

Hamersaw is a full-combat 1lb antweight built for the ring, not the arena of "please don't break." The whole robot is designed around one idea: put as much kinetic energy as possible into a single Hardox steel bar, and don't waste weight budget on wheels that a hit could snap off anyway.

Everything in this repo — CAD, STL/STEP files, the BOM, wiring diagram, and assembly notes — is here so the build is fully reproducible, and so future-me (or anyone else) can retrace every design decision in the build journal instead of guessing from finished parts.

### Key Features

- **Hardox Steel Vertical Spinner**
  Full-width vertical spinner bar machined from Hardox for maximum toughness against opposing weapons.

- **Feet-Based Drivetrain (No Wheels)**
  Brushless-driven nylon feet with silicone traction pads replace the usual wheel-and-tire setup, keeping traction and ground clearance high while removing a common failure point.

- **Dual AM32 ESC Control**
  Runs on a Repeat Robotics dual AM32 open-source ESC, giving reliable, tunable brushless drive control without proprietary firmware lock-in.

- **Direct-Drive Weapon**
  Tangent Drive 1407 spins the weapon directly, paired with a Repeat 2307 brushless motor on the drivetrain side.

- **Fully Documented Build**
  CAD source files (Fusion 360 `.f3z` + `.step`), a full BOM, wiring diagram, and a running build journal are all included.

### Built With

- Hardox steel (weapon bar)
- Nylon + silicone (feet / traction pads)
- [Repeat 2307](https://repeatrobotics.com/) brushless motor
- Tangent Drive 1407 (weapon motor)
- Repeat Robotics dual [AM32](https://github.com/am32-firmware/AM32) ESC
- [Fusion 360](https://www.autodesk.com/products/fusion-360/) (CAD)

---

## Getting Started

Everything needed to reproduce or reference this build lives in this repo.

### Prerequisites

- Access to a mill/CNC or waterjet capable of cutting Hardox steel (for the weapon and metal forks)
- A 3D printer for the nylon feet, drive pods, gears, and arm holder
- Basic brushless motor + ESC soldering/wiring experience
- Fusion 360 (or a STEP-compatible CAD viewer) to open the source files
- Parts from the [BOM](bomc.csv)

### Repo Contents

| File | Purpose |
| --- | --- |
| `hamersaw1lb.f3z` / `hamersaw1lb.step` | Full CAD assembly |
| `main body metal forks.stl` | Hardox chassis/forks — cut file |
| `arm holder.stl` | Weapon arm mount |
| `driwe pods.stl` | Drive pod housings for the feet |
| `gears.stl` | Drivetrain gearing |
| `bom` / `bomc.csv` | Bill of materials |
| `asembly instrucshon` | Step-by-step assembly notes |
| `wiering diagram.png` | Electronics wiring diagram |
| `JOURNAL.md` | Build log / design decisions |

---

## Build & Assembly

1. Cut the main body and forks from Hardox steel per `main body metal forks.stl`
2. 3D print the feet, drive pods, gears, and arm holder
3. Order parts per the [BOM](bomc.csv)
4. Wire the Repeat 2307 drive motor and Tangent Drive 1407 weapon motor into the dual AM32 ESC following [`wiering diagram.png`](wiering%20diagram.png)
5. Flash/configure AM32 on both ESC channels
6. Follow [`asembly instrucshon`](asembly%20instrucshon) for final mechanical assembly
7. Balance and spin-test the weapon before any drive testing

---

## System Overview
<img width="987" height="691" alt="image" src="https://github.com/user-attachments/assets/5408aaca-5803-4bbd-8444-04bbc5571209" />

## Roadmap

- [ ] Finalize weapon balance/tuning
- [ ] First competition test
- [ ] Iterate on foot traction (silicone compound testing)
- [ ] Publish full assembly instructions
- [ ] Post fight footage / results to the journal

See the [open issues](https://github.com/lidmasina123/1lb-combat-robot-/issues) for the full list of known issues and proposed changes.

---

## Contributing

Suggestions, part sourcing tips, and design feedback are welcome.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## License

Distributed under the license in [`LICENSE`](LICENSE).

---

## Contact

Project Link: <https://github.com/lidmasina123/1lb-combat-robot->

([back to top](#hamersaw))
