<img width="522" height="517" alt="image" src="https://github.com/user-attachments/assets/82712a02-92ca-4929-969c-94ab4c7daa2a" /># CN3791 MPPT Solar Charger Controller – KiCad Library

Custom KiCad symbol and PCB footprint library for the CN3791 MPPT solar charger controller module.

This library was created because accurate KiCad symbols and footprints for the CN3791 module were not publicly available.

---

## Features

- Custom schematic symbol
- Custom PCB footprint
- Pin mapping verified
- Ready for KiCad 7 / KiCad 8
- Open-source and free to use

---

## Module Specifications

| Parameter | Value |
|---|---|
| Controller IC | CN3791 |
| Input Voltage Range | 4.5V – 28V |
| Recommended Solar Panel Range | 6V – 15V |
| Maximum Charging Current | Up to 2A |
| Application | MPPT Solar Charging |

---

## Repository Structure

```text
Symbol/          → KiCad schematic symbol
Footprint/       → KiCad PCB footprint
Example_Project/ → Example implementation
Datasheet/       → Reference datasheet
Images/          → Preview images
```

---

## Preview

### Module
<img width="796" height="735" alt="image" src="https://github.com/user-attachments/assets/47c7600f-f7a4-43f6-9827-3fceca940d58" />

### Schematic Symbol

<img width="699" height="369" alt="image" src="https://github.com/user-attachments/assets/9c6a5e80-c59a-4812-8525-b654c17b7f49" />

### PCB Footprint

<img width="779" height="639" alt="image" src="https://github.com/user-attachments/assets/a0c827d0-cf76-46d1-8db7-50b6e49f513f" />

---

## Installation

### Symbol Installation

1. Open KiCad
2. Go to:
   Preferences → Manage Symbol Libraries
3. Add:
   `CN3791.kicad_sym`

### Footprint Installation

1. Open KiCad
2. Go to:
   Preferences → Manage Footprint Libraries
3. Add:
   `CN3791.pretty`

---

## Verification

The footprint dimensions and pin mappings were created and verified manually using:
- Module measurements
- Datasheet references
- PCB inspection

---

## License

This project is released under the MIT License.

---

## Author

Created by Abdallah Mohamed abdallah

GitHub:
(Add GitHub link later)

LinkedIn:
https://www.linkedin.com/in/abdallah-mohamed-67a639265/?skipRedirect=true
