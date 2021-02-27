# ArduinoGitAction

Testing auto compile and binary release for arduino sketches. The idea being that the binaries can be downloaded and flashed directly onto the Arduino
through the Dcc++ EX commandline interface automatically ... No IDE / No compiling etc.. for flashing required anymore
Basically : install the cli; put together the CS; hook it up to the serial port ( you still have to know which one is the right one ); start the cli; open the serial port; run upload
this will pull the latest release from github and flash it onto the arduino. Subsequent configuration of the CS will be done through the CLI ( WiFi, network etc etc )