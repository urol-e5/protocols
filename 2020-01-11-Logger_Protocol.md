---
layout: post
title: XXXXXXXXX
date: '2020-01-01'
categories: Protocols
tags: loggers, pH, PAR, temperature, conductivity
projects: E5, Putnam Lab
---

# Standard protocol for Collection of Corals from the Field

Original: 220200111   
Last Revised: 20200111

Contents  
- [**HOBO_U24_Conductivity_Logger**](#Conductivity)
- [**HOBO MX pH Logger**](#pH)
- [**Light (PAR) Logger**](#PAR)
- [**HOBO v2 (U22) Temperature Logger**](#Temperature)  

# <a name="Conductivity"></a> **HOBO_U24_Conductivity_Logger**

### Data Download
Following the logger [manual](https://www.onsetcomp.com/files/manual_pdfs/16844-G%20U24-002-C%20Manual.pdf):  
1. Connect the U24 coupler to the base station, and connect the USB cable fron the base station to the laptop.  
2. Align the arrows on the coupler and sensor, and push the sensor into the coupler following the image below.

![logger](https://github.com/urol-e5/protocols/blob/master/images/U24_conductivity.png?raw=true)

3. Start HOBOware on the laptop.  
4. Read out the logger data by clicking the "Readout Device" icon.     
5. Verify the status of the logger and launch as necessary.

### Calibration
Conductivity Solution
RICCA Cat# 2248 Conductivity Standard 50,000 µS/cm at 25°C

Measure a known conductivity standard in the lab at 25°C _**before deployment and after the return of the logger before cleaning**_.  **IF THESE CALIBRATIONS ARE NOT DONE THE DATA ARE USELESS** Here is the logger manual [manual](https://www.onsetcomp.com/files/manual_pdfs/16844-G%20U24-002-C%20Manual.pdf).

Following Method #3: Taking a sample back to the office in a sealable jar to measure there (recommended for locations with conductivity that is stable when you do not have a field meter or it is not convenient to access the logger):
1. Place a sample of the water taken from next to the logger in a jar and immediately seal it to ensure that none of the water evaporates. This allows the specific conductance and salinity of the sample to be maintained, which in turn results in usable temperature and conductivity readings when you measure it with the meter at a later time.
2. Write down the time you take the sample for use later in the HOBOware Conductivity Assistant.
3. At the office, measure the temperature and actual conductivity of the sample with a meter and write down the values next to the time you noted in step 2.

If not water sample was taken, the protocol can be done with a known conductivity standard.
1. Place all conductivity loggers, a temperature probe, and a discrete conductivity probe in a known conductivity standard (50,000 µS/cm at 25°C).  
2. Heat or cool down the solution to 25°C.  
3. Take a discrete conductivity reading at the same time the loggers are scheduled to take a measurement. Take note of the time, temperature, logger conductivity readings, and the discrete conductivity measurement.  

### Deployment

Following the deployment protocol in the logger [manual](https://www.onsetcomp.com/files/manual_pdfs/16844-G%20U24-002-C%20Manual.pdf):  
1. Launch the logger with a laptop or shuttle. *More details added here soon.*
2. Take a calibration reading as described above.  
3. Remove white electrical and copper tape that has fouled over the sampling time period. Re-tape with new electrical and copper tape prior to re-deployment.  
4. Clean the conductivity sensor as necessary (not with sharp objects).   
5. See field image below as an example for deployment.

# <a name="pH"></a> **HOBO MX pH Logger**

**The pH sensor must be kept in storage solution when not being calibrated or deployed in water. The hydration layer surrounding the sensor starts to break down after 10 minutes if the pH sensor is not submerged in storage solution or calibration solution, or deployed in water.**

Following the protocols in the [HOBO MX pH logger manual](https://github.com/urol-e5/protocols/blob/master/22511-M%20MX2501%20Manual.pdf).
### Data Download
1. Download the HOBOmobile app from the App Store® or Google Play™. Open the app and enable bluetooth in device settings.  
2. Wake up the logger by pushing the switch on the mounting end of the logger into the gap beneath the mounting lanyard.  
3. Tape the Devices icon and then tap Loggers at the top of the screen. Tape the logger in the list to connect to it. See image below.  

![pH](https://github.com/urol-e5/protocols/blob/master/images/pH_Max_logger1.PNG?raw=true)

4. Select Readout and the export as a CSV file option.

![ph2](https://github.com/urol-e5/protocols/blob/master/images/pH_Max_logger3.PNG?raw=true)

### Calibration

1. If the sensor is in the storage solution, unscrew the clear storage cap and remove it from the logger.
2. **If you removed the clear storage cap, screw the closure cap onto the logger.**
3. Open HOBOmobile and tap the Devices icon and then tap Loggers at the top of the screen.  
4. Find the logger in the list and tap it to connect to it. If the logger was previously configured with Bluetooth Always Off, press the switch on the logger to wake it up. If the logger was previously configured with Bluetooth Off Water Detect and it is deployed in water, remove it from water.
5. Once connected, tap Yes if prompted to calibrate the logger. Otherwise, select pH Calibration.
6. Select the calibration type (two-point using pH 7.00 and 4.01 solution, two-point using pH 7.00 and 10.00 solution, or three-point using pH 7.00, 4.01, and 10.00 solution). Tap Start Calibration.  

![ph cal](https://github.com/urol-e5/protocols/blob/master/images/pH_Max_logger2.PNG?raw=true)

7. Use a squirt bottle to rinse the pH sensor with deionized or distilled water.  
8. Place the sensor end of the logger in the pH 7.00 solution. Make sure the sensor end cap, temperature sensor, and closure cap are submerged in the solution as shown in the illustration. pH 7.00 buffer will only be 7.00 at 25°C. Follow the instructions on the screen. Once the pH reading is stable, tap Confirm Buffer.  
9. Rinse the pH sensor with deionized or distilled water again. Tap Next Buffer.  
10. Place the sensor end of the logger in either the pH 4.01 or 10.00 solution as prompted, making sure the sensor end cap, temperature sensor, and closure cap are submerged in the solution. Follow the instructions on the screen. Once the pH reading is stable, tap Confirm Buffer.   
11. Tap Save Calibration.
12. Rinse the pH sensor with deionized or distilled water again. **If you will not be deploying the logger immediately, place the pH electrode in storage solution.**

### Deployment

1. Launch the logger as necessary.   
2. Take a calibration reading as described above.  
3. Remove white electrical and copper tape that has fouled over the sampling time period. Re-tape with new electrical and copper tape prior to re-deployment.  
4. **Make sure to bring closure caps on the boat to re-attach after removing pH storage solution on the boat.**   
5. See field image below as an example for deployment.

# <a name="PAR"></a> **Light (PAR) Logger**

### Data Download

Following the protocol in the [Xtract](https://github.com/urol-e5/protocols/blob/master/Xtract%20User%20Manual.pdf) and [Xpert](https://github.com/urol-e5/protocols/blob/master/Xpert%20User%20Manual.pdf) manuals for data download.

### Calibration

Following the protocol in the Odyssey Xtreem [user manual](https://github.com/urol-e5/protocols/blob/master/Odyssey%20Xtreem%20PAR%20Logger%20User%20Manual.pdf).

### Deployment

1. Launch the logger as necessary.   
2. Remove white electrical and copper tape that has fouled over the sampling time period. Re-tape with new electrical and copper tape prior to re-deployment.  
3. See field image below as an example for deployment.

# <a name="Temperature"></a> **HOBO v2 (U22) Temperature Logger**

### Data Download
Following the logger [manual](https://github.com/urol-e5/protocols/blob/master/10366-I_U22-001_Temp_Manual.pdf):  
1. Connect the U22 coupler to the base station, and connect the USB cable fron the base station to the laptop.  
2. Align the arrows on the coupler and sensor, and push the sensor into the coupler following the image below.

![logger](https://github.com/urol-e5/protocols/blob/master/images/tempU22_logger.png?raw=true)

3. Start HOBOware on the laptop.  
4. Read out the logger data by clicking the "Readout Device" icon.     
5. Verify the status of the logger and launch as necessary.

### Calibration

Cross calibrate the loggers betweeb each deployment in a bucket of water outdoors at the lab. Log temperature manually at the corresponding logger time with the digitial traceable thermometer.

### Deployment

1. Launch the logger using the base station and laptop as necessary.  
2. Remove white electrical and copper tape that has fouled over the sampling time period. Re-tape with new electrical and copper tape prior to re-deployment.  
3. See field image below as an example for deployment.

# E5 sensor deployment

![loggers](https://github.com/urol-e5/protocols/blob/master/images/correct_sensor_deployment.png?raw=true)
