# Transformerless Power Supply PCB

This project is a **Transformerless Power Supply PCB design** created using **KiCad**. The objective of this project is to design a compact AC-to-DC power supply circuit without using a bulky step-down transformer.

> ⚠️ **Safety Warning**
> Transformerless power supplies are **not isolated from AC mains**. This circuit can be dangerous and may cause electric shock if handled incorrectly. This project is intended only for educational PCB design and simulation study. Do not touch, test, or power the circuit directly without proper supervision, isolation, fuse protection, and safety precautions.

---

## Project Overview

A transformerless power supply converts high-voltage AC mains into low-voltage DC using passive components such as capacitors, resistors, diodes, and voltage regulation components. This type of supply is commonly used in low-current applications where compact size and low cost are important.

This PCB was designed to understand:

* AC-to-DC conversion
* Capacitive dropper power supply concept
* Rectification and filtering
* Voltage regulation
* PCB layout design using KiCad
* Electrical safety spacing and component placement

---

## Problem Statement

Traditional transformer-based power supplies are bulky and expensive for small low-power circuits. For compact low-current applications, a transformerless power supply can reduce size and cost.

The goal of this project is to design a PCB for a simple transformerless power supply and understand the practical design considerations involved in AC mains-based circuits.

---

## Features

* Compact PCB design
* Transformerless AC-to-DC conversion
* Capacitive voltage dropping
* Bridge rectifier-based AC rectification
* Filter capacitor for DC smoothing
* Voltage regulation stage
* Designed using KiCad
* Suitable for educational PCB design practice

---

## Tools Used

* KiCad
* Schematic Design
* PCB Layout Design
* Electrical Rule Check
* Design Rule Check
* Git and GitHub for version control

---

## Project Files

```text
Transformerless-Power-supply/
│
├── README.md
├── Transformerless power supply.kicad_pro
├── Transformerless power supply.kicad_sch
├── Transformerless power supply.kicad_pcb
└── .gitignore
```

---

## File Description

| File                                     | Description                                                 |
| ---------------------------------------- | ----------------------------------------------------------- |
| `Transformerless power supply.kicad_pro` | KiCad project file                                          |
| `Transformerless power supply.kicad_sch` | Schematic design file                                       |
| `Transformerless power supply.kicad_pcb` | PCB layout file                                             |
| `.gitignore`                             | Prevents unwanted KiCad temporary files from being uploaded |
| `README.md`                              | Project documentation                                       |

---

## Basic Working Principle

The circuit works in the following stages:

1. **AC Input Stage**
   The circuit receives AC mains input.

2. **Capacitive Dropper Stage**
   A high-voltage capacitor limits the current by capacitive reactance instead of using a transformer.

3. **Rectifier Stage**
   Diodes convert AC into pulsating DC.

4. **Filtering Stage**
   A capacitor smooths the pulsating DC output.

5. **Voltage Regulation Stage**
   A Zener diode or regulator limits the output voltage to a safer fixed DC level.

6. **Output Stage**
   The regulated DC output can be used for very low-current applications.

---

## Applications

* Low-power indicator circuits
* Small control circuits
* LED driver circuits
* Relay trigger circuits
* Educational power supply design study
* PCB design practice for AC circuits

---

## Important Design Considerations

* Maintain proper clearance between AC and DC sections
* Use high-voltage-rated capacitors
* Add fuse protection at input
* Use discharge resistor across dropper capacitor
* Avoid touching the circuit when powered
* Do not connect this circuit directly to USB, laptop, Arduino, ESP32, or any human-accessible device
* Use an isolation transformer while testing
* Enclose the circuit properly if practically implemented

---

## Limitations

* No galvanic isolation from AC mains
* Dangerous for direct human interaction
* Not suitable for high-current loads
* Output current is limited
* Poor safety compared to transformer-based or SMPS designs
* Not recommended for beginner-level live testing

---

## Future Improvements

* Add fuse protection
* Add MOV for surge protection
* Add proper silkscreen safety markings
* Increase PCB clearance for mains voltage
* Add enclosure design
* Add test points
* Add output LED indicator
* Compare with isolated SMPS-based design

---

## Project Status

This is Version 1 of the PCB design. The current focus is on understanding transformerless power supply design, PCB layout practice, and GitHub project documentation.

---

## Author

**Umar Fazil K**
Electronics and Communication Engineering
Madras Institute of Technology, Anna University

GitHub: [umarfazilk](https://github.com/umarfazilk)
LinkedIn: [linkedin.com/in/umarfazilk](https://linkedin.com/in/umarfazilk)

---

## Disclaimer

This project involves AC mains voltage concepts. It is shared only for learning and documentation purposes. The author is not responsible for damage, injury, or unsafe usage caused by practical implementation of this circuit.
