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

####

# References
- [https://github.com/The-OpenROAD-Project/OpenLane](https://github.com/The-OpenROAD-Project/OpenLane)
- [https://www.youtube.com/watch?v=EczW2IWdnOM](https://www.youtube.com/watch?v=EczW2IWdnOM)
- [https://www.youtube.com/watch?v=Vhyv0eq_mLU](https://www.youtube.com/watch?v=Vhyv0eq_mLU)
