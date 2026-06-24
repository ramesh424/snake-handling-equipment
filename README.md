# Open-Source Cable-Actuated Snake Rescue Tool with Rotation-Assisted Body Winding for Controlled Head Restraint

This repository contains the open-source hardware design files, documentation, bill of materials, assembly instructions, operation protocol, validation data, and demonstration media for a low-cost cable-actuated snake rescue tool.

The tool is designed for long-reach snake handling and prototype-stage evaluation using a flexible dummy snake or rubber tube. The mechanism combines cable-actuated body gripping, spring-assisted jaw reopening, compliant soft-grip jaw pads, and manually controlled working-end rotation. After initial body engagement, the working-end assembly is rotated manually so that the snake body winds around the gripper/shaft region, reducing uncontrolled movement and supporting controlled head-restraint positioning.

> **Important safety note:** This prototype has been validated only using a dummy snake/rubber tube. It is not a field-certified live-snake rescue device. Live-animal use should only be performed by trained snake rescuers or authorized wildlife personnel under applicable ethical approval, local wildlife regulations, and expert supervision.

---

## Repository overview

This project supports open-source replication and further development of a cable-actuated snake rescue tool for trained wildlife rescue and educational demonstration contexts.

The repository includes:

* Editable CAD files
* Printable STL/3MF files
* Bill of materials
* Assembly instructions
* Operation protocol
* Validation dataset
* Rendered figures
* Demonstration media
* License files

---

## Hardware summary

| Field                     | Description                                                                                                                                |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| Hardware name             | Open-source cable-actuated snake rescue tool with rotation-assisted body-winding restraint mechanism and compliant soft-grip jaw interface |
| Subject area              | Wildlife rescue engineering; field safety equipment; humane animal handling; open-source mechanical hardware                               |
| Hardware type             | Long-reach mechanical rescue tool; cable-actuated gripping mechanism; manually rotatable body-winding restraint hardware                   |
| Closest commercial analog | Conventional snake tongs and animal handling poles used for wildlife rescue and reptile handling operations                                |
| Estimated cost            | Approximately INR 2296 per unit, excluding manufacturing scale-up, transportation, and supplier-dependent cost variation                   |
| Hardware license          | CERN Open Hardware Licence Version 2 – Weakly Reciprocal                                                                                   |
| Documentation license     | Creative Commons Attribution 4.0 International                                                                                             |

---

## Key features

* Long-reach aluminium shaft for maintaining operator distance
* Bicycle-style brake lever for simple cable actuation
* Steel cable transmission system
* Spring-return jaw linkage for automatic reopening
* Compliant soft-grip jaw pads for improved contact distribution
* Manually rotatable working-end assembly
* Rotation-assisted body-winding mechanism
* Modular 3D-printed support components
* Low-cost and locally repairable construction
* Open-source design files for replication and modification

---

## Operating principle

The intended functional sequence is:

1. **Approach**
   The operator approaches the snake from a safe distance using the long aluminium shaft.

2. **Initial body grip**
   The working-end jaw is positioned around a suitable body region, and the brake-style trigger is actuated.

3. **Secure body capture**
   The cable-actuated jaw closes using compliant soft-grip pads to hold the dummy snake body.

4. **Working-end rotation**
   The operator manually rotates the working-end assembly about the shaft axis.

5. **Body winding around gripper/shaft region**
   The captured body rotates and winds around the gripper/shaft region.

6. **Controlled head-restraint positioning**
   As body winding progresses, the head is brought into a controlled restrained position during dummy-snake testing.

7. **Spring-assisted release**
   Releasing the trigger allows the spring-return jaw to reopen for controlled release or transfer.

---

## Repository structure

