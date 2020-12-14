---
layout: post
title: SDR Respirometry Protocol
date: '2020-12-14'
categories: Protocols
tags: respirometry, coral, physiology
projects: E5, Putnam Lab
---

# SDR Respirometry Protocol

Original: 20201214
Last Revised: 20201214

**Contents**
- [**Supplies**](#Supplies)
- [**LoligoⓇ MicroResp™ Software**](#Loligo_MicroResp_Software)
- [**pH HydroDishⓇ**](#pH_HydroDish)
- [**Oxygen OxoDishⓇ**](#Oxygen_OxoDish)
- [**Initial Setup**](#Initial_Setup)
- [**Sample Preparation**](#Sample_Preparation)
- [**Photosynthesis**](#Photosynthesis)
- [**Respiration**](#Respiration)
- [**pH**](#pH)
- [**Final Checks**](#Final_Checks)
- [**Data Analysis**](#Data_Analysis)
- [**Take-Down and Clean Up**](#Take-Down)

<a name="Supplies"></a> **Supplies**

- 2 PreSens SDR SensorDish® Reader Basic Set [(SDR Information)](https://www.presens.de/products/detail/sdr-sensordish-reader-basic-set)
- 2 PreSens OxoDish® OD24 for oxygen measurements [(PreSens OxoDish® OD24)](https://www.presens.de/products/detail/oxodish-od24)
- 2 PreSens HydroDish® HD24 for pH measurements [(PreSens HydroDish® HD24)](https://www.presens.de/products/detail/hydrodish-hd24)
- LoligoⓇ MicroResp™ Software [(Software Download)](https://www.loligosystems.com/downloads)
- Circular Coverslips (> 48)
- Windows Computer 
- Handheld Temperature Probe 
- 2 AI Aquaillumination Prime™ 16HD Reef Aquarium Lights [(Product Description)](https://www.aquaillumination.com/products/prime)
- Apogee Quantum Light Meter [(User Manual)](https://www.apogeeinstruments.com/content/MQ-500.pdf)
- Kimwipes
- DI Water
- Squeeze Bottle
- Large Towel

<a name="Loligo_MicroResp_Software"></a> **LoligoⓇ MicroResp™ Software**

1. Download and install the LoligoⓇ MicroResp™ Software to a windows computer. Download found here: [(Software Download)](https://www.loligosystems.com/downloads). 
2. See comment 

<a name="pH_HydroDish"></a> **pH HydroDishⓇ**

1.  If interested in measuring pH on the SDR plate, there is a pH HydroDish that has pre-calibrated pH sensors integrated at the bottom of each well and are read out contactless with the SDR SensorDish Reader. It can be ordered here:  [(PreSens pH HydroDish HD24)](https://www.presens.de/products/detail/hydrodish-hd24)


<a name="Oxygen_OxoDish"></a> **Oxygen OxoDishⓇ**

1.   If interested in measuring oxygen on the SDR plate, there is an Oxygen OxoDish  that has pre-calibrated oxygen sensors integrated at the bottom of each well and are read out contactless with the SDR SensorDish Reader. It can be ordered here: [(PreSens OxoDish® OD24)](https://www.presens.de/products/detail/oxodish-od24)


<a name="Initial_Setup"></a>**Initial Setup**

Setting up the SDR sensor plates and accompanying system for the first time in a new place:

1. Suspend an AI light above each SDR plate and follow the [(AI Light Protocol)](https://github.com/urol-e5/protocols/blob/master/2020-03-18-AI-Lights.md) for set up instructions. Notes: make sure to check what saturating light conditions your study organism needs for Photosynthesis trials. To calculate saturating light conditions, follow the [(PI Curve Protocol)](https://github.com/urol-e5/protocols/blob/master/2020-01-01-PI-Curve-Protocol.md)
2. Assemble SDR reader following the [(SDR SensorDish Reader Installation Video)](https://www.youtube.com/watch?v=F0_b4Ws6Eow&feature=youtu.be). Connect the SDR plate readers to the USB port on the computer and open the LoligoⓇ MicroResp™ Software. 
3. To ensure that the correct saturating light level is set on the AI light, follow the [(Apogee User Manual)](https://www.apogeeinstruments.com/content/MQ-500.pdf). Situate the Apogee above the SDR plate and take ~ 8 readings at various positions around the SDR plate to get an average light measurement. Adjust the placement of the SDR plate, light stand, and AI light as necessary to attain desired light intensities. Ideally, light levels should be as equal as possible across the different positions across the 2 SDR plates. Note: In Mo’orea, average saturating light level for *Acropora hyacinthus* larvae should be set at ~500 PFD. 
4.Record the AI light setting and position combinations required to obtain each desired light intensity to use in Photosynthesis trials.
5. See comment 

<a name="Sample_Preparation"></a> **Sample Preparation**

1. Set up SDR respirometry equipment (see [**Initial Setup**](#Initial_Setup) for details). Set oxygen concentration in units of umol/L. 
2. Load samples into wells, loading 22 wells with samples and 2 with FSW as blanks. Randomize the location for each run (see XXX for details). Use 6-8 larvae per well. If possible, run a quick trial in 3-5 wells to see if 6-8 larvae provide a signal in Photosynthesis and Respiration. If necessary, you can include more larvae per well - just record the number of larvae you use. 
3. Seal the plate with coverslips. See video HERE and refer to protocol for details. 
4. Run [**Photosynthesis**](#Photosynthesis) or [**Respiration**](#Respiration) trials.

<a name="Photosynthesis"></a> **Photosynthesis**

1. Turn AI lights on 30% intensity for all channels (~500 PAR). Collect data under light for 30 minutes. Oxygen measurements will appear “jumpy” under the light. Look for an increase in oxygen that is different from the blanks.
2. Run 1 full plate. No need to do more than 1 run unless there is a problem with the first run (lots of bubbles, tech issues, etc.). This should take about 1 hour run time + 1 hour set up/clean up.
3. Export data and save. Label the saved files with the following name format: “Date_RunID”. Because there is only 1 run per day, the format will be: “Date_Run1”. If more runs are needed, use Run2, Run3, etc.

<a name="Respiration"></a> **Respiration**

1. Turn off lights. Collect data under darkness for 30 minutes. Look for a decrease in oxygen that is different from the blanks. Respiration measurements will be much more stable than Photosynthesis measurements.  

<a name="pH"></a> **pH**

1.  

<a name="Final_Checks"></a> **Final Checks**

1. Make sure that the OxoDish or HydroDish are correctly aligned over the middle of the lasers (Insert photo of proper loading)

<a name="Data_Analysis"></a> **Data Analysis**

1. 

<a name="Take-Down"></a> **Take-Down and Clean Up**

1. Stop the MicroResp program. 
2. Disconnect and disassembly the SDR SensorDish Readers carefully and place components back into the SDR SensorDish Reader cases. 
3. Use an alcohol wipe on the cables and wipe with kimwipes. Notes: make sure to avoid the top of the SDR SensorDish Readers and ends of the wires. 
4. Record and export all data to multiple locations (GoogleDrive, GitHub, Computer).
5. Check that all data files appear to have data in proper columns and consistency throughout. If you see any inconsistencies, make sure to redownload data from program or re-run trials before clean up.
6. Remove larvae from wells and either preserve for larval size/biomass measurements, or carefully place back into the stock population.
7. Over a sink, remove any access seawater from the wells. 
8. Use a squeeze bottle filled with DI water to rinse out each individual well and rinse the entire OxoDish or HydroDish with DI water and place on a towel to dry.
9. Rinse the top and bottom of each coverslip with DI water and place on a kimwipe to dry.
10. After all supplies have been dried, put them back in their respective cases. 
