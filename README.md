# About This Guide

This guide is created for "Human-in-the-loop Sensing and Control for Commercial Building Energy Efficiency and Occupant Comfort" research project at Carnegie Mellon University. It aims to provide an introduction to using EnergyPlus to estimate energy consumption of a single thermal zone, instead of a complete building. Considering the easiness of using Windows version to create the model from scratch, this guide focuses on the Windows version of EnergyPlus. 

# Directory Descriptions

1. Introduction
   - There are two files in this directory. The pdf file provides detailed description, while the power point can be referred to as an outline of the pdf guide.
   - This guide include introduction to basics of EnergyPlus. It also includes a description of the overall building scheme of an EnergyPlus model. For more detailed descriptions of specific step or for an example, please see Example directory.
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
   - .csv meter file: contains the detailed summary of output variables added by user in the idf file. This file will be generated if requested in idf input file on Windows EnergyPlus, but not on Mac's EP-Launch-Lite.

# Run EnergyPlus:

The interface that is used to run the simulation is called EP-Launch for a Windows system and EP-Launch-Lite on a Mac. 

On a Mac, an icon will be put in the APPs interface. Current version of EnergyPlus (8.9.0) will have both EP-Launch-Lite and IDFVersionUpdater icons installed. 

On a Windows, EnergyPlus needs to be run in the installed directory of the whole package. Copying the icon to desktop and open directly from desktop won't work. 

After open EP-Launch/EP-Launch-Lite, choose the input idf file and weather file, click "simulate" and wait for result.

# Further Information

This guide is created by Sally Chen from Civil and Environmental Engineering department at Carnegie Mellon University. It is not created as a complete user guide for EnergyPlus and I have also not fully explored all modules of EnergyPlus. It is only created in order to provide help in building simple model, since I had a hard time building the model. Please contact me at kexinc@andrew.cmu.edu for any confusion or any correction to this guide.

# Reference

EnergyPlus Version 8.9.0 Documentation - Getting Started. U.S. Department of Energy, 23 Mar. 2018, energyplus.net/sites/all/modules/custom/nrel_custom/pdfs/pdfs_v8.9.0/GettingStarted.pdf. 
