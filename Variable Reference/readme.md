This file aims to provide a summary of the assumptions, variable explanations and example inputs of objects related to HVAC system modelling in EnergyPlus. The example inputs are from the example model made for Scott Hall 6002 at CMU campus. Notice that this file is an overall explanation only for rooms with a VAV HVAC system. For other systems, e.g. Unitary system, please read the following section **For Other System** for variable examination suggestions. 

# Reading Instruction

There are in total seven sheets in this excel file. 
- **Required Info**: a summary of the variables that need to be examined for one particular model. There are two tables in this sheet: one listed for variables that must be asked for simulation on one system, the other one for variables that are optional but would suggest asking. The way they are separated into two tables is based on whether EnergyPlus has a default value for it or not. 
- **all other sheets**: These sheets include the variable information about an HVAC system. Filling out all these information is all that's necessary for adding a VAV HVAC system in EnergyPlus. The sheets are structured in the following rules:
  - *All Variables of an Object*, included with: Units, Must Have an Input Value or Not, Example Input Value for Scott 6002.
  - *Schedules*, if required by the object. The details of scheudles are included here with the related object to help user understand how scheudules are combined with HVAC system. However, in the IDF-Editor, schedule and HVAC system are separated into two different classes. 
  - *Comments*. Reference of comments is EnergyPlus documentation *InputOuputReference*. This is only included to provide a shorter version of the full explanation. 
  - *Note*. This part categorizes different variables into groups so that user can have a better understanding of what the variable is asked about. This can also help better relate the variables with real system.

# For Other System
