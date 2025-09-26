# supply-chain-optimization

 Linear Programming project for supply chain optimization (multi-warehouse, multi-customer, inventory + penalty costs)
Project Overview

This project demonstrates how Linear Programming (LP) can be applied to real-world supply chain planning problems.
Inspired by feed optimization models, it extends the concept to multi-warehouse and multi-customer logistics optimization
The goal:
Minimize transportation, inventory, and unmet demand costs.
Ensure optimal allocation of resources from warehouses to customers.

 Problem Statement
A company supplies products from multiple warehouses to multiple customers.
Each warehouse has limited capacity.
Each customer has a demand requirement.
Transporting goods incurs different costs per route.
If a warehouse has leftover supply, inventory holding costs apply.
If demand is not fully met, a penalty cost is applied.


Objective:
Minimize Total Cost = Transport + Inventory + Penalty
Minimize Total Cost = Transport + Inventory + Penalty

 
 Tools & Technologies
Python
PuLP(Linear Programming solver)
pandas (data handling)
matplotlib & networkx (visualization of supply chain flows)

 Dataset (Sample)
Warehouses (3) with given supply capacity.
Customers (5) with given demand.
Transportation cost matrix (warehouse → customer).
Inventory cost per unit.
Penalty cost per unmet demand unit.


 Key Features

Formulates and solves a Linear Programming optimization model.
 Finds the optimal shipping plan from warehouses to customers.
 Calculates total minimized cost.
 Shows warehouse inventory leftover and customer shortages.
 Provides visualizations of supply chain flows.

