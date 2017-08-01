## Welcome

Thank you for visiting my portfolio. _This is not intended to be a comprehensive resume._ Here I will upload open source projects I have completed as well as describe my past accomplishments. If you would like to know more about me or view my resume, visit [LinkedIn.](https://www.linkedin.com/in/joshglenen/)

### My C# Projects

**Talking Clock:** [Link]https://github.com/joshglenen/Portfolio/tree/master/Talking%20Clock)
  
`A simple lightweight system tray application for Windows 10 that announces the hour every hour.`

**Notify Me:** [Link](https://github.com/joshglenen/Portfolio/tree/master/Talking%20Clock)

`Another system tray application that builds off of "Talking Clock". This low resource application allows you to create custom and       recurring notifications for Windows 10 with ease.`


### My Capstone Project

My capstone project was "Improving the Safety of Powered Wheelchairs and Scooters." Throughout the 2016-2017 year, I studied and learned the principals on powered wheelchair controllers, Bluetooth Low Energy, low power electronics (including batteries, beacons, RFID, WIFI), 3D printing, Android development, 3D printing, antenna design, and project management. I worked with team members Hassan and Yuan to develop an idea into a fully functioning and cheaply reproducible prototype. We were recruited to fulfill a need by our client to allow trainers or parents of powered wheelchair and scooter patients to have control of the machines from a distance. Our product would improve the lives of both trainers and patients by reducing accidents and injuries that would otherwise be avoidable.

My responsibility on the project involved producing the code to allow the custom micro-sized Arduino embedded BLE system to operate alongside an application. Various iterations of the design where examined including using a separate button controller, using an iPhone App, and creating a proximity activated shut-down zone to prevent Powered vehicles from entering dangerous areas or leaving the training area. These ideas where not fulfilled during the development due to either design or cost constraints. The deliverable for my project was to create a device which stops a powered wheelchair or scooter while not being invasive by accessing the internal controls of the machine. The device needed to compete with expensive and rudimentary products already available by being cheaper, more compact, and more convenient.

Other deliverables were to create a working prototype, test its performance, and access the market potential. Together, my team successfully created a $30 prototype which was 6x3x3 cubic centimeters and plugged into the charging port that is standard in most but not all powered wheelchairs and scooters. The cost of the prototype does not include assembly or sales costs; however, mass production would greatly reduce the cost of the parts. This device fed off the machines built in power supply and consumed a maximum of 0.4W. This consumption could be lowered to an average of 0.1W by using a different voltage converter that adds another 3$ on the manufacturing price. The power consumption was deemed to be insignificant due to the size of conventional powered wheelchair batteries. Below are pictures of the 3D case which holds the modified embedded system as well as our final simplified circuit diagram.

<p align="center"> 
<img src="Capstone Project/image001.png">
</p>
<p align="center"> 
<img src="Capstone Project/image003.png">
</p>
<p align="center"> 
<img src="Capstone Project/image009.png">
</p>

An android app was also created and can be found by clicking this **[Link](https://play.google.com/store/apps/details?id=tartanrehab.timeoutbutton&hl=en).** This application was my focus on the project along with research and circuit design. The application will detect the BLE IC when the prototype is plugged in and will provide the option to connect. Once connected, a trainer could trigger an alarm or stop the machine. During testing, it was found that the machines could take up to a meter to stop at top speed; however, this also depended on the manufacturer and the controller's programming. This means that the deceleration of each machine would require a technician to alter the programming which is specific to each manufacturer. Once stopped and the danger averted, the prototype automatically returns the control to the machine's user to operate as normal.

In conclusion, my team developed a way for a technician or parent to prevent accident or injury to a powered wheelchair or scooter user. My team created a more compact (6x3x3 cubic centimeters), cheaper ($30), and more convenient (Android app). During this project, I became more experienced in the development process, project management, and greatly increased my programming skills beyond what I'd previously thought possible for myself. My team's product has significant potential for the future and could eventually be deployed to rehabilitation centres around the world. I look forward to the opportunity to complete similar projects that will allow me to improve my skills and help improve the safety of people’s lives.

### Remarks

This page was last updated 8/1/2017 and is not yet complete. 

