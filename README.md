# Fire-Alarm-System

**Abstract:**
We've developed a GUI enabled file alarm system for CC3 building (IIIT Allahabad). The system
involves inputs of various sensor devices like heat sensor, smoke detector and carbon
monoxide detector. The CC3 building is equipped with all these sensors at various places. Our
system receives the input from these sensors and draws the verdict to generate fire alarm or
not. Furthermore, the system is able to localize the area that initiated the alarm. A
log report is also be maintained to analyse the situation later. This report consists of
details like sensed values, timestamp of alarm, the device which triggered the alarm, etc.
Design
Following are the interface screens and associated functionalities that are developed:
1. Main screen:
  a. Register button:
  A new screen appears to register the sensor along with the
  following details:
    i. Sensor ID: <Textfield> (ID type validation)
    ii. Sensor type: <Dropdown>
    iii. Floor No: <Textfield> (Number type validation)
    iv. Install Location: <Textfield> (Area type validation in CC3 building)
  b. Configuration button:
  A new screen appears to configure:
    i. Threshold of each type of sensor
    ii. Duration of alarm
    iii. Sound of alarm
    iv. Log interval
  c. Start monitoring
  A new screen appears that displays:
    i. Reading being sensed at each sensor.
    ii. If the sensed value crosses the threshold at some location then an alarm
    must be generated along with the message in the display panel showing
    the location of the sensor that triggered the alarm.
    iii. Log report should be generated and saved for the events at regular
    intervals
  d. Stop monitoring
  e. Quit()
