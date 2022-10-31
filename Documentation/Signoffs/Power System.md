## Required Format and Sections of the signoff request

This signoff is for the power system of a robot. It must take in the voltage and current supplied by the battery and transform it to the desired levels of each of the subsystems connected. Further, it must appropriately filter the power such that the ripple does not cause the voltage to go out spec for any of the components.


## Constraints

Voltage 



<p align="center">
<img src="https://i.stack.imgur.com/WK2zg.png">
</p>


## Buildable pdf schematic 

The third section should show the buildable schematic directly embedded in the markdown file as an image (pdf files can't be embedded, but they can be converted with high resolution to jpg). If the schematic is not clearly readable and appropriately sized, the supervisor will reject the signoff. 

The schematic must be appropriate to the design. ie. 3d model for a physical system or wiring schematic for a circuit. Further, the schematic(s) must contain every detail necessary for the design to be built by someone who has no knowledge of the design. Every relevant component value and measurement must be given.

## Analysis

A complete and relevant analysis of the design showing that it **should** meet the constraints and perform the desired function must be given. This analysis must be comprehensive and well explained so that it is convincing to the faculty supervisor. If the signoff request is not convincing either because the requirements and constraints are insufficient, unjustified, or not appropriately shown to be met by the design, then approval will not be given. Without approval, the components for the subsystem aren't allowed to be ordered. 

$V=I \cdot R$

## BOM

A complete list of all components needed for the design must be given with the cost of each component and the total cost of the subsystem. The BOM should be a markdown table (excel tables can be copied and pasted directly into the markdown file and they will be automatically converted).

