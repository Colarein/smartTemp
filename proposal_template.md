# Project Name
#### Student Name: *Caroline Conway*   Student ID: *20095353*

TODO: To create a smart heating system/Thermostat in a house which only has a traditional gas boiler. The thought process behind this is to keep the house at a comfortable temperature but also not using the heating on days that it is not required. Traditional timer systems are not able to discern the temperature so this is why were are looking to implement this. If you leave the heating on constant it can be easy to forget to turn it off, while working from home or busy studying. To write a program that pings google weather and reads in the current temperature in Clonmel. We would also like to be able to track this via a website aswell as the home temp data.


## Tools, Technologies and Equipment

TODO: Write a list of things you propose to use in your work. This can be hardware, programming languages etc.

Write a script which uses the command line to turn ping google weather every mooning at 6am and updates the website with the weather of the day. These Scripts will be linked to a smartbot which is a device that makes any switch such as a light switch or the heating switch a smart switch. 

Have 3 programmes/schedules to take certain actions which will be depending on the time:

6am - 7am Morning Call Wake Up: Reads in the temperature at 6am and if temp is 8-14 degrees activates heatign at 6.30am and turns it off at 7am.
If temps is 8 degrees or lower turns on heating at 6am instead or perhaps once the desired internal house temperature has been reached. 

7am - 9pm Daytime Programe:
The temperature will be updated on the website every hour from 6am, after 7am the daytime programe will activate until 9pm.  The temperature will be check once an hour on the hour. If the temperature has dropped below the desired temperature threshold of 18 degrees, then the heating will turn on.

9pm to 6am: Night time programme: Check temperature once an hour and only activate if temperature goes below 10degrees. Sends an email when this happens as a reminder that perhaps the night time program should be adjusted if this happens often.

Raspberry Pi - linked with a DS18B20 temperature senseor- will read and send the temperature and will also displays the last recorded temperature.

Website Similiar to weather top too- will have a house temperature chart of the previous day which displays house temperature in one line of the graph and indicates at what point the heating was turned on.

Create a calculation of Heating x Cost to calculate how much the heating is costing each day.
Have this be Compared to the traditional timer method to show energy saved or money saved. Some days this may be more expensive.
Compare timed heating vs heating turned on manually to measure the effectiveness of the programs.

## Project Repository
TODO: Create a repository for your project. You can add this proposal to it!