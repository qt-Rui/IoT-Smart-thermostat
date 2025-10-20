- Summarize the project and what problem it was solving.

This project involves a RaspberryPi 4 with an Ubuntu server installed for the operating system. Connected to the RaspberryPi, there is a breadboard with an LCD, buttons, and LEDs attached to the breadboard. There is also a humidity sensor attached which has the ability of reading the current temperature of the location it is in. The combination of this setup and the script that was developed allowed me to make a setup for a thermostat which allows the user to see what the current temperature is and then choose to either turn on heating or cooling to adjust the temperature of the room. If the room is hotter than desired when on heating, or if the room is colder than the desired temperature when on cooling, the LEDs will signal that to the user to let the user know. The LCD will constantly display the temperature, date, time, and humidity, and the buttons provide the functionality that this setup needs to control the desired temperature and whether the system is on heating, cooling, or off. Ultimately, this provides the user with an easily controllable and readable thermostat for a system. 


- What did you do particularly well?

I believe that my dedication to fixing any issues that I ran into is what made me strongest going through this project. Starting from the very beginning, I had issues with the connection between the breadboard and RaspberryPi, and I could not figure out a solution, so I spent countless hours trying to narrow down what the problem could potentially be. Not every situation was this bad, but each time I had an issue like this, I dedicated my time to figuring out the root cause of the issue, and as a result, I was able to learn more and gain a deeper understanding of my system and the way that it works. Compared to the first week where I was completely clueless about what I was even looking at, I can confidently say that I gained invaluable experience and knowledge through fighting the errors until I gained a solution each time.


- Where could you improve?
  
To be completely fair to myself, I feel like I could massively improve in all areas, but if I had to choose one area to focus on more than others, it would be my ability to code and put the python script together. I want to spend even more time familiarizing myself with the functionality between the GPIO breakout board and my code because the ability to make my code influence objects in the real world intrigues me, and I one day wish to get into robotics on my own. So therefore, knowing more about how to put code together correctly and securely will be invaluable for me in my journey on creating my own sort of invention. 


- What tools and/or resources are you adding to your support network?

I have always wanted to mess with a RaspberryPi because of the capabilities it has in being anything you want it to be, like a surveillance camera, or a media player. Now that I have actually gotten hands on with a RaspberryPi, I will only be continuing my experience with it by incorporating resources we have used in the course like the statemachine library and gpiozero for hardware control alongside newer resources to explore the limits of it. I will continue to use Python and the packages that it provides which give functionality and expands the usability and versatility of the RaspberryPi.

- What skills from this project will be particularly transferable to other projects and/or course work?

Moving forward, the experience and knowledge I gained pertaining to state machine designs and hardware/software integration is invaluable alongside what I learned about when it pertains to peripheral communication and multi-threaded application management. It will carry over to future professional projects that also involve embedded systems and help me in getting started on my own personal projects.

- How did you make this project maintainable, readable, and adaptable?

The code contains detailed comments and clear class and variable names that prevent confusion and help someone looking over the code to quickly understand what the code does every piece and part of the way. The modular design allows for easy modification of components like the sensors and the display. With it being easy to read, maintain, and adapt, it gives the capability of being reapplied to other projects. 
