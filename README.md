# Thermostat-Embedded-System
I created a Thermostat prototype that detects temperature, indicates the function of heat on/off and utilizes button interrupts to drive the set temperature all while simulating an upload to the cloud via Wi-Fi that displays the temperature data. This was created to introduce a company into the market of global smart thermostats and I was tasked to develope a prototype to demonstrate functionality.

I think I did well on this project particularly with the state machines that control the switching of operations for the thermostat.

I feel that areas for improvement would be with my task scheduler that runs the thermostat. I could change the code to create specific tasks to then use for loops to iterate through the list of tasks to operate rather than the current method of running if statements in a while loop to switch between the three state machine states.

This thermostat currently requires the use of a TI SimpleLink Wi-Fi CC3220S microcontroller to function.

I feel that this project has given me more experience with microcontrollers and how to figure out driver compatibility and learing how to better read documentation on something I know nothing about. These skill are highly transferable to all aspects of coding projects and work in the future as I have a better understanding of where to look and how to look for certain information.

# Morse-Code-Embedded-System
I created a Morse code unit that uses GPIO interrupts via button input to flash an LED to output SOS or OK in Morse Code. 

