# DDD-MDVSP-TS
 
This repository contains the code for solving the Multi-Depot Vehicle Scheduling Problem with Trip Shifting. Three algorithms are implemented: 

1. MIP: a mixed-integer programming model based on the fully time-expanded network
2. DDD: a Dynamic Discretization Discovery Algorithm that starts with a sparse network and adds time points dynamically when needed
3. BNP: a Branch-and-Price algorithm based on an extended route formulation

The code depends on CPLEX to solve all LPs and MIPs. 
