---
layout: page
permalink: /ee272a-winter2021/
title: EE272A - Design Projects in VLSI Systems I
show_sidebar: false
menubar: ee272a_menu
---
## Overview
EE272A will introduce you to the tools and methods to create CMOS integrated circuits. Working in teams you will create a small mixed-signal VLSI design using a modern design flow and EDA tools. The project involves writing a synthesizable C++ model of the chip, using high level synthesis tools to convert it into Verilog, creating a testing/debug strategy for your chip, wrapping custom layout to fit into a standard cell system, using synthesis and place and route tools to create the layout, and understanding all the weird stuff you need to do to tape-out a chip. Useful for anyone who will build a chip in their Ph.D.

**Term**: 2020-2021 Winter  
**Units**: 3-4  
**Instructor**: Priyanka Raina (praina at stanford dot edu)  
**TAs**: Jackson Melchert (melchert at stanford dot edu), Kalhan Koul (kkoul at stanford dot edu)  
**Lectures**: Mon, Wed 10:00 AM - 11:20 AM over Zoom.   
**Office hours**:  
Priyanka: Wed, 2:30 - 3:30 PM over Zoom.  
Jackson: Mon, 11:30 - 12:30 PM and Fri, 9 - 10 AM over Zoom.  
Kalhan: Thu, 6 - 7 PM and Sun, 6 - 7 PM over Zoom.  
**Canvas**: All documents, including lecture notes, and lecture video recordings will be posted on Canvas.   
**Piazza**: For questions about lectures and homework we will use Piazza.  

## Class Project
This is a project based class, and there is a lot of material that we need to cover in a quarter. As a result you will be introduced to a number of new tools that you will learn through weekly tasks to build your project. The project will involve building a large digital design (a neural network accelerator) and an analog design (a phase-locked loop (PLL)) from scratch. We recommend forming teams of two for all homework.

## Pre-requisites  
[EE271](/ee271-autumn2019/) is a pre-requisite for this course. Please talk to us if you have any questions about pre-requisites.

## Course Topics and Tentative Schedule
   # Date
1 2
3 4 5 6 7
8 9
10 11 12
Topic
Homework
    Mon, Jan 11
  Class objective and overview, major tasks, tools, and flow
  HW1: Design space exploration
   Wed, Jan 13
  DNNs, chip constraints, and the limitation of accelerators
     Mon, Jan 18
  Martin Luther King, Jr., Day (holiday, no classes)
  HW1 due, HW2: Unit testing and design in SystemVerilog
   Wed, Jan 20
  Maintaining designer sanity, creating a testing infrastructure
     Mon, Jan 25
  High level synthesis
  HW2 due, HW3: Integration testing and design in SystemVerilog
   Wed, Jan 27
  High level synthesis
     Mon, Feb 1
  Visual introduction to physical design
  HW3 due, HW4: HLS design and functional verification
  Wed, Feb 3
 Static timing analysis
     Mon, Feb 8
 Advanced synthesis (retiming, memories, clock, reset), floorplanning
 HW4 due, HW5: HLS design and performance verification
  Wed, Feb 10
 P&R: Placement
     Mon, Feb 15
 Presidents' Day (holiday, no classes)
 HW5 due, HW6: Synthesis, floorplanning, EE272B project proposal due
   Wed, Feb 17
  P&R: Clock tree synthesis, routing
     Mon, Feb 22
  P&R: Signoff steps - timing closure, DRC, LVS, LPE, GLS
  HW6 due, HW7: Place and route, timing closure, signoff
  Wed, Feb 24
 Analog functional model
                 https://canvas.stanford.edu/courses/131349
2/14

 7/1/2021 Design Projects in VLSI Systems I
    # Date
Topic
Homework
   Mon, Mar 1
 Making cells
   HW7 due, HW8: Analog block modeling and design
   Wed, Mar 3
 How to use Virtuoso for schematic and layout, design rule overview, how to wrap a cell for P&R
    Mon, Mar 8
  Design for testability
  HW8 due, HW9: Hierarchical design, analog block integration
  Wed, Mar 10
 Packaging
     Mon, Mar 15
 Power domains
 HW9 due, HW10: Optimization, comparison with DSE, comparison with related work, paper like final report (due only if taking the class for 4 units)
   Wed, Mar 17
  Board design
    Fri, Mar 19
  HW10 due, EE272B project checkin
13
14
15 16
17
18

### Course Texts and Materials
The lecture notes are the main reference material that you will use in the class. While the notes will cover the material in the class, they will not be as complete as the information that you would find in a textbook.
To get additional information and/or an alternative explanation of the material in the notes, you can refer to these textbooks:  
Kahng, Lienig, Markov, Hu, VLSI Physical Design  
Weste, Harris, Principles of CMOS VLSI Design (4th Edition)  
Rabaey, Chandrakasan, Nikolic, Digital Integrated Circuits (2nd Edition)  

### Course Videos
Course recordings can be accessed by logging into the course Canvas site. These recordings might be reused in other Stanford courses, viewed by other Stanford students, faculty, or staff, or used for other education and research purposes. Note that while the recording will mostly capture instructor slides and video, occasionally a part of your image or voice might be incidentally captured. If you have questions, please contact a member of the teaching team.

### Academic Misconduct Policy
It is expected that Stanford’s Honor Code will be followed in all matters relating to this course. You are encouraged to meet and exchange ideas with your classmates while studying and working on homework assignments, but you are individually responsible for your own work and for understanding the material. You are not permitted to copy or otherwise reference another student’s homework or computer code. If you have any questions regarding this policy, feel free to contact us.
Compromising your academic integrity may lead to serious consequences, including (but not limited to) one or more of the following: failure of the assignment, failure of the course, disciplinary probation, suspension from the university, or dismissal from the university.
Students are responsible for understanding the University’s Honor Code policy and must make proper use of citations of sources for writing papers, creating, presenting, and performing their work, taking examinations, and doing research.
Full text of the honor code policy and fundamental standard is [here](https://communitystandards.stanford.edu/student-conduct-process/honor-code-and-fundamental-standard).

### ADA Policy
Students who may need an academic accommodation based on the impact of a disability must initiate the request with the Office of Accessible Education (OAE). Professional staff will evaluate the request with required documentation, recommend reasonable accommodations, and prepare an Accommodation Letter for faculty dated in the current quarter in which the request is being made. Students should contact the OAE as soon as possible since timely notice is needed to coordinate accommodations. The OAE is located at 563 Salvatierra Walk (phone: 723-1066, [website](http://oae.stanford.edu)).

### Other Useful Classes
Introduction to VLSI systems (EE271) - Pre-requisite  
Design Projects in VLSI Systems II (EE272B) - Follow up course to EE 272A  
Digital Systems Engineering (EE273)  
Semiconductor Memory Devices and Circuit Design (EE309A)  
Emerging Non-Volatile Memory Devices and Circuit Design (EE309B)  
Fundamentals of Analog Integrated Circuit Design (EE214A)  
Advanced Integrated Circuit Design (EE214B)  
RF Integrated Circuit Design (EE314A)  
Analog-Digital Interface Circuits (EE315)  
Programming (perl, C, python)  
Plus application-specific knowledge  