```text
snake-rescue-tool/
│
├── CAD/
│   ├── STEP/
│   ├── STL/
│   └── 3MF/
│
├── BOM/
│   ├── BOM_snake_rescue_tool.csv
│   └── BOM_snake_rescue_tool.xlsx
│
├── Assembly_Instructions/
│   └── assembly_manual.pdf
│
├── Operation_Protocol/
│   └── operation_protocol.pdf
│
├── Validation_Data/
│   ├── validation_dataset.csv
│   └── validation_dataset.xlsx
│
├── Figures/
│   ├── annotated_full_assembly.png
│   ├── multi_view_cad.png
│   ├── exploded_component_layout.png
│   ├── initial_body_engagement.png
│   ├── soft_grip_jaw_closeup.png
│   └── working_end_rotation_test.png
│
├── Demonstration_Media/
│   └── operation_sequence_video.mp4
│
├── LICENSE
├── LICENSE-DOCUMENTATION
└── README.md
```

---

## Design files

The design package includes editable and printable files required to reproduce the tool.

| Design file category               | File types              | Description                                 |
| ---------------------------------- | ----------------------- | ------------------------------------------- |
| Main assembly                      | `.step`, `.stl`, `.3mf` | Complete assembled tool model               |
| Movable jaw/grip component         | `.step`, `.stl`, `.3mf` | Movable gripping component                  |
| Grip back support                  | `.step`, `.stl`         | Rear jaw/grip support part                  |
| Hex back support for grip assembly | `.step`, `.stl`         | Support component for jaw assembly          |
| Insert rod component               | `.step`, `.stl`, `.3mf` | Rod insertion support                       |
| Side-base support                  | `.step`, `.stl`, `.3mf` | Main side-base support                      |
| Side-base angle rod insert         | `.step`, `.stl`         | Angled rod insert support                   |
| Cable-passing support              | `.step`, `.stl`         | Cable guide/support component               |
| Rear cable-passing support         | `.step`, `.stl`         | Rear cable guide component                  |
| Side bolt base                     | `.step`, `.stl`, `.3mf` | Bolt support component                      |
| Support wedge                      | `.step`, `.stl`         | Wedge support part                          |
| Support wedge revision 1           | `.step`, `.stl`         | Revised wedge support part                  |
| Rendered figures                   | `.png`, `.jpg`          | Assembly, operation, and validation figures |
| Demonstration video                | `.mp4`                  | Functional operation demonstration          |

---

## Bill of materials

The estimated fabrication cost is approximately **INR 2296 per unit**.

| Component                               | Quantity | Estimated cost |
| --------------------------------------- | -------: | -------------: |
| Aluminium hollow shaft/tube             |        1 |        INR 350 |
| Angled aluminium handle tube            |        1 |        INR 180 |
| Bicycle brake lever/trigger             |        1 |        INR 250 |
| Steel brake cable                       |        1 |         INR 80 |
| Cable outer housing/Bowden sleeve       |        1 |        INR 100 |
| 3D-printed cable guide/support parts    |        4 |        INR 240 |
| 3D-printed side-base/support parts      |        4 |        INR 280 |
| 3D-printed jaw/grip support parts       |        3 |        INR 195 |
| Stainless steel linkage strips          |        2 |        INR 180 |
| Extension spring for jaw return         |        1 |         INR 45 |
| Soft rubber/TPU gripping pads           |        2 |         INR 80 |
| Pivot bolts, nuts, washers, and spacers |    1 set |        INR 140 |
| Cable stopper/clamp and adjuster        |    1 set |         INR 75 |
| Rear grip/end cap                       |        1 |         INR 70 |
| Adhesive/finishing consumables          |    1 set |         INR 31 |
| **Total**                               |          |   **INR 2296** |

Costs may vary depending on supplier, material grade, 3D-printing method, and local availability.

---

## Assembly overview

The tool is assembled in seven stages:

1. Preparation of fabricated and printed parts
2. Main shaft assembly
3. Operator handle and trigger assembly
4. Cable-routing assembly
5. Working-end jaw and rotating mechanism assembly
6. Final cable tensioning and alignment
7. Functional checking before validation

