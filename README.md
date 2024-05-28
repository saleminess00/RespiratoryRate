![image](https://github.com/saleminess00/RespiratoryRate/assets/92652356/a40a4a79-572a-4fbb-817b-2c888f27b102)
# About
## Overview
Respiratory rates are vital health indicators used by clinicians. Manual measurement is time-consuming and prone to inaccuracies. This project aims to develop a machine learning method to predict respiratory rates using physiological signals such as ECG, PPG, and impedance pneumography. Accurate, real-time estimation enables continuous monitoring and early detection of respiratory issues.

The ability to predict respiratory rates empowers healthcare providers to monitor patients continuously and identify deviations from normal ranges promptly. This proactive approach can prevent adverse events and optimize patient care, enhancing outcomes and patient safety.

**Note:** My contribution was focused on data analysis and pre-processing.
##  Features

1. breaths ann1 [signal sample no]: Manual annotations of breaths by the first annotator, indicating the sample numbers corresponding to the start and end of each breath.

2. breaths ann2 [signal sample no]: Manual annotations of breaths by the second annotator, indicating the sample numbers corresponding to the start and end of each breath.

3. HR: Heart rate, derived from the ECG signal (beats per minute).

4. PULSE: Pulse rate, derived from the PPG signal (beats per minute).

5. RESP: Respiratory rate, derived from the impedance respiratory signal (breaths per minute).

6. SpO2: Blood oxygen saturation level, expressed as a percentage.

7. RESP: Impedance respiratory signal.

8. PLETH: Photoplethysmogram (PPG) signal.

9. V: Lead V ECG signal.

10. AVR: Lead AVR ECG signal.

11. II: Lead II ECG signal.

These features represent various physiological parameters and signals recorded during the monitoring of critically-ill patients. They provide valuable information for assessing cardiac and respiratory function.
