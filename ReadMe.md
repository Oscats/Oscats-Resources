# Oscats Resources Page

On this page, you can find links to much of the documentation for the products we use. This will begin as a programming reference, but the hope is that it will grow over time.
Here are some quick links to sections of this page...

## Index

- [Oscats Resources Page](#oscats-resources-page)
  - [Index](#index)
  - [Programming Resources](#programming-resources)
  - [FRC Robot](#frc-robot)
    - [VMXPi](#vmxpi)
    - [Vendor Libraries](#vendor-libraries)
    - [Vision](#vision)
  - [Non-FRC](#non-frc)
  - [Flow Charts](#flow-charts)

## Programming Resources

- [WPILib](https://docs.wpilib.org/en/stable/) has all the resources we need to learn how to program a robot. We will be utilizing this resource frequently.

This is outdated, but I am keeping it here as it is a bit clearer in some ways than Docs.wpilib.org--- [Programming Done Right](https://frc-pdr.readthedocs.io/en/latest/index.html) This is a helpful resource with examples from all three main languages. It has tutorial websites as well as how to program a robot to win competitions. Some of the code may be a bit outdated, but is still a premium resource.

Do you want to learn a language from scratch? PDR recommends this site. It has an intro course for free in each of the following languages.

- [Java](https://www.tutorialspoint.com/java/index.htm)
- [C++](https://www.tutorialspoint.com/cplusplus/index.htm)
- [Python](https://www.tutorialspoint.com/python3/index.htm)
  
- [w3Schools](https://www.w3schools.com/) If you find yourself bored with the sites above or needing a quick resource, you cannot get much better than this. How do I do x in y language? This should have the answer. I learned Javascript and JSON syntax through this site exclusively.
  - [Python](https://www.w3schools.com/python/default.asp)
  - [Java](https://www.w3schools.com/java/default.asp)
  - [C++](https://www.w3schools.com/cpp/cpp_syntax.asp)

[Back to the Index](#Index)

## FRC Robot

- [WPILib](https://docs.wpilib.org/en/stable/)
- [Romi](https://docs.wpilib.org/en/stable/docs/romi-robot/index.html)

- [RobotPy](https://robotpy.readthedocs.io/en/stable/)

### VMXPi

- [Vmx-Pi](https://pdocs.kauailabs.com/vmx-pi/software/vmx-pi-for-frc-2020-robot-programming/vmx-pi-for-frc-documentation/)
- [Titan Motor Controller](https://docs.wsr.studica.com/en/latest/docs/GettingStarted/index.html)
  
[Back to the Index](#Index)

### Vendor Libraries

- Kuai Labs They make...
  - [Navx IMU](https://pdocs.kauailabs.com/navx-mxp/)
  - [VMX-Pi](https://pdocs.kauailabs.com/vmx-pi/software/vmx-pi-for-frc-2020-robot-programming/vmx-pi-for-frc-documentation/)
- [C.T.R.E.](https://docs.ctre-phoenix.com/en/stable/) They make...
  - Talon (FX and SRX) Motor Controllers
  - Victor (SPX) Motor Controllers
  - Pigeon IMU
- [Rev Robotics](https://docs.revrobotics.com/docs/first-robotics-competition)  They make...
  - Spark Max Motor Controller
  - Neo Brushless Motor
  - Neo 550 Brushless Motor
  - Ultra Planetary Gearbox <- Mechanical
  - [Color Sensor](https://docs.revrobotics.com/color-sensor/application-examples#frc-application)
  - [Analog Pressure Switch](https://www.revrobotics.com/content/docs/REV-11-1107-DS.pdf)
  - [2m Distance Sensor](https://github.com/REVrobotics/2m-Distance-Sensor)
  
[Back to the Index](#Index)

### Vision

- [Limelight](https://docs.limelightvision.io/en/latest/) The Limelight has become standard in FRC implementation, but we are beginning to find some better options as well
- [Photon](https://docs.photonvision.org/en/latest/) This is like a limelight, but it works on any Pi, is faster, and supports 3d imaging with solve PNP
- [Photon NetworkTables API](https://docs.photonvision.org/en/latest/docs/programming/nt-api/nt-api.html) Since Photon does not have raspberry pi binaries, the best way to use it on the VMX-Pi is to use network tables.
- [Photon Code Examples](https://docs.photonvision.org/en/latest/docs/examples/index.html) These example tutorials are wonderful. On the VMX Pi, we need to use the older [PID Controller Class](https://docs.wpilib.org/en/2020/docs/software/advanced-control/controllers/pidcontroller.html).
- [WPILibPi](https://docs.wpilib.org/en/stable/docs/software/vision-processing/wpilibpi/index.html) This is the image for the Romi, but it also doubles as a Vision pipeline image. It is probably better to use one of the other options for ease of access. Yet, for customization and Machine Learning options, this is the place to be

[Back to the Index](#Index)

## Non-FRC

- Finch
  - [Installation](https://www.birdbraintechnologies.com/finch/java/install/1-1)
  - [Tutorials](https://www.birdbraintechnologies.com/finch/java/program/)
  - [Makecode](https://www.birdbraintechnologies.com/finch/makecode/)
- [Maqueen](https://github.com/MrRSquared/Oscats-Hackathon/blob/main/Robots/Non-FRC/Maqueen/Maqueen_Plus_Getting_Started_Tutorial_MakeCode-master)
- [Zumo](https://github.com/MrRSquared/Oscats-Hackathon/tree/main/Robots/Non-FRC/Zumo)
  - [Zumo rules](http://robogames.net/rules/all-sumo.php) (The Zumo bots we have are in the mini category)
  
[Back to the Index](#Index)

## Flow Charts

 As our code gets more complex, thinking through our processes will be helpful. Flow charts are a wonderful way to do so.
You may use [LucidCharts](https://lucidchart.com) to create your own flowcharts. There is an [entire vocabulary](https://www.gliffy.com/blog/guide-to-flowchart-symbols) of flowchart icons, but you could use whichever for now,as long as you know what the icons you choose represent as you intend them (and will be able to do so later).

[Back to the Index](#Index)
