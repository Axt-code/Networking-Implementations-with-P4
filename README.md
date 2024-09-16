# P4 Programming Assignment

## Overview
This project involves implementing various P4 programs for network packet management and routing. The assignment is divided into four main tasks: Packet Reflector, Packet Repeater, L2 Basic Forwarding, and ECMP Routing.

## Tasks
1. **Packet Reflector**
   - Developed a P4 program to reflect packets as described in the example exercises.

2. **Packet Repeater**
   - Implemented the `repeater.p4` program by filling in TODO sections using two approaches:
     - Approach 1: Conditional statements and fixed logic.
     - Approach 2: Match-action table populated using CLI.

3. **L2 Basic Forwarding**
   - Implemented the `l2_basic_forwarding.p4` program by completing TODO sections.
   - Created `s1-commands.txt` for table configurations.

4. **Equal-Cost Multi-Path (ECMP) Routing**
   - Completed the `ecmp.p4` program and related header files by filling in the gaps.
   - Created six `sX-commands.txt` files for switch configurations.

## Instructions
1. **Download and Setup**
   - Download the VM from the provided link and import it using VirtualBox (username: p4, password: p4).

2. **Implementation**
   - Follow the instructions in the respective exercise directories to complete each task.

3. **Submission**
   - Zip the following folders: `02-Repeater`, `03-L2_Basic_forwarding`, `05-ECMP`.
   - Each folder should contain:
     - `.p4` files
     - Subfolders `logs` and `pcap`
     - Any additional or modified scripts

## Resources
- P4 Tutorial
- BMV2
- P4-16 Specification
- Portable Switch Architecture (PSA) Specification

For detailed instructions and guidance, refer to the README files provided in each exercise directory.

