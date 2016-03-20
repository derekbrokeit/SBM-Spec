#Manufacturing Environment
##Build Surface

Build surfaces are used as the base to grow 3D printed items on. In microgravity it is uniquely critical that parts are secured without the aid of gravity. The build surface is designed for quick removal and installation so they may be swapped out depending on use case or maintenance.
                                
##Specifications and Technical Notes

###For Hardware Designers
The build surface interface allow hardware designers to create new capabilities for existing space-based manufacturing platforms as well as capabilities that conform well to new platforms as they come online. The drawing file for the build surface provides a starting point for designers. The key design feature in the build surface are the through holes which are used to mount the build surface to the space-based manufacturing build environment. Hardware designers may develop a variety of build surface materials and surface treatments to provide new options for building parts off of.

###For Software Engineers
The current build surface interface does not entail a software aspect.

###For Manufacturing Engineers
As with the technical notes listed above for hardware designers, manufacturing engineers should leverage the build surface drawing file as a defacto blueprint for manufacturing new instances of the hardware. 

A general best practice when manufacturing the build surface is to abide by NASA Payload Safety Policy and Requirements for the International Space Station, document SSP 51700, in order to meet safety and human factors requirements. Since the build surface is a component that at some point may be handled by crew, certain design additions may need to be made to enable accessibility and ease of manipulation. This design exercise is left to the manufacturing engineer and hardware designer to determine what is best given the specific mission needs based on NASA specifications and requirements.


##Build Surface Interfaces
The build surface is the base for parts to be 3D printed on, mounted for other manufacturing or secondary processes, or otherwise utilized in an on orbit manufacturing facility. The interfaces below show the minimum design features required for the build surface to integrate with the AMF.

###Physical Interfaces
The build surface is designed to be quickly removed from a build platform by simply retracting four threaded screws. The alignment of the threaded hole is critical and shall be to the dimensions shown in the Figure 3a. The length and width dimensions shall not exceed the values listed in the diagram. The top surface does not necessary need to be flat if there is a contour or geometry that is more suitable for the application.

###Material Properties
All materials will need to be approved for use on the International Space Station. The  MSFC-HDBK-527 Material Selection List for Space Hardware Systems can be followed for material selection. Materials not currently in NASA’s Materials and Processes Technical Information System (MAPTIS) may need to be tested for Flammability and Outgassing per NASA-STD-6001.

###Safety and Human Factors
Crew safety is paramount during ISS operations. Safety processes per SSP 51700 shall be followed when designing new hardware.

Relevant Documents
MSFC-HDBK-527 Material Selection List for Space Hardware Systems

SSP 30237 Space Station Electromagnetic Emission and Susceptibility
Requirements

SSP 51700 Payload Safety Policy and Requirements for the International Space Station

NASA-STD-6001, Test 7 Flammability, Odor, Offgassing, and compatibility Requirements
and Test Procedures for Materials in Environments That Support Combustion

