# Advanced Physical Design using OpenLANE/Sky130

[![Advanced-Physical-Design-using-OpenLANE_Sky130_1](https://user-images.githubusercontent.com/89193562/134464331-c6dbf721-80f0-4efa-98fa-820c485e9373.png)](https://www.vlsisystemdesign.com/advanced-physical-design-using-openlane-sky130/)

## Brief Description of the Workshop

# *Index*

- [Day 1: Inception of open-source EDA, OpenLANE and Sky130 PDK](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#day-1-inception-of-open-source-eda-openlane-and-sky130-pdk)
    - [How to talk to computers](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-1-how-to-talk-to-computers)
        - [Sub-Part 1: Introduction to QFN-48 Package, chip, pads, core, die and IPs](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-1-introduction-to-qfn-48-package-chip-pads-core-die-and-ips)
        - [Sub-Part 2: Introduction to RISC-V](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-2-introduction-to-risc-v)
        - [Sub-Part 3: From Software Applications to Hardware]()

# Day 1: Inception of open-source EDA, OpenLANE and Sky130 PDK

## Part 1: How to talk to computers

### Sub-Part 1: Introduction to QFN-48 Package, chip, pads, core, die and IPs

- The block diagram for the port diagram of the board of Arduino Leonardo should look as follows:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134467899-dd1fdfe0-65c1-45ee-8067-56008061d9f6.JPG" />
</p>

- If we open the chip, it should look something as given below:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134468286-1fefb66d-1acf-460d-867e-faacf61f273e.png" />
</p>

- The dimensions of this chip are 7mm x 7mm.
- The package of this chip is **QFN-48**.
- QFN stands for "Quad Flat No-leads".
- "48" means that the IC has 48 pins. 
- The chip is somewhere at the centre of the package and we will be able to transfer all the signals that are coming from the outside world to the chip.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134478921-05ffc729-d7fe-453f-817f-954137875a83.png" />
</p>

- **Die** is basically the size of the entire chip.
- **Pads** are something through which you can send the signal inside or outside the chip.
- **Core** is a place where all of the digital logic is placed.

- An IP stands for Intellectual Property.
- Macros are something that require pure digital logic and Foundry IPs require some amount of intelligence.

### Sub-Part 2: Introduction to RISC-V

- This is the way in which we are going to talk to the computers.
- This is basically the flow of information from high level language program to the flip-flop level language program (binary language).
- Any high level language is first compiled in its assembly language program.
- This assembly language program is then converted into the machine language program.
- The bits (0s and 1s) of the machine level program get executed in the layout and we get the required output.
- The interface that is required between RISC-V architecture and the layout is the "Hardware Description Language".

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134481931-023bda19-2700-4a6d-b1bb-74f4234322d7.JPG" />
</p>

### Sub-Part 3: From Software Applications to Hardware
