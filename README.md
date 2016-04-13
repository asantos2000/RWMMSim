RWMMSim
=====================

> Update Apr 13, 2016

> Code updated for run on Mac OS X 10.11.4 and Contiki 3.0

## Roadmap
* Change the Contiki's mobility app to read Bonnmotion mobility scenarios files natively.

## Notes
Script generate-mobility.py depend on python NumPy module. To install it on Mac, try

``` bash
$ sudo port install NumPy
``` 

## References
[1] [A Mobility Scenario Generation and Analysis Tool](http://sys.cs.uos.de/bonnmotion/doc/README.pdf)

[2] [BonnMotion Home](https://sys.cs.uos.de/bonnmotion/index.shtml)

[3] [Utilizando O BonnMotion, Um Gerador De Cenários De Mobilidade](http://www.decom.ufop.br/imobilis/utilizando-o-bonnmotion-um-gerador-de-cenarios-de-mobilidade/)

[4] [Simulating Wireless and Mobile Networks in OMNeT++ The MiXiM Vision](http://www.tevp.net/papers/mixim.pdf)

[5] [Mobility of Nodes in Cooja](http://anrg.usc.edu/contiki/index.php/Mobility_of_Nodes_in_Cooja)

[6] [NumPy v1.11.dev0] (https://docs.scipy.org/doc/numpy-dev/user/quickstart.html)

[7] [CONET Simulation Platform] (http://www.cooperating-objects.eu/testbed-simulation/simulation-platform/)

# Original text

* RWMMSim is a Random Waypoint Mobility Model position data generator for use with
the Contiki COOJA network simulator. It allows you to generate position data for
nodes moving in a simulation, according to some parameters such as time, space, 
speed and duration.

* Now also contains a fork/copy of the actual Cooja plugin. The fork was made 2013-march-27
  from the following address:
  svn://svn.code.sf.net/p/contikiprojects/code/
