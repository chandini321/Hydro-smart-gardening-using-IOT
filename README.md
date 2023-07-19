# Mini-Project
Hydro smart gardening using IOt
This setup contains one yellow,red LED,DHT11,soil moisture sensor and nodeMCU microcontroller.the DHT ground pin connected to the nodemcu G pin, the out pin attached to D1, and the Vcc connected to 3V in the nodemcu.Soil moisture comparator ao pin a0 pin nodemcu and ground and Vcc are identical to dht11. The positive of the led is linked to D5 in the node, while the positive of the resistor is connected to the G pin in the nodemcu.When the soil moisture level is greater than threshold value red LED on.

And coming to the soil moisture sensor working it has a probe with two pins connected with potentiometer,when we put the probe into the mud if the soil is wet it indicates green light. When the soil moisture level is less than the threshold.

Soil moisture takes the values in the form of analog it gives to the comparator and it compares the voltage difference between those values and displays it in the serial monitor of Arduino IDE.

                                        
Our prototype is connected to the system after we write the code in the Arduino IDE and add a deployment id from the Google App Script deployment process. The Arduino serial monitor prints the output after that, and the spreadsheet also stores the values from the humidity and temperature recordings.


In the Arduino code we include the gas id of google appscript by this we can store the temperature and humidity values in it. Google app script code contains the sheet id and for printing the current time and date we use functions in javascript.
