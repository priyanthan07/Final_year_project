# Final_year_project
COORDINATION OF PV SMART INVERTERS FOR GRID  VOLTAGE REGULATION
Due to the variable and intermittent nature of solar photovoltaic(PV), its adoption is growing, 
posing new issues for the modern power system. The grid's voltage operation restrictions may be 
exceeded by fluctuating PV generation outputs. By adjusting active and/or reactive power at the 
connection point, PV smart inverters (SIs) provide a quick way to control voltage. The current 
local autonomous control system for SIs is based solely on local data, which can result in 
suboptimal performance. This report presents a study on the coordination of photovoltaic (PV) 
smart inverters for grid voltage regulation using the Deep Reinforcement Learning (DRL) 
algorithm. The objective of this research is to develop a control strategy that enables PV inverters 
to actively participate in voltage regulation in distribution grids. A DRL-based algorithm that is 
Deep Deterministic Policy Gradient(DDPG) created and put into use. The DDPG algorithm is 
employed to train the Smart Inverters to autonomously adjust their reactive power outputs, taking 
into account grid voltage conditions and system constraints. Reward scheme of DRL is created to 
guarantee that the grid's voltage operation restrictions are satisfied while utilizing SI reactive 
power more efficiently. The suggested DRL agent for voltage control can interact with large offline 
simulations to learn its policy and can adjust to load and solar variations. The performance of the 
DRL agent is compared with the local autonomous control on the IEEE 37 node system with 
countless situations. The results demonstrate that a properly educated DRL agent is capable of 
intelligently coordinating various SIs to keep grid voltage within permissible limits, reduce PV 
production curtailment, and reduce system losses
