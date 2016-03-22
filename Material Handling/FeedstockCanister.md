#Material Handling |
##[Feedstock Canister](http://sbmspec.com/feedstock-canister)

#####The feedstock canister is an enclosure for containing wire feedstocks for manufacturing and processing. It provides a safe environment for maintaining material integrity as well as access for control of feedstock in and out of the canister.

####Feedstock Canister Interfaces

Feedstock Canisters are designed to contain raw materials for later utilization. Power and data interface requirements for commanding electrical subsystems for robotically manipulating the filament to the canister are provided.

######Physical Interfaces

The standard feedstock canister interface allows for rapid integration into payloads. The exit port for the filament is shown in Figure 1a. The feedstock canister can exchange 1.75 ± 0.1mm diameter filament. The outer dimensions shall not exceed the dimensions listed in Figure 1a. A handle shall be placed on the front face to provide a method for crew members to grip and pull the feedstock canister.

######Electrical Interfaces

A 10-pin connector is used to transfer power and data to the feedstock canister and is located in the rear wall. The connector provides an interference fit connection to the inverse connector found within a space-based manufacturing system. The feedstock canister should integrate the male-end connector, which plugs into a female-end connector within the space-based manufacturing system. The feedstock canister shall be designed to self feed and retract the filament.

Both a 24V and 5V DC power source is available for the feedstock canister. Total power draw is limited to 40W. Pinouts are shown the table below.

**[TABLE]**

##Specifications and Technical Notes

###For Hardware Designers

The Feedstock Canister interfaces allow hardware designers to create new capabilities for existing space-based manufacturing platforms as well as capabilities that conform well to new platforms as they come online. The drawing file for the feedstock canister provides a starting point for designers. In some cases, depending on feedstock material requirements driven by the end user, the feedstock canister may require all pass-throughs to be sealed in order to maintain feedstock
longevity and integrity.

###For Software Engineers

Capabilities for handling feedstock within the canister and moving feedstock out of canister to a material processing location must be designed. The interface describes a standard MOLEX 15-24-7143 connector that provides power and data pass through into the canister. This connector defines the extent of the electrical & mechanical interface of the feedstock canister, allowing for a wide flexibility in control options.

###For Manufacturing Engineers

When manufacturing the feedstock canister, abide by NASA Payload Safety Policy and Requirements for the International Space Station, document SSP 51700, in order to meet safety and human factors requirements. Since the feedstock canister is a component that at some point may be handled by crew, certain design additions may need to be made to enable accessibility and ease of manipulation. This design exercise is left to the manufacturing engineer and hardware designer to determine
what is best given the specific mission needs based on NASA specifications and requirements.

###Safety and Human Factors

Crew safety is paramount during on orbit operations. Safety processes per SSP 51700 shall be followed when designing new hardware.

######Relevant Documents

MSFC-HDBK-527 Material Selection List for Space Hardware Systems

SSP 30237 Space Station Electromagnetic Emission and Susceptibility Requirements

SSP 51700 Payload Safety Policy and Requirements for the International Space Station

NASA-STD-6001, Test 7 Flammability, Odor, Offgassing, and compatibility Requirements and Test Procedures for Materials in Environments That Support Combustion
