# SIAS-lab

## Project Description
This project develops a profit-maximization framework for autonomous vehicles (AVs) competing with human-driven vehicles (HVs). HV behavior is modeled using a fixed, realistic rule in which drivers naturally crowd the busiest demand areas. In contrast, the AV fleet learns an optimal policy governing both pricing and spatial fleet positioning. After incorporating traffic-flow dynamics, the model will identify how AVs should reposition themselves and adjust fares to maximize profit while competing against HVs in a mixed-autonomy ride-hailing market.

### iter 3:
- fixed constants
- #### Notes:
    decided project direction
- #### To Do:
    - HV model
    - dynamic traveller model
    - Hybrid Action space
    - Action mask
    - Traffic Flow model
    - switch Dijkstra to A*
    - add positioning to action space

### iter 2:
- fixed obs space
- added no action to action space
- fixed step logic
- #### Notes:
    constants need to be fixed before anything meaningful can come from model. Optimal strategy was not doing anything and now its max price per ride. Need to fix constants, HV model, and traveller model.
- #### To Do:
    - fix constants
    - HV model
    - dynamic traveller model
    - Hybrid Action space
    - Action mask
    - Traffic Flow model

### iter 1:
- base model

### iter 0:
- static model