Detailed build instructions are provided in the `Assembly_Instructions/` folder.

---

## Validation summary

Prototype-stage mechanical validation was performed using a flexible dummy snake/rubber tube. No live snakes were used during the reported validation.

| Validation parameter                      | Result     |
| ----------------------------------------- | ---------- |
| Maximum jaw opening                       | 72 mm      |
| Minimum jaw gap after trigger pull        | 8 mm       |
| Soft pad contact width                    | 18 mm      |
| Average grip force                        | 7.06 N     |
| Trigger travel                            | 36 mm      |
| Cable displacement at working end         | 24 mm      |
| Trigger force required for jaw closure    | 12 N       |
| Maximum working-end rotation angle        | 360°       |
| Practical rotation range for body winding | 180°–270°  |
| Average release time                      | 0.80 s     |
| Trigger open-close cycles completed       | 100 cycles |
| Working-end rotation cycles completed     | 50 cycles  |

The validation confirmed the intended prototype operation sequence: cable-actuated initial body grip, secure body capture, spring-assisted jaw reopening, working-end rotation, body winding around the gripper/shaft region, controlled head-restraint positioning, and controlled release.

The results should be interpreted as prototype-stage mechanical characterization, not live-animal field performance validation.

---

## Safety and ethics

No live snakes were used during the prototype-stage validation reported for this project. All functional tests were performed using a flexible dummy snake/rubber tube to avoid animal stress, injury risk, and unnecessary live-animal handling during early-stage hardware development.

This tool is intended only for:

* trained snake rescuers,
* authorized wildlife personnel,
* supervised research demonstrations,
* educational prototype testing.

This tool should not be used by untrained individuals for live-snake handling. Any future live-snake evaluation should be conducted only under applicable institutional ethical approval, local wildlife regulations, and supervision by trained snake-handling experts.

---

## Limitations

The current prototype is an early-stage open-source hardware platform and should not be interpreted as a field-certified live-snake rescue device.

Key limitations include:

* Validation was performed using a dummy snake/rubber tube, not live snakes.
* Live-snake muscular resistance, defensive movement, surface friction, and strike behavior were not evaluated.
* Grip force depends on trigger input, cable tension, jaw geometry, and pad compliance.
* A calibrated mechanical force-limiting mechanism has not yet been integrated.
* The body-winding behavior may vary with snake size, body diameter, flexibility, surface texture, and environmental conditions.
* 3D-printed components require further durability testing.
* Cable wear, cable stretch, and tension loss require long-term evaluation.

Future work should include calibrated force limitation, improved working-end rotation locking, stronger cable-routing protection, expanded durability testing, ergonomic assessment, cleaning/disinfection evaluation, and controlled testing by trained handlers.

---

## Recommended citation

If you use or adapt this hardware design, please cite the related manuscript and Zenodo archive.

```text
Reddy, R. Open-Source Cable-Actuated Snake Rescue Tool with Rotation-Assisted Body Winding for Controlled Head Restraint. HardwareX manuscript under preparation.
```

After Zenodo upload, replace the above with:

```text
Reddy, R. Open-Source Cable-Actuated Snake Rescue Tool with Rotation-Assisted Body Winding for Controlled Head Restraint. Zenodo. DOI: [insert DOI]
```

---

## Licenses

Hardware design files are released under:

**CERN Open Hardware Licence Version 2 – Weakly Reciprocal (CERN-OHL-W v2)**

Documentation, figures, bill of materials, validation data, and demonstration media are released under:

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

See the `LICENSE` and `LICENSE-DOCUMENTATION` files for details.

---

## Contact

For questions, feedback, or collaboration, please contact:

**Author:** [insert author name]
**Email:** [insert email address]
**Repository:** [insert GitHub repository URL]
**Zenodo DOI:** [insert Zenodo DOI]
