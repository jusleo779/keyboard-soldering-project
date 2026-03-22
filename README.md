# keyboard-project

## Background

Developed and designed a custom keyboard using off-the-shelf parts, featuring an ATmega32U4 microcontroller (Pro Micro) and a Tanuki PCB. Through this project, I developed hands-on skills in soldering, hardware debugging, and mechanical design. The project required months of research, design decisions, multiple 3D model drafts, and iterative assembly. Although the final system was not completed due to hardware failure during PCB rework, the project provided practical experience in the design process and hardware-level debugging.

## Overview of Project Planning

The planning phase took approximately a month and a half and included research and skill development. I focused on developing skills in tools and software such as soldering and FreeCAD, while researching essential components compatible with the PCB. Although some components were initially missing, the research phase provided a solid foundation for understanding the required materials and system integration constraints.

## Research

Originally, I planned to begin by learning PCB layout and designing a board from scratch. However, PCB design requires circuit-level knowledge beyond my current background. Due to time constraints, I decided to focus on hardware assembly and system integration using an existing PCB.

I researched off-the-shelf components and verified compatibility with the ATmega32U4 microcontroller, resistors, diodes, and other hardware elements. To minimize integration issues, I evaluated component specifications and ensured electrical compatibility with the PCB. I also researched 3D printing tolerances and mechanical constraints that could affect case alignment when combining the open-source case with my custom FreeCAD design.

## Learning

The main focus of the project was developing practical soldering skills. While I learned foundational techniques from online tutorials, most lessons came from hands-on application.

Key knowledge from tutorials:

• Soldering temperature depends on solder material (lead-free vs. leaded).

• The soldering iron tip should be properly tinned before use.

• The iron must contact both metal surfaces to create a proper joint.

Lessons from real-world application:

• Through-hole solder joints are mechanically strong and difficult to remove without proper desoldering tools.

• Controlling solder quantity is critical to avoid bridges and ensure clean joints.

• Flux significantly improves solder flow and joint quality.

• Thermal management is essential. During desoldering of the microcontroller headers, excessive heat propagated to the surface-mounted USB connector, causing pad separation. Multiple repair attempts further damaged the board, preventing powered validation of the system.

This experience reinforced the importance of tool limitations, planning rework steps carefully, thermal control, and researching repair strategies before repeated attempts.

My second focus was **FreeCAD**, which became necessary when the purchased case did not fit the PCB. I designed and 3D printed a custom bottom case to resolve this issue.

Design considerations included:

• PCB structural support  
• Screw holes with increased tolerance to account for 3D printing variation  
• Slip-pad slots to prevent movement  

This portion of the project strengthened my understanding of mechanical tolerances, measurement constraints, and CAD-based problem solving.

## Testing

I developed a structured testing plan to evaluate electrical and mechanical reliability. The reliability plan included slip testing, impact testing, shaking tests, and USB connector stress considerations.

The electrical validation plan involved using a multimeter to check for voltage stability under multiple key presses and to verify proper electrical connections.

Due to hardware failure during USB connector rework, the testing plan was not executed. However, defining a validation approach highlighted the importance of structured verification in hardware projects.

## Lesson Learned

• Without the right tools, the solder is permanent, so it's important to plan a course of action and steps before committing

• Research is an essential in designing and developing the project, but it's not final, you must be adaptable and ready to problem-solve issues

• When reworking you should act with caution because it can cause further damage to components

## Connection to Hardware Engineering

Hardware Engineering requires a lot of time to assemble, debug, and validate the hardware system. These processes relate back to essential skills like soldering and mechancial design.

Soldering is essential for assembling circuits, reworking components, and repairing faults throughout the project. Without proper soldering techniques and temperature management, the hardware can fail or become permanaetly damaged. 

Mechanical Design is essential for protecting and supporting the electrical hardware components preventing further physical damage, and increases reliability of the system. 
