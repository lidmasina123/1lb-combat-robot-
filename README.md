# Zagitis

**Zagitis** is a 1 lb combat robot with a unique weapon system. Unlike most robots in this weight class, which simply use a spinning weapon mounted directly to the chassis, Zagitis uses an **articulating weapon arm** with a spinning mass mounted at the end.

This allows the weapon to feed into an opponent more effectively, increasing the amount of damage it can deal.

The robot is designed to attack opponents from above, as the top armor on many 1 lb combat robots is significantly weaker than the front or sides.

I chose this design because many modern atveight robots are extremely similar—typically 4WD vertical eggbeaters. Building a robot that is only slightly better than existing designs is both difficult and expensive. Instead, Zagitis is designed to counter this common style by targeting their weaker top armor.
<img width="860" height="570" alt="Screenshot 2026-06-25 173845" src="https://github.com/user-attachments/assets/330d0d51-4b6f-4176-aa5e-c4251ceb550b" />
<img width="647" height="497" alt="Screenshot 2026-06-25 140701" src="https://github.com/user-attachments/assets/a707f896-36c5-4b2c-909c-b757ba32095e" />
<img width="1012" height="560" alt="Screenshot 2026-06-25 170153" src="https://github.com/user-attachments/assets/a6e6f541-ad6b-49bf-a450-5743db45357c" />
<img width="916" height="625" alt="Screenshot 2026-06-25 171035" src="https://github.com/user-attachments/assets/752acfdc-5f29-4391-901d-fa42831052d2" />

---

# Features

## 1. Fully Brushless Drive

The drive system is completely brushless, providing a better power-to-weight ratio, higher efficiency, and improved reliability.

## 2. Carbon Fiber + TPU Construction

The robot combines carbon fiber with TPU printed parts. This allows it to absorb impacts while remaining structurally rigid.

## 3. Compact Electronics

The robot uses **two Repeat Robotics dual-drive ESCs**, allowing all of the electronics to fit into a very compact chassis.

## 4. Narrow but Wide Design

The robot is narrow from the front while maintaining a wide wheelbase. This reduces the number of exposed sides where opponents can gain an advantage while improving stability.

## 5. 4S Battery

Most 1 lb combat robots run on **3S batteries**.

Zagitis uses a **4S battery** for increased power and faster weapon spin-up.

## 6. Two Configurations

The robot has two interchangeable configurations depending on the opponent.

- Vertical spinner configuration
- Horizontal spinner configuration

## 7. Tangent Drive

Unlike most 1 lb combat robots, which use smaller motors paired with gearboxes, Zagitis uses **tangent drive motors**.

This allows the use of larger, more powerful motors while eliminating the gearbox, reducing complexity and improving efficiency.

---

# Wiring Diagram

<img width="987" height="691" alt="wiering diagram" src="https://github.com/user-attachments/assets/50dbace7-dd9a-4263-b158-862635a298c3" />

---

# Bill of Materials

| Part | Link | Price | Qty | Total |
|------|------|------:|----:|------:|
| Drive Motors – Tangent 1406 | https://palmbeachbots.com/products/repeat-robotics-tangent-drive-motor-1406-1500kv | $18 | 2 | $36 |
| Arm Motor – 16 mm Brushed Planetary | https://palmbeachbots.com/products/repeat-robotics-16mm-brushed-planetary-motor | $17 | 1 | $17 |
| Weapon Motor – Repeat 2307 | https://www.aliexpress.com/item/1005007338658310.html | $15 | 1 | $15 |
| Repeat Robotics Dual Drive ESC | https://palmbeachbots.com/products/repeat-robotics-am32-dual-brushless-drive-esc-with-bec | $40 | 2 | $80 |
| FlySky FS-i4X Transmitter | https://palmbeachbots.com/products/flysky-fs-i4x-2-4ghz-4-channel-transmitter-with-receiver-afhds2a | $52 | 1 | $52 |
| FS2A Receiver | https://palmbeachbots.com/products/fs2a-4-channel-mini-receiver-afhds-2a-works-with-flysky-fs-i6 | $12 | 1 | $12 |

## Total Cost

**$212 USD**

---

# Assembly

This robot is designed to be easy to assemble and repair, making it quick to service between fights.

## Step 1 – Assemble the Drive Pods

First, assemble the two drive pods.

Each drive pod requires:

- 2 × M4 screws or shoulder bolts for the wheel
- 4 × M2 screws to mount the drive motor

Once assembled, make sure the wheel spins freely.

---

## Step 2 – Assemble the Weapon Arm

You will need:

- 1 × M4 bolt for the arm shaft
- 2 × M2 screws for the arm motor

Attach the arm motor first.

Press the gear onto the motor shaft.

Insert the arm shaft through one side of the chassis, through the arm gear (with both **4×8×3 mm bearings** installed), and out through the opposite side.

Finally, bolt the weapon arm to the arm gear and install the completed assembly into the chassis.

---

## Step 3 – Assemble the Chassis

Attach all mechanical components to the bottom carbon fiber plate using:

- 18 × 2.5 mm wood screws

---

## Step 4 – Install the Electronics

Install both dual-drive ESCs.

Wiring is straightforward:

- Connect each drive motor to one side of a dual-drive ESC.
- Connect both ESC signal wires to the receiver.
- Connect the weapon ESC and weapon motor.
- Connect the battery.
- Verify that all motors spin in the correct direction before securing the wiring.

---

## Step 5 – Finish Assembly

Install the top armor plates and secure them with the screws.

The robot is now fully assembled and ready for testing.

> **Note**
>
> More detailed assembly instructions with photos will be added once all of the parts have arrived and the robot has been fully assembled.

---

# Additional Information

- Approximately **130 g** of filament is required for all printed parts.
- All carbon fiber parts fit within a **100 mm × 200 mm × 1.5 mm** carbon fiber sheet.
- The robot is designed for fast maintenance and easy part replacement between fights.

---

# License

This project is open source.

Feel free to build, modify, and improve the design.
