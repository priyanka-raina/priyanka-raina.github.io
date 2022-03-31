---
layout: page
permalink: /ee271-autumn2019/
title: EE271 - Introduction to VLSI Systems 
show_sidebar: false
menubar: ee272_menu
---
## Overview
Rarely does a single technology take over the world in quite the way that integrated circuits (ICs) have done. From their invention around 60 years ago, ICs are now found in almost everything we do (computers, smart phones, wearables, robots). While in the past, the focus was on designing high performance general purpose processors, the industry is now moving towards more and more specialized ICs (called accelerators) such as graphics processing units (GPUs), deep learning accelerators and image and video processing accelerators. This move towards specialization is driven by the high performance and energy efficiency demands of sensor-rich smart phones, autonomous robots, and large data centers running applications such as image and video processing and analysis, graphics, speech processing, AI and machine learning. This course will teach you how to design such specialized ICs.

The course starts with a quick introduction to MOS transistors and IC fabrication and then creates abstractions to allow you to create and reason about complex digital systems. It uses a switch resistor model of a transistor, uses it to model gates, and then shows how gates and physical layout can be synthesized from Verilog or SystemVerilog descriptions. Most of the class will be spent on providing techniques to create designs that can be validated, are low power, provide good performance, and can be completed in finite time.

**Term**: 2019-2020 Autumn    
**Units**: 3    
**Instructor**: Priyanka Raina    
**TAs**: Kartik Prabhu, Maxwell Bradley Strange    
**Lectures**: Mon, Wed 10:30 AM - 12:00 PM at Thornton 102    
**Review sessions**: Fri, 11:30 - 12:20 at Thornton 102    
Weekly review sessions will help you recap some of the pre-requisites and discuss homework and background material for the project.    
**Office hours**:    
Priyanka: Mon, Tue, 1:30 - 2:30 PM in Allen 114    
Kartik: Mon, Wed, 6:00 - 7:00 PM in Packard 106    
Max: Tue, Thur, 10:30 - 11:30 AM in Gates 323    
**Canvas**: All documents, including lecture notes, and lecture video recordings will be posted on Canvas.    
**Piazza**: For questions about lectures, homeworks and project we will use Piazza.     

## Course learning goals
By taking this course, you will be able to:

1. Build combinational digital logic from transistors and wires and model and optimize its delay and power.
2. Build sequential logic using clocks and storage elements; understand the tradeoffs between different clocking methods.
3. Design a complex digital system by describing it in Verilog or SystemVerilog and use CAD tools to synthesize it into gates and physical layout.
4. Verify the system using testing and formal methods using CAD tools.
5. Measure the system's power, performance and area; build an intuition for tradeoff's between these and iterate on the design to optimize them.

## Prerequisites
EE 101A and EE 108  (or equivalents) are pre-requisites for this course. We are looking for familiarity with transistors, logic design, Verilog and digital system organization from these pre-requisite courses.

Please talk to us if you have any questions about prerequisites.

## Course topics and tentative schedule
#	Date	Topic	Homework
1	Mon, Sep 23	Introduction	
2	Wed, Sep 25	Transistors and gates	HW 1 out
Fri, Sep 27	Review session 1	
3	Mon, Sep 30	Layout and fabrication	
4	Wed, Oct 2	Gate delay and power - 1	
Fri, Oct 4	Review session 2	HW 2 out, HW 1 due
5	Mon, Oct 7	Gate delay and power - 2, scaling	
6	Wed, Oct 9	Delay optimization and logical effort - 1	
Fri, Oct 11	Review session 3	HW 3 out, HW 2 due
7	Mon, Oct 14	Delay optimization and logical effort - 2	
8	Wed, Oct 16	Static timing analysis	
Fri, Oct 18	Review session 4	HW 4 out, HW 3 due
9	Mon, Oct 21	Sequential circuits	
10	Wed, Oct 23	HDLs, synthesis, optimizations	
Fri, Oct 25	Review session 5: Midterm review	HW 5 out, HW 4 due
11	Mon, Oct 28	Midterm (in class)	
12	Wed, Oct 30	Hardware generators (genesis, magma)	
Fri, Nov 1	Review session 6: Project walk-through	HW 5 due, Project out
13	Mon, Nov 4	Design verification (Richard Ho)	
14	Wed, Nov 6	Formal verification - 1 (Clark Barrett)	
Fri, Nov 8	Review session 7: SystemVerilog, genesis2, UVM drivers and monitors	
15	Mon, Nov 11	Formal verification - 2 (Clark Barrett)	Project part 1 due
16	Wed, Nov 13	Advanced synthesis, delay models	
Fri, Nov 15	Review session 8: Writing assertions and using CoSA (Makai)	
17	Mon, Nov 18	High level synthesis	
18	Wed, Nov 20	QED and symbolic QED (Subhasish Mitra)	Project part 2 due
Fri, Nov 22	Review session 9: Rasterizer optimizations	
Mon, Nov 25	No class (Thanksgiving)	
Wed, Nov 27	No class (Thanksgiving)	
Wed, Nov 29	No review session (Thanksgiving)	
19	Mon, Dec 2	Testing and design for testability	
20	Wed, Dec 4	Accelerators	Project part 3 due
Fri, Dec 6	Review session 10: Magma + fault (Lenny), HLS	
Fri, Dec 13		Project part 4 due (extra credit)

