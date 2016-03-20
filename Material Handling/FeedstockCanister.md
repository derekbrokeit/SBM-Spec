#Material Handling |
##[Feedstock Canister](http://sbmspec.com/feedstock-canister)

######The feedstock canister is an enclosure for containing wire feedstocks for manufacturing and processing. It provides a safe environment for maintaining material integrity as well as access for control of feedstock in and out of the canister.

##Specifications and Technical Notes

###For Hardware Designers

The Feedstock Canister interfaces allow hardware designers to create new capabilities for existing space-based manufacturing platforms as well as capabilities that conform well to new platforms as they come online. The drawing file for the feedstock canister provides a starting point for designers.  In some cases, depending on feedstock material requirements driven by the end user, the feedstock canister may require all pass-throughs to be sealed in order to maintain feedstock longevity and integrity.  

###For Software Engineers

Software engineers and electrical engineers may work simultaneously to design control capability for handling feedstock within the canister and to move feedstock out of canister to a material processing location. The interface describes a standard MOLEX 15-24-7143 connector that provides power and data pass through into the canister. This connector defines the extent of the electrical/mechanical interface of the feedstock canister, allowing for a wide flexibility in control options. 

###For Manufacturing Engineers

As with the technical notes listed above for hardware designers, manufacturing engineers should leverage the feedstock canister drawing file as a defacto blueprint for manufacturing new instances of the hardware. The MOLEX connector can be mounted within the feedstock canister in a variety of manners, leaving freedom to the manufacturing engineer to choose which method best suits the given purpose. 

A general best practice when manufacturing the feedstock canister is to abide by NASA Payload Safety Policy and Requirements for the International Space Station, document SSP 51700, in order to meet safety and human factors requirements. Since the feedstock canister is a component that at some point may be handled by crew, certain design additions may need to be made to enable accessibility and ease of manipulation. This design exercise is left to the manufacturing engineer and hardware designer to determine what is best given the specific mission needs based on NASA specifications and requirements.

##Feedstock Canister Interfaces

Feedstock Canisters are designed to contain raw materials for payloads. When required payloads may be supply power and data for commanding electrical subsystems for robotically manipulating the filament to the canister. The physical and electrical interfaces for integrating the Feedstock canister with a payload are detailed below.

###Physical Interfaces

The standard feedstock canister interface allows for rapid integration into payloads. The exit port for the filament are shown in Figure 1b. The feedstock canister can exchange 1.75mm ± 0.1mm diameter filament with the payload. The outer dimensions shall not exceed the dimensions listed in the diagram. A handle shall be placed on the front face to provide a method for crewmembers to grip and pull the canister.

###Electrical Interfaces

A 10-pin connector is used to transfer power and data to the feedstock canister and is located in the rear wall. The connector provides an interference fit connection to the inverse connector found within a space-based manufacturing system. The feedstock canister should utilize the male-end connector, which plugs into a female-end connector within the space-based manufacturing system. Cartridge shall be designed to self feed and retract the filament.

Both a 24V and 5V DC power source is available for the cartridge. Total power draw is limited to 40W. Pinouts are shown the table below. 


###Material Properties
All materials will need to be approved for use on the International Space Station. The  MSFC-HDBK-527 Material Selection List for Space Hardware Systems can be followed for material selection. 

Materials not currently in NASA’s Materials and Processes Technical Information System (MAPTIS) may need to be tested for Flammability and Outgassing per NASA-STD-6001. Outgass testing at operational temperatures may be required for new filament materials.

###Safety and Human Factors 
Crew safety is paramount during ISS operations. Safety processes per SSP 51700 shall be followed when designing new hardware.


###Relevant Documents
MSFC-HDBK-527 Material Selection List for Space Hardware Systems

SSP 30237 Space Station Electromagnetic Emission and Susceptibility
Requirements

SSP 51700 Payload Safety Policy and Requirements for the International Space Station

NASA-STD-6001, Test 7 Flammability, Odor, Offgassing, and compatibility Requirements
and Test Procedures for Materials in Environments That Support Combustion


