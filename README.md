## Welcome

Thank you for visiting my portfolio. I will link the open source projects I have completed since my graduation while I extend my knowledge and improve my skills. I am currently looking for work as an electrical/software engineer. [Here is my resume.](https://github.com/joshglenen/Portfolio/blob/master/images/Resume%20of%20Josh%20Glenen.pdf) Feel free to visit my [LinkedIn](https://www.linkedin.com/in/joshglenen/) or [email me](mailto:josh.glenen.contact@gmail.com) for more information.



### Python Applications

**Movie Rating Recalculator:** [Link to website](https://raterecal.herokuapp.com/) / [Source](https://github.com/joshglenen/Rating-Recalculator/)

`A python web app that retrieves the ratings of a movie or tv show from imdb.com and recalculates the ratings. Ratings are adjusted to remove the impact of users that purposly give the highest or lowest possible score in order to manuipulate the average. Future plans involve creating a browser extention to make the process faster and remove the need for the slow free-dynomos provided by heroku.

Updated 2017-11-21 to work with the most recent IMDB iteration.`



### C# Applications

**Talking Clock:** [Source](https://github.com/joshglenen/Talking-Clock/)
  
`A simple lightweight system tray application for Windows 10 that announces the hour every hour. Created while learning about c# app development.`

**Texas Hold'em:** [Source](https://github.com/joshglenen/TexasHoldEm/)

`A complex card game that was built off the principals learned from my Black Jack app. Currently expanding to allow for both visual assets and probability calculations within the application. Current design is to train an individual new to the game to understand the probabilities that govern player choices. Still in development.`

**Notify Me:** [Source](https://github.com/joshglenen/Notify-Me/)

`Another system tray application that builds off of "Talking Clock". This low resource application allows you to create custom and       recurring notifications for Windows 10 with ease. Currently discontinued due to lack of potential interest.`

**Black Jack:** [Source](https://github.com/joshglenen/BlackJack/)

`A simple program using c# and the first Windows application I created.`


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

