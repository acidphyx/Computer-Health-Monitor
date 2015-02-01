# Computer-Health-Monitor

This is the Source code file I created for my Custom Arduino setup.
The Arduino Monitors upto two +5VSB Rails for V-Drop and if detected attempted to restart the Power Supply or Computer.
It also monitors several tempurature probes using Thermistors wired through voltage divider circuits for safety.

The Status of Power and Tempurature is Output to a LCD Screen with an attached JoyStick, which facilitiates the navigation of the menu.

# Menu Options
  1. Status -> "Displayes Tempuratues and Voltages"
  2. Options -> "A Set of Options Including (Serial Output, Sensor Configuration, Alarms, Auto-Off)" !See NOTE 1 @ bottom!
  3. Power -> "Manually Turn On/Off the attached power supply"
  4. About -> "An About Message"

# NOTE 1

A Large number of the intended functions displayed as menu options were never completed as I ran into the maximum memory limit of the Arduino pretty fast.

  All Status and Auto Monitoring functions Do Work Correctly!
  
As for the Options Menu, only the Serial Output On/Off Switch is functional. The other options in "Options" are only there in menu but have not backend functions to support of facilitate their functionality.

The "Power" Options does work completely.

# NOTE 2 

This is code for a regular Arduino or Arduino Nano. If you would like more information on the custom cirtuits I built the work as the hardware part of this system please contact me @  zwilliams@orbitsystems.ca or Skype @ ZacharyTheTech
