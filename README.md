# MovingTrapSlowerSimulation  
[![Build Status](https://travis-ci.org/SuperYuLu/MovingTrapSlowerSimulation.svg?branch=master)](https://travis-ci.org/SuperYuLu/MovingTrapSlowerSimulation)  
Simulation of a moving magnetic trap for adiabatic decelerating of paramagnetic atoms

## Intro  
Cold atoms physics is studying the interactions between atoms and related physics at extremely low temperatures close to absolute zero. The first step is to have a atomic source with nice properities. In my research the atom source a supersonic atomic beam generated by [Even-Lavie Valve](https://sites.google.com/site/evenlavievalve/home), which has properities such as low transvers temperature, low angular dispersion, high atoms flux, controllable beam pulse parameters, etc. The most beneficial part of this source is that it let us starts with a very cold beam while having a very high flux ( 10^15 atoms / shot). Yet there is only one drawback: the speed of the atomic beam is too fast (500 m/s) in the labtorary frame. To achieve successive cooling and future experiments, one has to bring the atoms to rest in a trap, but slowing the atoms from this high speed while maintain the good properities is always challenging. 
The novelty of our approach is to use a moving magnetic trap which consist of 480 overlapping anti-Helmholtz magnetic fields. The low-field-seekng hyperfine states of alkali atoms will always be trapped at the field potential minimium. By activating these 480 magnetic traps in a properly controlled time-overlapping manner, one can generate effectively a "moving" magentic trap. Thus, slowing down the swithing speed leads to reducing the speed of atoms in the moving trap.  

## How to run  
### Install  

```
git clone git@github.com:SuperYuLu/MovingTrapSlowerSimulation.git
```

### Check  

```
make check
```

### single trap analysis  

```
make singleTrapRun
```

Adding new features.....  

## Results  
### Single trap analysis  
![single trap run](https://github.com/SuperYuLu/MovingTrapSlowerSimulation/blob/master/img/singleTrapRun.png)

