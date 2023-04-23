<h1> CS 350 Portfolio </h1>
<h2><b>Summarize the project and what problem it was solving</b></h2>
The purpose of this project was to create a prototype of a smart thermostat using the TI board. For the prototype, it used the TMP006 temperature sensor to read the room temperature (via I2C), an LED to indicate the output to the thermostat where LED on = heat on (via GPIO), two buttons to increase and decrease the set temperature (via GPIO interrupt), and the UART to simulate the data being sent to the server.
<br><br>
<h2><b>What did you do particularly well</b></h2>
I feel I was able to create a well designed task scheduler that helped make laying out and designing the code a lot easier. With creating the logic in the diagram, I was able to come up with the IF/ELSE statements that corresponded to these tasks.
<br><br>
<h2><b>Where could you improve?</b></h2>
With all the TI board has to offer, and my limited knowledge of embedded systems, I am sure there are plenty of features that I can leverage from the board to help make it behave and look like a smart thermostat. This project kept it very basic, and as my knowledge increases, I am sure my coding would change with my understanding of how the board functions.
<br><br>
<h2><b>What tools and/or resources are you adding to your support network?</b></h2>
I am adding the experience using C (first time using this language) to encodean embbedded system. This class was my firdt exposure to embedded systems, so the first part of the class was a little rough, but it ended up being a lot of fun seeing the results after each milestone.
<br><br>
<h2><b>What skills from this project will be particularly transferable to other projects and/or course work?</b></h2>
Skill wise, I feel that making sure I have a good diagram/documentation (state machine diagram/task scheduler for embedded systems) is something that would be transferable to other projects and  course work. It helps you understand what is needed from the programming and lays out directions as to what parts are going to be needed. It also helps determine what parts of code may be reusable in different parts of a program. Non-skill wise, I learned not to judge from a first look. I was not too particularly excited at first when class started, but when I got into it and really saw the control over the board that I could have, I got excited seeing the results that I needed to achieve.
<br><br>
<h2><b>How did you make this project maintainable, readable, and adaptable?</b></h2>
I made sure to follow to the best of my knowledge industry standards when writing the code. I made sure to add plenty of comments to explain the purpose of my code, and kept it in a logical order. With the way the code is written, if more functionality would be required down the line, or say there would need to be adjustments made to certain default values like how often the information is written to the console, or how often the temperature is checked, these can be easily added or changed because of the way the code was set up and how readable to code is. 
