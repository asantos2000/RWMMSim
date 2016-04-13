RWMMSim
=====================

> Update Apr 13, 2016

> Code updated for run on Mac OS X 10.11.4 and Contiki 3.0

## Roadmap
* Change the Contiki's mobility app to read Bonnmotion mobility scenarios files natively

## Notes
Script generate-mobility.py depend on python NumPy module. To install it on Mac, try

``` bash
$ sudo port install NumPy
``` 

# Original text

* RWMMSim is a Random Waypoint Mobility Model position data generator for use with
the Contiki COOJA network simulator. It allows you to generate position data for
nodes moving in a simulation, according to some parameters such as time, space, 
speed and duration.

* Now also contains a fork/copy of the actual Cooja plugin. The fork was made 2013-march-27
  from the following address:
  svn://svn.code.sf.net/p/contikiprojects/code/
