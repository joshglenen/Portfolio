## Welcome

Thank you for visiting my portfolio. I will link the open source projects I have completed since my graduation while I extend my knowledge and improve my skills. I am currently looking for work as an electrical/software engineer. [Here is my resume.](https://github.com/joshglenen/Portfolio/blob/master/images/Resume%20of%20Josh%20Glenen.pdf) Feel free to visit my [LinkedIn](https://www.linkedin.com/in/joshglenen/) or [email me](mailto:josh.glenen.contact@gmail.com) for more information.

### Python Applications

**Movie Rating Recalculator:** [Link to web app (slow)](https://raterecal.herokuapp.com/) / [Source files](https://github.com/joshglenen/Rating-Recalculator/)

`A python web app that retrieves the ratings of a movie or tv show from imdb.com and recalculates the ratings. Ratings are adjusted to remove the impact of users that purposly give the highest or lowest possible score in order to manuipulate the average.`

`Future plans involve creating a browser extention to make the process faster and more convenient as the heroku service currently being used is very slow and often unreliable.`

### C# Applications

**Texas Hold'em:** [Source files](https://github.com/joshglenen/TexasHoldEm/)

`A single player card game designed to teach a player the rules of the game along with the probabilities that govern different outcomes. Features a complete GUI, a simple AI algorithm, a leaderboard system, and a back-end that can easily be expanded to allow additional card game types.`

**Talking Clock:** [Source files](https://github.com/joshglenen/Talking-Clock/)
  
`A simple lightweight system tray application for Windows 10 that announces the hour every hour. Created while learning about c# app development.`

**Black Jack:** [Source files](https://github.com/joshglenen/BlackJack/)

`A very simple Windows program created using c#. My first c# program.`

**Notify Me:** [Source files](https://github.com/joshglenen/Notify-Me/)

`A complex system tray application that builds off of my earlier work. This low resource application will allow you to create custom and recurring notifications for Windows 10 with ease. Currently not being developed but may complete in the future.`

### C++ Scripts

**Project Echo:** [Source files](https://github.com/joshglenen/Project-Echo/)

`A c++ script that will eventually be able to determine the location of a sound's origin based on the input of two microphones embedded in a robotic head similar to the human ears. Still early in development as the fft is much more difficult to implement in c++ than it is in python, MatLab, and LabView.`

### Capstone Project

My capstone project was "Improving the Safety of Powered Wheelchairs and Scooters." Throughout the 2016-2017 year, I studied and learned the principals on powered wheelchair controllers, Bluetooth Low Energy, low power electronics (including power supplies, beacons, RFID, WIFI), 3D printing, Android development, antenna design, and project management. I worked with my team members to develop our client's need into a fully functioning and cheaply reproducible prototype. We were recruited by our client to provide a means for trainers or parents of powered wheelchair and scooter patients to have control of the machines from a distance. Our product would improve the lives of both trainers and patients by reducing accidents and injuries that would otherwise be avoidable.

My responsibility on the project involved producing the code to allow the custom micro-sized Arduino embedded BLE system to operate alongside an application. Various iterations of the design where examined including using a separate button controller, using an iPhone App, and creating a proximity activated shut-down zone to prevent Powered vehicles from entering dangerous areas or leaving the training area. The scope for my project was to create a device which stops a powered wheelchair or scooter while not being invasive by accessing the internal controls of the machine. The device needed to compete with expensive and rudimentary products already available by being cheaper, more compact, and more convenient.

The deliverables were to create a working prototype, test its performance, and access the market potential. Together, my team successfully created a $30 prototype which was 6x3x3 cubic centimeters and plugged into the charging port that is standard in most powered wheelchairs and scooters. This device fed off the machines built in power supply and consumed a maximum of 0.4W. Our final desing reduced this consuption to 0.1W and it is possible to reduce that amount even further with a different microcontroller. The power consumption was ulimatly deemed to be insignificant due to the size of conventional powered wheelchair batteries. Below are pictures of the 3D case which holds the modified embedded system as well as our final simplified circuit diagram.

<p align="center"> 
<img src="images/image001.png">
</p>
<p align="center"> 
<img src="images/image003.png">
</p>

An android app was also created and can be found by clicking this **[Link](https://play.google.com/store/apps/details?id=tartanrehab.timeoutbutton&hl=en).** This application was one of my focuses on the project along with research and circuit design. The application will detect the BLE IC when the prototype is plugged in and will provide the option to connect. Once connected, a trainer could trigger an alarm or stop the machine. During testing, it was found that the machines could take up to 1.5 seconds to stop which meant that our product would only be effective at slow to medium operating speeds. 

In conclusion, my team developed a way for a technician or parent to prevent accident or injury to a powered wheelchair or scooter user. My team created a more compact (6x3x3 cubic centimeters), cheaper ($30), and more convenient (Android app). During this project, I became more experienced in the development process, project management, and greatly increased my programming skills beyond what I'd previously thought possible for myself. My team's product has significant potential for the future and could eventually be deployed to rehabilitation centres around the world. I look forward to the opportunity to complete similar projects that will allow me to improve my skills and help improve the safety of people’s lives.

### Remarks

Last updated 2017-11-21

