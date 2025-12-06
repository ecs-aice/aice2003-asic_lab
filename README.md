# AICE2004 ASIC Design Lab

This lab is a (slight) modification of the excelent LibreLane workshop that Leo Moser ran during HeiChips 2025.

You will learn how to use and configure LibreLane, debug your design, integrate macros, and implement a full chip.

- LibreLane repository: https://github.com/librelane/librelane
- LibreLane documentation: https://librelane.readthedocs.io
- Original workshop: https://github.com/FPGA-Research/heichips25-workshop

## Learning Outcomes
This laboratory exercise aims to:
* Familiarise you with a typical ASIC design flow.
* Demonstrate that open-source tools can be used to develop ASICs

Having successfully completed the lab, you will be able to:
* Configure LibreLane,
* debug a design,
* integrate macros and
* implement a full-chip ASIC.

## Lab Equipment
You need to bring:
* Your logbook
* Pens, pencils, etc.

You may want to bring (optional):
* Real Digital Blackboard
* Micro USB cable

Software:
* WSL
* LibreLane
* OSS CAD Suite

General Information
* You should work in pairs.
* The lab is assessed by an end-of-lab test on Moodle that will be made available during the lab and can only be completed from a lab PC.

Academic Responsibility and Conduct Reminder
* You are expected to work in pairs for this lab. Not groups of three, four or more.
* While collaboration with other students in the lab is encouraged, remember that the work you submit as a pair must be your own.
* Yes, we expect that the code that you and your lab partner submit will be identical - this is permitted.
* Copying code from another pair or sharing your code with another pair is collusion and may be referred to the ARC officer.
* Do NOT share screenshots/photos of the test with other students. Do NOT take any screenshots/photos of the test.
* If you use sources from the web to help answer some of the questions and/or complete the lab, record any sources in your logbook.

## Prerequisites
You will require the AICE2003 ASIC Lab WSL image or a working [Nix-based Installation](https://librelane.readthedocs.io/en/latest/installation/nix_installation/installation_linux.html) of LibreLane and the [OSS Cad Suite](https://github.com/YosysHQ/oss-cad-suite-build).

The instructions are written around the use of the WSL image.

## Setting Up
Download the AICE2003 ASIC Lab WSL image and then import it into WSL:

Start the image and make sure you are in your home directory in the image by typing `cd ~`.

`cd` into the librelane directory and execute `nix-shell` to start the LibreLane environment. This has to be done each time you want an extra terminal.

Once Nix has started, check that LibreLane is happy by running `librelane --smoke-test`. This runs through the full flow and checks that everything is working as it should. You will see a lot of text fly by and should end up seeing something like: 

<img width="1733" height="980" alt="image" src="https://github.com/user-attachments/assets/001e49ac-9309-4959-9367-cfe9a140942e" />

You now have a working LibreLane installation and can move on with the exercises below.

## Exercises

- [Exercise 1](exercise_1/README.md): Let's Implement a Counter
- [Exercise 2](exercise_2/README.md): All About Configuration Variables
- [Exercise 3](exercise_3/README.md): Controlling the Flow
- [Exercise 4](exercise_4/README.md): Using Macros
- [Exercise 5](exercise_5/README.md): The LibreLane API
- [Bonus](bonus/README.md): Full Chip Design

### License

The code is licensed under Apache 2.0

Workshop: CC-BY-SA-4.0 Leo Moser
