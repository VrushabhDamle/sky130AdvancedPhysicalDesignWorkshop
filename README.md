# Advanced Physical Design using OpenLANE/Sky130

[![Advanced-Physical-Design-using-OpenLANE_Sky130_1](https://user-images.githubusercontent.com/89193562/134464331-c6dbf721-80f0-4efa-98fa-820c485e9373.png)](https://www.vlsisystemdesign.com/advanced-physical-design-using-openlane-sky130/)

## Brief Description of the Workshop

# *Index*

- [Day 1: Inception of open-source EDA, OpenLANE and Sky130 PDK](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#day-1-inception-of-open-source-eda-openlane-and-sky130-pdk)
    - [How to talk to computers](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-1-how-to-talk-to-computers)
        - [Sub-Part 1: Introduction to QFN-48 Package, chip, pads, core, die and IPs](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-1-introduction-to-qfn-48-package-chip-pads-core-die-and-ips)
        - [Sub-Part 2: Introduction to RISC-V](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-2-introduction-to-risc-v)
        - [Sub-Part 3: From Software Applications to Hardware](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-3-from-software-applications-to-hardware)
    - [Part 2: SoC design and OpenLANE](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-2-soc-design-and-openlane)
        - [Sub-Part1: Introduction to all components of open-source digital asic design](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part1-introduction-to-all-components-of-open-source-digital-asic-design)
        - [Sub-Part 2: Simplified RTL2GDS flow](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-2-simplified-rtl2gds-flow)
        - [Sub-Part 3: Introduction to OpenLANE and Strive chipsets](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-3-introduction-to-openlane-and-strive-chipsets)
        - [Sub-Part 4: Introduction to OpenLANE detailed ASIC design flow]()
- [References](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#references)

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

- To run a software on the given hardware:
    - Application software enters into the system software.
    - System software converts the application program in the binary language.
- The components of the system software are:
    - Operating System (OS)
    - Compiler
    - Assembler

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134483547-bee84ad2-2b26-4624-8c9b-8811baba5724.JPG" />
</p>

- Job of the OS is to:
    - Handle Input-Output operations
    - Allocate memory
    - Low-level circuit functions
- The job of the compiler is to convert high level language programs to the hardware's understandable language/instructions.
- The job of the assembler is to take the instructions and convert it into binary language (0s and 1s).
- The instructions act as an abstract interface between software and hardware. This is known as instruction set architecture or architecture of computer.
- We need an RTL which implements the instruction set and synthesizes it to the gate level.
- Gate level is converted into respective layout based on the RTL.

## Part 2: SoC design and OpenLANE

### Sub-Part1: Introduction to all components of open-source digital asic design

- "ASIC" stands for Application specific integrated circuits.
- The digital ASIC design elements are:
    - RTL IPs (Hardware Description Language and Register Transfer Level models)
    - EDA Tools
    - PDK Data

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134486394-8526e296-7605-4491-b996-037853ce93fd.JPG" />
</p>

- PDK is the interface between the FAB and the designers.
- PDK stands for "Process Design Kit".
- PDK is a collection of files used to model a fabrication process for the EDA tools used to design an IC.

## Sub-Part 2: Simplified RTL2GDS flow

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134488123-eb564ad3-c0db-48d5-916b-a59439c10727.JPG" />
</p>

- **Synthesis**:
    - Converts RTL to a circuit out of components from the standard cell library (SCL).
    - Standard cells have regular layout.
    - Each has different views/models.
- **Floor planning and Power planning**:
    - Partition the chip die between different system building blocks and place the Input-Output pads.
    - **Macro Floor planning**: Dimensions, pin locations, row definitions.
    - Power network is constructed.
    - Typically chip is powered by multiple Vdd and Gnd fence.
    - The power fence are connected to all components through vertical and horizontal metal straps.
    - Parallel structures are meant to reduce resistance.
    - Typically the power distribution network uses upper metal layers as they are thicker than lower metal layers hence have less resistance.
- **Placement**:
    - Place the cells on the floor plan rows, aligned with the sites.
    - Placement is usually done in two steps: Global and Detailed.
    - Global placement tries to find optimal placement for all cells. Such positions are not necessarily legal so cells may overlap.
    - In Detailed placement, the positions obtained from global placement are minimally altered to be legal.
- **Clock Tree Synthesis**:
    - Create a clock distribution network.
    - Clock skew means arrival of the clock to different components at different times.
- **Routing**:
    - Implement the interconnect using available metal layers.
    - Metal tracks form a routing grid.
    - Routing grid is huge.
    - Divide and Conquer technique is used:
        - Global Routing: Generates routing guides.
        - Detailed Routing: Uses the routing guides to implement the actual wiring.
- **Sign Off**:
    - Physical Verification which has two steps:
        - Design Rules Checking (DRC)
        - Layout Versus Schematic (LVS)
    - Timing Verification which includes:
        - Static Timing Analysis (STA)

### Sub-Part 3: Introduction to OpenLANE and Strive chipsets

- To develop and open-source ASIC flow we need to know about \-
    - Tools qualification
    - Tools calibration
    - Missing Tools
- **OpenLANE** started as an open-source flow for a true open-source tape-out experiment.
- "striVe" is a family of open everything SoCs.
- Open everything means open PDK, open EDA and open RTL.

- **OpenLANE's Main Goal**: Produce a clean GDSII with no human intervention (no-human-in-the-loop).
- Clean means:
    - No LVS violations
    - No DRC violations
    - No Timing Violations
- OpenLANE is used for Sky130nm open PDK but it also supports XFAB150 and GF130G.
- It is containerized:
    - Functionally out of the box.
    - Instructions to build and run natively will follow.
- It can be used to harden Macros and Chips.
- It has two modes of operation:
    - Autonomous mode
    - Interactive mode
- It supports Design Space Exploration (find the best set of flow configurations).
- It has a large number of design examples.

### Sub-Part 4: Introduction to OpenLANE detailed ASIC design flow

# References
