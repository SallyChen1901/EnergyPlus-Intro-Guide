This file aims to provide a summary of the assumptions, variable explanations and example inputs of objects related to HVAC system modelling in EnergyPlus. The example inputs are from the example model made for Scott Hall 6002 at CMU campus. Notice that this file is an overall explanation only for rooms with a VAV HVAC system. For other systems, e.g. Unitary system, please read the following section **For Other System** for variable examination suggestions. 

# Reading Instruction

There are in total seven sheets in this excel file. 
- **Required Info**: a summary of the variables that need to be examined for one particular model. There are two tables in this sheet: one listed for variables that must be asked for simulation on one system, the other one for variables that are optional but would suggest asking. The way they are separated into two tables is based on whether EnergyPlus has a default value for it or not. 
- **all other sheets**: These sheets include the variable information about an HVAC system. Filling out all these information is all that's necessary for adding a VAV HVAC system in EnergyPlus. The sheets are structured in the following rules:
  - jiji
  - aea

# For Other System
