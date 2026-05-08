# CIPE-WRO-2026
Team Cipe Wro future engineers project 


Hello and welcome to the collaborative project from Oliver and Gerli.

All fothos and diagramms are under branch Photo. 


Our car:
•body (skeleton)
•motors and useges
•camera
•button
•Brain and battery



BODY

The body was designed in tinkercad and 3D printed. We downsised the car for mobility as the previous module didn't turn as well.
For intrest here is the 3D module of all the pices that were used in building the cars body. 
https://www.tinkercad.com/things/bGn80zf6chB-powerful-kieran/edit?returnTo=%2Fthings%2FbGn80zf6chB-powerful-kieran&sharecode=TpZ5YribnzESrsAAGL8cDnb4Db5TR1IsGgDdK0VczvQ
Small screws and bolts were used to hold everything together (any brand/type will do). Hot glue is used only if there is no other way to hold pices together. Car wheles are the most commonly used wheeles for DIY Arduino projects. (diy -do it yourself)
Can be found under serch: Arduino wheel

But we ended up going with a difret car.


We used the Base of a remote controlled car wich worked perfectly. We fixed up the tiers. Any toy car will do. We added the rest of the mechanism to it.



MOTORS

Our robot has 2 motors, one for steering and one for driving forward and backwards. For steering, at the frot, is used a 5V DC motor motor as it is comoackt enough to not bulk up the car and strong enough to still turn the wheels. For driving we use the 12V DC motor, though it isnt as small its still powerful enough to move thrpe car at a faster pase and simultaneously also being able to carry along the rest of the technology on the car, without giving out.
In case of a motor breaking or burning out they are easy to replace, even though it might be a bit incomplete as it requires a bit of patience. Motor driver vas used to get them to work.


CAMERA 

The camera for use is ESP 32 Camera module. Edga impulse was used in writing the program to recognize shapes/objects. The object recognition program was based of off a controllgroup of picktures. The testing of the camera was done on a seprete setup from the car wich is seen on the pickture. The camera diagramm is also included where its simpler to understand how everything was built.  In a new environment te camera needs to be recalibrated with new pictures. To connect thr camera was used USB-TTL converter.
On eiter side of the car there is a ultrasonic sensor, wich pakes sure that the car drives further away from the wall and if to far from a wall closer so to not drive into something else.


BUTTON

A swich was added to start the programm.

BRAIN & BATTERY

For programming we use arduino uno with c and c++ code. We use a battery for arduino and the camera. For the motors we use a battery pack. 
