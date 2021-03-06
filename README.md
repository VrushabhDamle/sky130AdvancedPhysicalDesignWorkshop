# Advanced Physical Design using OpenLANE/Sky130

[![Advanced-Physical-Design-using-OpenLANE_Sky130_1](https://user-images.githubusercontent.com/89193562/134464331-c6dbf721-80f0-4efa-98fa-820c485e9373.png)](https://www.vlsisystemdesign.com/advanced-physical-design-using-openlane-sky130/)

## Brief Description of the Workshop

# *Index*

- [Advanced Physical Design using OpenLANE/Sky130](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#advanced-physical-design-using-openlanesky130)
    - [Brief Description of the Workshop](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#brief-description-of-the-workshop)
- [Day 1: Inception of open-source EDA, OpenLANE and Sky130 PDK](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#day-1-inception-of-open-source-eda-openlane-and-sky130-pdk)
    - [How to talk to computers](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-1-how-to-talk-to-computers)
        - [Sub-Part 1: Introduction to QFN-48 Package, chip, pads, core, die and IPs](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-1-introduction-to-qfn-48-package-chip-pads-core-die-and-ips)
        - [Sub-Part 2: Introduction to RISC-V](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-2-introduction-to-risc-v)
        - [Sub-Part 3: From Software Applications to Hardware](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-3-from-software-applications-to-hardware)
    - [Part 2: SoC design and OpenLANE](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-2-soc-design-and-openlane)
        - [Sub-Part1: Introduction to all components of open-source digital asic design](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part1-introduction-to-all-components-of-open-source-digital-asic-design)
        - [Sub-Part 2: Simplified RTL2GDS flow](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-2-simplified-rtl2gds-flow)
        - [Sub-Part 3: Introduction to OpenLANE and Strive chipsets](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-3-introduction-to-openlane-and-strive-chipsets)
        - [Sub-Part 4: Introduction to OpenLANE detailed ASIC design flow](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-4-introduction-to-openlane-detailed-asic-design-flow)
    - [Part 3: Get familiar to open-source EDA tools](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-3-get-familiar-to-open-source-eda-tools)
        - [Sub-Part 1: OpenLANE Directory structure in detail](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-1-openlane-directory-structure-in-detail)
        - [Sub-Part 2: Design Preparation Step](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-2-design-preparation-step)
        - [Sub-Part 3: Review files after design prep and run synthesis](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-3-review-files-after-design-prep-and-run-synthesis)
        - [Sub-Part 4: OpenLANE Project Git Link Description](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-4-openlane-project-git-link-description)
        - [Sub-Part 5: Steps to characterize synthesis results](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-5-steps-to-characterize-synthesis-results)
            - [MCQ questions solutions](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#mcq-questions-solutions)
- [Day 2: Good floorplan vs bad floorplan and introduction to library cells](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#day-2-good-floorplan-vs-bad-floorplan-and-introduction-to-library-cells)
    - [Part 1: Chip Floor planning considerations](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-1-chip-floor-planning-considerations)
        - [Sub-Part 1: Utilization factor and aspect ratio](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-1-utilization-factor-and-aspect-ratio)
        - [Sub-Part 2: Concept of pre-placed cells](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-2-concept-of-pre-placed-cells)
        - [Sub-Part 3: De-coupling capacitors](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-3-de-coupling-capacitors)
        - [Sub-Part 4: Power planning](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-4-power-planning)
        - [Sub-Part 5: Pin placement and logical cell placement blockage](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-5-pin-placement-and-logical-cell-placement-blockage)
        - [Sub-Part 6: Steps to run floorplan using OpenLANE](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-6-steps-to-run-floorplan-using-openlane)
            - [MCQ questions solutions](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#mcq-questions-solutions-1)
        - [Sub-Part 7: Review floorplan files and steps to view floorplan](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-7-review-floorplan-files-and-steps-to-view-floorplan)
        - [Sub-Part 8: Review floorplan layout in Magic](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-8-review-floorplan-layout-in-magic)
    - [Part 2: Library Binding and Placement](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-2-library-binding-and-placement)
        - [Sub-Part 1: Netlist binding and initial place design](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-1-netlist-binding-and-initial-place-design)
        - [Sub-Part 2: Optimize placement using estimated wire-length and capacitance](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-2-optimize-placement-using-estimated-wire-length-and-capacitance)
        - [Sub-Part 3: Final placement optimization](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-3-final-placement-optimization)
        - [Sub-Part 4: Need for libraries and characterization](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-4-need-for-libraries-and-characterization)
        - [Sub-Part 5: Congestion aware placement using RePlAce](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-5-congestion-aware-placement-using-replace)
    - [Part 3: Cell design and characterization flows](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-3-cell-design-and-characterization-flows)
    - [Part 4: General timing characterization parameters](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-4-general-timing-characterization-parameters)
- [Day 3: Design library cell using Magic Layout and ngspice characterization](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#day-3-design-library-cell-using-magic-layout-and-ngspice-characterization)
    - [Part 1: Labs for CMOS inverter ngspice simulations](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-1-labs-for-cmos-inverter-ngspice-simulations)
        - [Sub-Part 1: IO placer revision](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-1-io-placer-revision)
        - [Sub-Part 2: SPICE deck creation for CMOS inverter](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-2-spice-deck-creation-for-cmos-inverter)
        - [Sub-Part 3: SPICE simulation lab for CMOS inverter](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-3-spice-simulation-lab-for-cmos-inverter)
        - [Sub-Part 4: Switching Threshold Vm](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-4-switching-threshold-vm)
        - [Sub-Part 5: Lab steps to git clone vsdstdcelldesign](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#sub-part-5-lab-steps-to-git-clone-vsdstdcelldesign)
    - [Part 2: Inception of Layout and CMOS fabrication process](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-2-inception-of-layout-and-cmos-fabrication-process)
    - [art 3: Sky130 Tech File Labs](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#part-3-sky130-tech-file-labs)
- [References](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#references)

# Day 1: Inception of open-source EDA, OpenLANE and Sky130 PDK

On the first day of the workshop, we learnt about the method in which an integrated circuit talks to a computer. We also looked into the steps that are required for a computer to talk to an IC. We also saw the RISC-V architecture and the flow from a high-level language program to a binary level program. Later on, we also saw the RTL2GDS flow. Finally, the day ended with us performing a synthesis run on an example design of "picorv32a".

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

[![openlane flow 1](https://user-images.githubusercontent.com/89193562/134491745-59fc8e15-77c5-4e9a-8065-4bea5f723b2b.png)](https://github.com/efabless/OpenLane)

- The flow starts with RTL synthesis so the RTL is fed to "Yosys" with the design constraints.
- Yosys translates the RTL into a logical circuit using generic components.
- This circuit can be optimized and then mapped in to cells using "abc".
- ABC has to be guided during the optimization and this guidance comes in the form of abc synthesis strategies.
- Synthesis exploration utility is used to generate a report that shows how the design delay and area is affected by the synthesis strategy.
- Based on this exploration we can choose the best strategy to continue with.
- Design exploration utility can be used to sweep the design configurations.
- It generates a report which shows different design matrix and number of violations generated after generating the final layout.
- **OpenLANE Regression Testing**:
    - The design exploration utility is also used for Regression Testing.
    - We run openLANE on ~70 designs and compare the results to the best known ones.
- Design for Test (DFT) includes:
    - Scan Insertion
    - Automatic Test Pattern Generation (ATPG)
    - Test Patterns Compaction
    - Fault Coverage
    - Fault Simulation
- Physical Implementation (also called automated PnR (Place and Route)) includes the following:
    - Floor planning and Power planning
    - End Decoupling capacitors and Tap Cells insertion
    - Placement: Global and Detailed
    - Post placement optimization
    - Clock Tree Synthesis (CTS)
    - Routing: Global and Detailed
- Logical Equivalence Check (LEC):
    - Everytime the netlist is modified, verification must be performed:
        - CTS modifies the netlist
        - Post placement optimization modifies the netlist
    - LEC is used to formally confirm that the function did not change after modifying the netlist.
- Dealing with Antenna Rules Violations:
    - When a metal wire segment is fabricated, it can act as an antenna.
        - Reactive ion etching causes charge to accumulate on the wire.
        - Transistor gates can be damaged during fabrications.
    - Two solutions are possible:
        - Bridging attaches a higher layer intermediately (requires router awareness).
        - Add antenna diode cell to leak away charges (antenna diodes are provided by the SCL)
    - We take a preventive approach:
        - Add a fake antenna diode next to every cell input after placement.
        - Run the antenna checker (magic) on the routed layout.
        - If the checker reports a violation on the cell input pin, replace the fake diode cell by a real one.
- Static Timing Analysis:
    - The tool used for STA is OpenSTA.
- Physical Verification DRC and LVS:
    - Magic is used for Design Rule Checking and spice extraction from layout.
    - Magic and Netgen are used for LVS (extracted spice by magic versus verilog netlist)

## Part 3: Get familiar to open-source EDA tools

### Sub-Part 1: OpenLANE Directory structure in detail

- Go to the directory having the openLANE files from the terminal using the "cd" command.
- Use the command `ls -ltr` to list everything in a chronological order.
- Open_pdk is a set of scripts and files that convert the foundry level PDKs to be compatible with the open source EDA tools.
- Enter the reference libraries folder using the "cd" command and observe "sky130_fd_sc_hd"
    - "fd" is the abbreviated foundry name.
    - "sc" is standard cell
    - "hd" is the variant of the PDK (here high density).

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134495519-9405137b-fe55-484d-a329-5fee1a1453df.JPG" />
</p>

- "techlef file contains the layer information.
- All the timing files for the process corners are in the lib directory.

### Sub-Part 2: Design Preparation Step

- Run docker using the command `docker`.
- This should run the docker application in the terminal.
- First type the command `pwd` on the terminal and then type the command `ls -ltr`
- Now, we have to run the flow.tcl file in an interactive manner so type the command `./flow.tcl -interactive`.
- The terminal should look as follows:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134505217-451655ed-2538-4856-bc63-01ccf0743fac.JPG" />
</p>

- Type the command `package require openlane 0.9` as:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134505348-8ac9edfb-292f-493b-9b9c-a8130a783ed2.JPG" />
</p>

- Open another terminal and enter in the "designs/picorv32a" directory using the "cd" command.
- In this folder, we have:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134505804-fdbd78f8-9393-44e2-a4f9-53ead37b16d5.JPG" />
</p>

- Return to the terminal that is having the openLANE open in it.
- Type the command `prep -design picorv32a`.
- In the terminal it should look like:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134506076-61bd239d-7442-4d8a-8502-b91cc1677a5e.JPG" />
</p>

### Sub-Part 3: Review files after design prep and run synthesis

- Now in the terminal that we had used to access the directory "picorv32a", there should be a runs folder that should have appeared in the folder.
- Enter into this runs folder using "cd" command.
- There should be a folder created with the date (in this case 23_09 as this was executed on 23 september 2021) and within this folder should be a tmp folder. Access it using the "cd" command.
- It should look like:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134506801-69e24dee-b6e9-4916-a8e7-4c674a7010d9.JPG" />
</p>

- The "merged.lef" file was created by the "prep" command in the previous sub-part.
- In the openLANE terminal, run the synthesis using the command `run_synthesis`.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134507340-5d07c074-8724-479b-8c70-a1abd84c2c90.JPG" />
</p>

### Sub-Part 4: OpenLANE Project Git Link Description

- GitHub is a remote repository collection.
- To get the files from the [openLANE directory](https://github.com/The-OpenROAD-Project/OpenLane) into your computer, perform the following steps:
    - Install git commands in the terminal using the command `sudo apt-get install git`.
    - Now copy the address of the git file and use the command `git clone https://github.com/The-OpenROAD-Project/OpenLane.git`

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134508798-fa5f751d-a4cb-4c54-b419-fce1c169ff84.JPG" />
</p>

### Sub-Part 5: Steps to characterize synthesis results

- The synthesis run has been completed in the sub-part 3.
- The chip area that we receive is:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134510414-5d382ceb-fbcf-42cd-a03e-d8ed650c5165.JPG" />
</p>

- Flop ratio is the ratio of total number of D flip-flops to the total number of cells.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134509767-f9241138-cbc5-48d9-84e7-48a1bdca3b07.JPG" />
</p>

- So in this case the number of D flip-flops that we have are:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134509872-83ffbf3f-35b6-4fed-8766-9a06da4b257b.JPG" />
</p>

- Total number of cells that we have are:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134509953-52e79bb9-60cd-46eb-a1a6-3e4a364aa0bc.JPG" />
</p>

- Hence, the flop ratio comes out to be: ~0.1084

#### MCQ questions solutions

- For the question regarding flop ratio of picorv32a, we have already calculated it to be ~0.1084
- For the question regarding buffer ratio, from the flop ratio formula, we can say that:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134510876-4871d5f3-e2e0-43a3-8ecd-0973f542c7ca.JPG" />
</p>

- Total number of buffers in the circuit are:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134511007-a8b1f7b6-83e6-4c97-8f1b-e5df6a28b637.JPG" />
</p>

- Hence total number of buffers are: 1664
- We have the total number of cells to be 14876
- Therefore, the buffer ratio comes out to be ~0.1118

# Day 2: Good floorplan vs bad floorplan and introduction to library cells

On the second day of the workshop, we started the discussion with the chip floor planning considerations which consisted of the utilization factor, aspect ratio, concept of pre-placed cells, de-coupling capacitors, power planning and pin placement. We also discussed about netlist binding and optimization of placement of the components. Finally, we also had a look on the cell design and characterization flows.

## Part 1: Chip Floor planning considerations

### Sub-Part 1: Utilization factor and aspect ratio

- Lets begin with a netlist

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134618895-f46f656d-70c2-4197-b578-57387622eef6.JPG" />
</p>

- FF = Flip-Flops/Latches/Registers
- A1,O1 = Standard cells (AND, OR, INVERTER)
- Consider a netlist with 2 flip flops and 2 gates, with above shown connections.
- A "netlist" describes the connectivity of an electronic design.
- While defining the dimensions of the chip, we are mostly dependant on the dimensions of the logic gates.
- Now, lets convert the gates symbols into physical dimensions.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134619788-1186773b-a6e3-44e2-ac75-3620ceb19729.JPG" />
</p>

- Lets say that the standard cells are given a dimension of 1unit x 1unit. So, the area of all the standard cells would be 1 sq. unit.
- Lets assume same area for flip-flops as well.
- Area occupied by the netlist would be the area of the standard cells added to the area of the flip-flops.
- So the area occupied by the netlist would be 4 sq. units.
- Now, when this netlist is placed on the "core", it will occupy more area because we have to route layers between them.
- Therefore, utilization factor becomes:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134620292-e3eb3040-e2ea-42f6-821a-fbf561fc1542.JPG" />
</p>

- The aspect ratio is:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134620459-fb8cebda-ee9e-4dbf-9884-172afe99d0a6.JPG" />
</p>

- An aspect ratio of "1" signifies that the package is a square package.

### Sub-Part 2: Concept of pre-placed cells

- If we consider a combinational logic circuit and cut it, then we have two seperate circuits and the connectivity information between them.
- These two circuits can be placed as two seperate blocks that will be implemented seperately.
- We take the two blocks independently and extend the Input-Output pins.
- Now, black box the blocks and detach them.
- Now, the two blocks will be implemented seperately.
- The advantage of doing this is that if a block is being used multiple times, then we don't need to implement them repeatedly. We can just black box them and then the circuit can be implemented multiple times. It can basically be reused.
- Similarly, there are other IPs available:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134621160-e78b524a-f979-4a90-9968-92ca510aff04.JPG" />
</p>

- This need not be implemented multiple times as it is a part of the top level netlist and the functionality of a particular cell will be implemented only once.
- The arrangement of these IPs in a chip is referred to as Floorplanning.
- These IPs/blocks have user defined locations and hence, they are placed in a chip before automated placement-and-routing and thus they are called pre-placed cells.
- Automated placement-and-routing tools place the remaining logical cells in the design on the chip.
- Pre-placed cells have to be placed in such a fashion that once they are placed, their locations cannot be changed.

### Sub-Part 3: De-coupling capacitors

- Consider the amount of switching current required for a complex circuit.
- Consider capacitance to be zero for the discussion. Rdd, Rss, Ldd, and Lss are well defined values.
- During switching operation, the circuit demands switching current i.e. peak current (Ipeak).
- Now, due to the presence of Rdd and Ldd, there will be a voltage drop across them and the voltage drop across them and the voltage at node 'A' would be Vdd' instead of Vdd.
- If Vdd' goes below the noise margin then due to Rdd and Ldd, the logic '1' at the output of the circuit won't be detected as logic '1' at the input of the the circuit following this circuit.
- The solution to this problem is to add a de-coupling capacitor.
- Addition of decoupling capacitors is done in parallel with the circuit.
- Everytime the circuit switches, it draws current from Cd (decoupling capacitor), whereas the RL network is used to replenish the charge into Cd.
- De-coupling capacitor decouples the circuit from the main power supply.

### Sub-Part 4: Power planning

- We have taken care of local communication by using the de-coupling capacitor.
- Now, if the decoupled circuit is black boxed and repeated multiple times.
- The connection between two blocks is not decoupled and the power supply is sitting at a far distance from this line. So, there is always a possibility of voltage drop.
- If we consider a 16 bit bus and pass it through an inverter.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134622669-c0347ce5-6081-4e07-8019-8e6b2b9d08c8.JPG" />
</p>

- This means, all capacitors which were charged to 'V' volts have to discharge to '0' volts through a single "ground" tap point. This will cause a bump in the "ground" tap point and this is called as "Ground Bounce".
- Also, all capacitors which were not charged have to charge to 'V' volts through a single "Vdd" tap point. This will cause a drop in the "Vdd" tap point and this is called as "Voltage Droop".
- To counter the issues faced, we use a grid pattern and supply power from multiple places. We have Vdd and Vss lines forming a mesh.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134623955-2abf6b0a-6d01-4b28-b015-b4f962ae54c7.JPG" />
</p>

### Sub-Part 5: Pin placement and logical cell placement blockage

- The connectivity information between the gates is coded using VHDL/Verilog Language and is called as "netlist".
- The ordering of input and output ports is random and the reason is the cell placement.
- Clock ports are bigger than data ports because the clock is the port which is driving all of the cells continuously.
- We need least resistance for clock ports as bigger size means lower resistance.
- We also add a logical cell placement covering the port area so that no cells are placed in this region.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134625512-b69d7d9f-fc1a-4073-a2fa-ae00d462a2c5.png" />
</p>

- Now the overall package should look like:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134646117-84ae7ed0-89f9-495b-952b-d244ecc3f93d.png" />
</p>

### Sub-Part 6: Steps to run floorplan using OpenLANE

- To run the floorplan we need to type the command `run_floorplan` after the synthesis is complete

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134626262-d7db01ad-afb1-4d15-b09c-96eb079c2a64.JPG" />
</p>

- To check the floorplanning information, go to the "configuration" folder in openlane using the "cd" command and type the command `less README.md` in the terminal.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134626453-8529df90-8d92-45f7-9691-e8271459865c.JPG" />
</p>

- When we scroll down the floorplan information should look like:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134626516-6ba4e916-b28b-466e-b408-956d73df4d08.JPG" />
</p>

#### MCQ questions solutions

- Setting the FP_IO_VMETAL switch sets the Vertical metal layer.
- Precedence order of floorplan configuration setting for a design is: sky130A_sky130_fd_sc_hd_config.tcl>config.tcl>floorplan.tcl

### Sub-Part 7: Review floorplan files and steps to view floorplan

- To review the file created from running the floorplan command, go to the runs directory using the "cd" command and go further into the floorplan directory.
- Use `ls -ltr` command to check available files.
- Open the file "4-ioPlacer.log" using the "less" command

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134636784-aee5a372-e900-4f8d-96b3-9701cb8e85d5.JPG" />
</p>

- When opened the file looks as follow:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134636977-8db00910-cd3d-4115-96f5-309a66f41087.JPG" />
</p>

- Now go to the "results/floorplan" directory and use the command `ls -ltr` to check the contents of this directory.
- Open the file "picorv32a.floorplan.def" using the "less" command.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134637538-55fba3c3-a2e8-4342-9e95-11eadec53235.JPG" />
</p>

- When opened the file looks as follow:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134637595-112ac2f1-deda-4547-a65e-a091446bfa5f.JPG" />
</p>

- The `DIEAREA ( 0 0 ) ( 660685 671405 ) ;` gives us the co-ordinates of the left bottom corner and right top corner of the chip.
- The `UNITS DISTANCE MICRONS 1000 ;` says that one micron equals thousand database units.

- Exit it by pressing "Q" button on the keyboard.
- Open the "merged.lef" file in magic using the command `magic -T /home/vrushabh/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.floorplan.def &`

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134638980-cae7c90e-5fc9-4898-a98b-7cb46acc5d6b.JPG" />
</p>

- When the magic terminal opens it looks as follows:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134639167-863e469f-7b00-4940-a9f6-4db2760eaa02.JPG" />
</p>

### Sub-Part 8: Review floorplan layout in Magic

- We will move the floorplan to the centre of the window.
- To select it, press "S" button on the keyboard.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134639762-1d8135db-831c-4edc-a56b-e518d07b8122.JPG" />
</p>

- Now to move it to the centre press "V" button on the keyboard.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134639806-e1d141be-4ded-4609-bc40-fc4df816aeb3.JPG" />
</p>

- To zoom in on a particular area form a box around that area.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134639971-c984b113-ced4-44ce-b88f-cfdb5a00bc78.JPG" />
</p>

- Now press "Z" button on the keyboard

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134640199-c77b932b-458d-4e13-bf0d-f3bd3642e2ef.JPG" />
</p>

- We can see that the input-output pins are equidistant from each other.
- To see what layer the input-output pins of the horizontal part are on, select one pin by moving the cursor over it and pressing the "S" button on keyboard.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134640617-ee8b99f2-8bdf-4829-9413-90c62b2ddb47.JPG" />
</p>

- Now, in the command window, type `what`:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134640717-e37682bd-2a19-48cd-8b7b-ccd1ddab0cdd.JPG" />
</p>

- We can see that the input-output pins are on metal3 layer which is what we had set.
- To see what layer the input-output pins of the vertical part are on, select one pin by moving the cursor over it and pressing the "S" button on keyboard.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134641044-22a9b3d8-e3af-4de7-bb35-8b49b0485f54.JPG" />
</p>

- Now, in the command window, type `what`:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134641082-1addea87-e7f5-4d56-ba0b-2b910e032315.JPG" />
</p>

- We can see that the input-output pins are on metal2 window as we had set.
- Tap cells are basically meant to avoid the latch-up conditions which occur in the CMOS devices. 
- So, N-well is connected to Vdd and substrate is connected to the ground.
- The tap cells are diagonally equidistant.
- The standard cells are present at the left bottom corner of the design.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134641803-1c089671-78aa-4b1a-8f4b-244e89ec9f1c.JPG" />
</p>

## Part 2: Library Binding and Placement

### Sub-Part 1: Netlist binding and initial place design

- Let us consider the following floorplan:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134652585-cd39929d-a821-4e32-adce-bc2377717ceb.JPG" />
</p>

- The first and foremost step is to bind the netlist with the physical cells.
- Basically, we convert the symbols of the components in real world shapes (boxes).
- Library is a place where all the standard cells are present.
- The library also has the timing information of the cells.
- A library will have the following information:
    - Width and Height of each cell.
    - Delay information of each and every cell.
    - Required conditions of every cell.
- Library also provides options/alternatives for a cell.
- A bigger standard cell has lower resistance and hence, it is faster.

- In placement stage, we do not move the pre-placed cells and the de-coupling capacitors.
- No cells should overlap with the pre-placed cells.

- For the first two flip-flop lines the placement could be like:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134648514-2b8e104a-5c70-457c-8a84-676600aaa457.png" />
</p>

### Sub-Part 2: Optimize placement using estimated wire-length and capacitance

- After placement of the third and fourth combinational logic the cirucit shall look like:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134653731-31e8ea37-1475-4fc3-8251-7b1e4b97812a.png" />
</p>

- We estimate the wire length and capacitance and based on that, insert repeaters.
- Distance of input pins from "brown" flip-flop is huge and the wire inserted between them will have a huge capacitance and resistance.
- We solve this problem of signal integrity due to huge wire length by adding repeaters but it causes a loss of area available in the core.
- Slew is a quantity dependant on the value of the capacitance of the wire.

### Sub-Part 3: Final placement optimization

- The brown flip-flop 1 and block 1 are very close to each other so there is no problem in reproducing the signal generated by the flip-flop.
- The blocks are placed so close to each other in high operating frequency circuits.

### Sub-Part 4: Need for libraries and characterization

- Typical IC design flow:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134658801-07d38185-504b-40e9-bf47-e6b2bd53d47a.JPG" />
</p>

- **Logic Synthesis**: Arrangement of gates that will represent the original signal functionality described by the RTL.
- **Floor Planning**: We import the output of the logic synthesis and decide the size of core and  die.
- **Placement**: We take the particular logic cells present in the netlist and place it on the chip in such a fashion that initial timing is met.
- **Clock Tree Synthesis**: The clock is being spread across the logic cells at an equal time. Clock buffers will take care that the signal has equal rise and fall time.

### Sub-Part 5: Congestion aware placement using RePlAce

- Global Placement is coarse placement and no legalization is happening.
- Standard cells are placed in standard cell rows and they should be placed exactly in the rows.
- Now, after running the floor plan, execute the command `run_placement`

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134661941-5295c208-7247-43b3-a6c6-60b65e432e11.JPG" />
</p>

- First the global placement will occur.
- Main objective of the global placement is to reduce the wire length.
- In openLANE, the concept of HPWL (Half Parameter Wire Length) is used.
- Now, to observe the placement, go to the placement directory using the "cd" command.
- Use the command `ls -ltr` to check what files are present in the directory.
- Now type the following command in terminal: `magic -T /home/vrushabh/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.placement.def &`
- This should open the magic terminal that looks like:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134662363-2a06552c-8a34-493c-a4ce-b53459bc0f20.JPG" />
</p>

- The zoomed version of this output looks like:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134662543-9b9ee771-850f-4f4d-9d78-08bdcaa24581.JPG" />
</p>

- We can observe that all the standard cells are placed in standard cell rows.

## Part 3: Cell design and characterization flows

- Standard cells are placed in a library.
- A library is a place where we keep all of out standard cells, macros, decap cells, IPs, etc.
- Different sizes of the same component have different drive strength and threshold voltage.
- The cell design flow is as follows:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134671659-36a3be10-cc4e-4fb4-86e5-74b64b6c2393.JPG" />
</p>

- Euler's path is the path that is traced only once.
- Characterization flow includes:
    - Read the models
    - Read the extracted SPICE netlist
    - Recognize the behaviour of the circuit
    - Read the subcircuits
    - Attach the necessary power source
    - Apply the stimulus
    - Provide necessary output capacitance
    - Provide necessary simulation command
- Feed in all the above steps as a configuration file to the characterization software called "GUNA".
- Software will generate timing, noise, power .libs, function
- Characterization of .libs:
    - Timing characterization
    - Noise characterization
    - Power characterization

## Part 4: General timing characterization parameters

- Timing Threshold Definitions:
    - slew_low_rise_thr:
        - Defines the point towards the lower set of the rising curve of the output.
        - Typically 20% of Vdd.
    - slew_high_rise_thr:
        - Defines the point towards the higher set of the rising curve of the output.
        - Typically 80% of Vdd.
    - slew_low_fall_thr:
        - Defines the point towards the lower set of the falling curve of the output.
        - Typically 20% of Vdd.
    - slew_high_fall_thr:
        - Defines the point towards the higher set of the falling curve of the output.
        - Typically 80% of Vdd.
    - in_rise_thr:
        - Defines the point towards the centre of the rising curve of the input.
        - Typically 50%
    - in_fall_thr:
        - Defines the point towards the centre of the falling curve of the input.
        - Typically 50%
    - out_rise_thr:
        - Defines the point towards the centre of the rising curve of the output.
        - Typically 50%
    - out_fall_thr:
        - Defines the point towards the centre of the falling curve of the output.
        - Typically 50%

- The formula of propogation delay becomes:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134675442-12831f00-5608-44ca-8d1a-b06d520b5931.JPG" />
</p>

- If output fall threshold is chosen then input rise threshold must be chosen and if output rise threshold is chosen then input fall threshold must be chosen.

- The delay should always come positive.
- Negative delay is not expected and if negative delay is received then it is due to poor choice of threshold points.
- The formula for Transition time becomes:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134675984-cc2e6d5b-26a0-419d-964c-d4fe71a2a3f5.JPG" />
</p>

# Day 3: Design library cell using Magic Layout and ngspice characterization

## Part 1: Labs for CMOS inverter ngspice simulations

### Sub-Part 1: IO placer revision

- First, we will look at the input-output placer.
- In OpenLANE follow the steps upto floorplan as discussed earlier.
- If we run the magic file command, then we had got the output file with equidistand input-output pins as follow:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134760073-dbdbc834-9f10-4922-8590-c547c9c234ea.JPG"/>
</p>

- Now, in a seperate terminal, go to the configuration folder and open the "floorplan.tcl " file using the less command

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134760017-2032cecc-c937-4f4e-8a8b-5de5d3d0ebd5.JPG" />
</p>

- This should open a window as follows:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134760027-0abe7cd0-176e-4b6b-b234-d55f3ad90250.JPG" />
</p>

- Copy the command "set ::env(FP_IO_MODE)" in to the OpenLANE terminal and add the value "2" to it as follows:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134760108-19995877-3bd8-42f6-9630-aa45c16b07e2.JPG" />
</p>

- If we view the magic terminal now, it gives the following output:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134760118-3ce768d7-eb02-4cfd-b69a-18ab94d39bf6.JPG" />
</p>

- When we zoom in on the pins then we can observe:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134760134-d402f56c-a027-4189-8dfc-f7b6504df7ee.JPG" />
</p>

### Sub-Part 2: SPICE deck creation for CMOS inverter

- To create a SPICE deck for a CMOS inverter we must complete the following steps:
    - Define component connectivity
    - Declare component values
    - Identify nodes
    - Name nodes
- Nodes are those two points in between which there is a component.
- We create the following netlist:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134760764-c60be24c-69b2-418e-82c7-af08be304997.JPG" />
</p>

### Sub-Part 3: SPICE simulation lab for CMOS inverter

- The netlist has the following code:

```
***MODEL Descriptions***
***NETLIST Description***
M1 out in vdd vdd pmos w=0.375u l=0.25u
M2 out in 0 0 nmos w=0.375u l=0.25u

cload out 0 10f

Vdd vdd 0 2.5
Vin in 0 2.5
***SIMULATION Commands***
.op
.dc Vin 0 2.5 2.5
***.include tsmc_025um_model.mod***
.LIB "tsmc_025um_model.mod" CMOS_MODELS
.end
```

- Steps to simulate the file in ngspice:
    - Go to the directory/folder containing the netlist using the "cd" command.
    - Then source the circuit file using the "source" command.
    - execute the circuit using the command "run".
    - Using "setplot" command check which plot is currently available.
    - Choose the plot by typing its name. In this case we choose "dc1".
    - Using the command "display" we can check the node voltages available.
    - Now type the command "plot out vs in" to get the dc transfer characteristics.
- Increasing the PMOS width shift the dc transfer characteristics plot to the right.

### Sub-Part 4: Switching Threshold Vm

- Switching threshold is the point at which the device switches.
- It is the point where Vin = Vout
- Graphical method to find Vm is to draw a line across the graph of output voltage to input voltage of a CMOS inverter starting at the origin and ending at the opposite diagonal of the plot (basically a line with a 45 degree inclination with the x-axis). Now, the x-coordinate of the point of intersection of this line and the curve is the switching threshold.
- At Vm, both PMOS and NMOS are turned 'ON' because Vgs has almost crossed the threshold region for both of them.
- IdsP = - IdsN which means that IdsP + IdsN = 0

### Sub-Part 5: Lab steps to git clone vsdstdcelldesign

- Go to the openlane directory using the "cd" commands.
- Now clone the vsdstdcelldesign directory from git using the command `git clone https://github.com/nickson-jose/vsdstdcelldesign.git`.
- Enter the folder "vsdstdcelldesign".
- Type the command "pws" to get the path of this directory.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134766736-9c63ad7c-a058-4ccf-b25e-495dffef43a9.JPG" />
</p>

- Open a new terminal and go to the magic folder in pdks directory using the "cd" command.
- Now copy the "sky130A.tech" file to the the address of "vsdstdcelldesign" directory using the "cp" command.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134766763-2436658c-a661-4e18-97e7-299971a1918d.JPG" />
</p>

- In the directory, "vsdstdcelldesign" check if the file is copied using the "ls -ltr" command.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134766796-e9301b04-a136-487b-ae86-2aeb5d8da9fa.JPG" />
</p>

- Now open the file "sky130_inv.mag" using the magic commands.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134766851-67dae12e-8156-4826-9a64-70029d984fd9.JPG" />
</p>

- The magic window looks like:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134766884-864a7dd1-46b7-45d3-980b-851dc2c968ec.JPG" />
</p>

## Part 2: Inception of Layout and CMOS fabrication process

- There is a 16 mask CMOS process which includes:
    - Selecting a substrate
    - Creating active region for transistors
    - N-well and P-well formation
    - Formation of Gate
    - Lightly doped drain (LDD) formation
    - Source and drain formation
    - Steps to form contacts and local interconnects
    - Higher level metal formation
- In a magic layout, to check if there are connections between two parts of the circuit, press "S" button on keyboard 3 times.
- LEF is library exchanged format.
- Functionality of LEF is protecting the IP.
- In the magic file if there is any DRC error, then go to the "DRC Find next error" option in the "DRC" menu.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134776530-f70f2316-9b58-4886-bc0b-3443e338e5de.JPG" />
</p>

- This option zooms in on the part where the error has occured:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134776556-17cc4475-de21-4d5c-8e46-6121328df590.JPG" />
</p>

- The command window also shows the error:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134776565-ccc2403f-0dbb-4794-a237-fd86a2f23c0a.JPG" />
</p>

- To extract the layout into a spice deck use the command "extract all", then use the command "ext2spice cthresh 0 rthresh 0" and finally "ext2spice"

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134776636-9da3a53b-6fde-4a56-a142-bbdf968f1185.JPG" />
</p>

- The command to view the spice deck created is:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134776950-bbc93e1f-12f7-4d43-94a0-b04bf4a060e2.JPG" />
</p>

- The spice deck for the inverter looks like:

<p align="center">
    <img src="https://user-images.githubusercontent.com/89193562/134776983-bcbf6e48-302a-4454-b50b-39a704207ed5.JPG" />
</p>

## Part 3: Sky130 Tech File Labs

# References
- [https://github.com/The-OpenROAD-Project/OpenLane](https://github.com/The-OpenROAD-Project/OpenLane)
- [https://www.youtube.com/watch?v=EczW2IWdnOM](https://www.youtube.com/watch?v=EczW2IWdnOM)
- [https://www.youtube.com/watch?v=Vhyv0eq_mLU](https://www.youtube.com/watch?v=Vhyv0eq_mLU)
- [https://github.com/nickson-jose/vsdstdcelldesign](https://github.com/nickson-jose/vsdstdcelldesign)
