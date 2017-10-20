# Reefcontroller
automated control of a reef aquarium

Who am I?
I am Thomas Devos my year of birth is 1981. I am father of two, girl born 2011, boy born 2015.
I work as a repair technician for the biggest telecom provider in my country. You could say that euhm,  I'm the cable guy  :)

In this project i am going to attempt to automate some aspects of my reef aquarium:
automatic top-of
temperature monitoring and control
ph monitoring and control
salinity monitoring and control
powering the equipment like pumps,lighting and other devices on a schedule or in function of sensor readings

I would like to include things like:
touchscreen for control
graphical user interface
graphing and logging sensor readings
power bar with integrated easy connection points for all the sensors

I would like to achieve these things:
keep it safe (Volt x H2O :):):))
learn cool stuff
do it economically


Lets get started!

After some resarch I already found some like minded people on youtube, on this moment Reefspy, who has is own youtube channel, is uploading a series of videos about how he set up his "REEFBERRYPI".
But also on other places there is a sea of information.

a few things I figured out by now are that I will be using the GPIO pins on my pi to connect sensors and relays to
some sensors wil be digital an some wil be analog. depending on the type the way to connect and use them will vary.

The I2C gpio pins will be used to interface withe the analog sensors.
