# About This Guide

This guide is created for "Human-in-the-loop Sensing and Control for Commercial Building Energy Efficiency and Occupant Comfort" research project at Carnegie Mellon University. It aims to provide an introduction to using EnergyPlus to estimate energy consumption of a single thermal zone, instead of a complete building. Considering the easiness of using Windows version to create the model from scratch, this guide focuses on the Windows version of EnergyPlus. 

# Directory Descriptions

1. EnergyPlus Introduction;
1. HVAC System;
2. Construction;
3. Scheduling;
4. Example (CMU Scott Hall Room 6002)

# Download and Versions

To install EnergyPlus, simply visit the EnergyPlus official website: https://energyplus.net/downloads. Choose the correct version to install.

EnergyPlus has two different versions for Mac system and Windows. Both perform the simulation and would be able to generate outputs. However, there're several differences:

1. IDF-Editor not available for Mac. While being a handy tool to edit EnergyPlus input idf file, the intallation of EnergyPlus on Mac does not contain IDF-Editor. Windows version does have this useful tool.

2. Less output files for Mac. Some files cannot be generated from the simulation on a Mac EnergyPlus. For example:
   - .svg drawing file: contains diagram of HVAC system;
   - .csv meter file: contains the detailed summary of output variables added by user in the idf file;

# Run EnergyPlus:

The interface that is used to run the simulation is called EP-Launch for a Windows system and EP-Launch-Lite on a Mac. 

On a Mac, an icon will be put in the APPs interface. Current version of EnergyPlus (8.9.0) will have both EP-Launch-Lite and IDFVersionUpdater icons installed. 

On a Windows, EnergyPlus needs to be run in the installed directory of the whole package. Copying the icon to desktop and open directly from desktop won't work. 

After open EP-Launch/EP-Launch-Lite, choose the input idf file and weather file, click "simulate" and wait for result.

# Reference

EnergyPlus Version 8.9.0 Documentation - Getting Started. U.S. Department of Energy, 23 Mar. 2018, energyplus.net/sites/all/modules/custom/nrel_custom/pdfs/pdfs_v8.9.0/GettingStarted.pdf. 
