# Mavic air 2 parameter tuning

#### Preamble

#### Most of the techniques and tips discussed on [ma2findings](https://github.com/444A49/ma2findings) are applicable to me, such as commands. If something here doesn't make sense or assumes things you're not familiar with, check the other guide.

## Purpose

By following this guide correctly, your drone should be able to decent and gain height at maximum 10m/s, tuning off LEDs on your drone, remove force landing when the drone is setting on low battery etc.

## Tools

* Drone hacks v1
  
  Drone Hack v2 takes forever to dump all parameters from the drone before you can modify any of the parameter settings. Since all we'll be doing is modifying parameters, use v1 for faster tuning turoughout the process at the cost of using a old software.

* Or Drone hacks v2
  
  Use v2 If you don't mind to wait for a little bit for the parameters to load, it's easier to use most of the time, plus all future updates Drone hacks are gonna post are probably on v2. 

* Windows 10/11
  
  Only tested on windows 11, should also work on wnything that runs drone hacks and edits your drone's parameter for you. 

### Parameters

before we start, I recommend using firmware 01.01.0610 for mavic air 2. this version of the firmware has the most compatability with other mods on drone hack. not necessary, but you might find different parameter value limit on different versions.



## 10m/s desent/gain in altitude

Dji limited the `vert_vel_down` parameter for sport mode to -3 as maximun, to bypass this limit, we need to change the 
