## scenario Demo

### 1. Loop network 

1. loop network. This network can support long running steps to gather enough experience for agent to learn. We can also support changing differnet traffic density to evaluate the driving efficiency and safety. In this network, the curvature's effect on speed is disabled.

1.1 Normal Loop network:

![Alt text](figures/loop.gif?raw=true "Loop network Traffic scenario. Red vehicle is the AV agent")


1.2 Loop network with stop and go:

![Alt text](figures/loopstopandgo.gif?raw=true "Loop network Traffic scenario with stop and go. Red vehicle is the AV agent")


### 2. QEW network 

2. Winston Churchill eastbound on-ramp QEW road geometry: To further evaluate the effectiveness of the proposed method, we create another network based on real road geometry, i.e., Queen Elizabeth Way (QEW) Winston Churchill eastbound on-16 ramp near Toronto, Canada. This network can apply emergent brake, stay in main lane and choose to exit.

2.1 stay in main lane in qew
![Alt text](figures/stay-main-lane-qew.gif?raw=true "qew network Traffic scenario with goal as stay in main lane. Red vehicle is the AV agent")

2.2 choose to exit in qew
![Alt text](figures/exit-qew.gif?raw=true "qew network Traffic scenario with goal as choose to exit the network. Red vehicle is the AV agent")

2.3 emergent brake in qew
![Alt text](figures/emergent-brake-qew.gif?raw=true "qew network Traffic scenario with emergent brake. Red vehicle is the AV agent")