## Course grading
Midterm: 35% - In class exam, closed book but 1 hand written cheatsheet allowed.    
Homework: 25% - 5 homeworks, 5% each.    
Project: 40% (+ extra 10%) - Can be time consuming, going to the review sessions will be helpful.    
In groups of 2.    
Part 1: Write C/C++ code to express high-level system behavior for a rasterization pipeline.    
Part 2: Implement the rasterization pipeline in SystemVerilog and synthesize it to gates using EDA tools.    
Part 3: Optimize the performance of the design.    
Part 4: (extra 10%) Port the rasterizer to magma and fault (new generator framework) and high level synthesis, and compare results.    

## Homework
Handed out on Fridays (except HW1).    
Due the following week (at 11:59 PM on Friday). Please submit homework on canvas.    
Homework received up to 24 hours late will receive 50% credit. Homework received beyond 24 hours late will receive 0% credit.    
Group work on homework is okay, but each student must prepare their own individual assignment to turn in.    
If you need us to regrade your homework or midterm it must be submitted within 1 week.    
Entire homework/midterm will be re-graded and downgrading is possible.    

## Make-up exam policy
There are no make-ups for the midterm, so you must plan to be in class that day. Let me know immediately if a university-sanctioned event makes it impossible for you to be present at the midterm.

## Course texts and materials
The lecture notes are the main reference material that you will use in the class. While the notes will cover the material in the class, they will not be as complete as the information that you would find in a textbook.
To provide additional information and/or an alternative explanation of the material in the notes, readings from other textbooks will be included in the notes. While these readings are not required, they are often helpful in understanding the material.
1. Weste, Harris, Principles of CMOS VLSI Design (4th Edition) - Primary reference. Most readings are from this book. The book is on reserve for class use in Terman library.
2. Rabaey, Chandrakasan, Nikolic, Digital Integrated Circuits (2nd Edition)
3. Wolf, Modern VLSI Design (3rd Edition)
4. Glasser Dobberpuhl, The Design and Analysis of VLSI Circuits - Good transistor-level circuits book, but very old (mostly nMOS!)

## Course videos
Video cameras located in the back of the room will capture the instructor presentations in this course. For your convenience, you can access these recordings by logging into the course Canvas site. These recordings might be reused in other Stanford courses, viewed by other Stanford students, faculty, or staff, or used for other education and research purposes. Note that while the cameras are positioned with the intention of recording only the instructor, occasionally a part of your image or voice might be incidentally captured. If you have questions, please contact a member of the teaching team.

## Academic misconduct policy
It is expected that Stanford’s Honor Code will be followed in all matters relating to this course. You are encouraged to meet and exchange ideas with your classmates while studying and working on homework assignments, but you are individually responsible for your own work and for understanding the material. You are not permitted to copy or otherwise reference another student’s homework or computer code. If you have any questions regarding this policy, feel free to contact us.

Compromising your academic integrity may lead to serious consequences, including (but not limited to) one or more of the following: failure of the assignment, failure of the course, disciplinary probation, suspension from the university, or dismissal from the university.

Students are responsible for understanding the University’s Honor Code policy and must make proper use of citations of sources for writing papers, creating, presenting, and performing their work, taking examinations, and doing research.

## ADA policy
Students who may need an academic accommodation based on the impact of a disability must initiate the request with the Office of Accessible Education (OAE). Professional staff will evaluate the request with required documentation, recommend reasonable accommodations, and prepare an Accommodation Letter for faculty dated in the current quarter in which the request is being made. Students should contact the OAE as soon as possible since timely notice is needed to coordinate accommodations. The OAE is located at 563 Salvatierra Walk (phone: 723-1066, URL: http://oae.stanford.edu).

## Other useful classes
1. Design Projects in VLSI Systems (EE272)
2. Analog Circuit Design (EE214)
3. Digital Systems Engineering (EE273)
4. Integrated Circuit Fabrication Processes (EE212)
5. Principles and Models of Semiconductor Devices (EE216)
6. RF Integrated Circuit Design (EE314A, B)
7. Programming (perl, C, python)
8. Plus application specific knowledge
