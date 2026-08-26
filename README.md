# Discrete-Event Simulation of Hotel Maintenance ⚙️

A discrete-event simulation project modelling and optimising the maintenance system of a hotel.

Developed using **SIMUL8** as part of my BSc Financial Mathematics degree at Cardiff University.

## What I explored

- Modelled scheduled and emergency maintenance within a shared maintenance system
- Used stochastic arrivals, service-time distributions, priority queues and resource constraints
- Modelled emergency jobs interrupting scheduled maintenance and the subsequent resumption of work
- Validated simulation outputs against independently calculated expected values
- Ran 100-trial experiments with warm-up periods and long-run result collection
- Tested alternative operating scenarios to identify potential improvements

## Key Findings

The baseline model produced technician utilisation of approximately **95.6%**, indicating a highly constrained maintenance resource.

A "What If?" experiment extending technician coverage to weekends reduced average emergency time in the system from **26.24 to 12.54 hours** and increased scheduled maintenance completion from **43.91% to 54.64%**.

Further experiments explored how changing emergency arrival frequency affected waiting times and technician utilisation.

Based on the results, I proposed changes including weekend coverage, a part-time technician and on-call support for out-of-hours emergencies.

## Project Files

📄 **[View the full report](./report.pdf)**  
🖥️ **[SIMUL8 model](./model.S8)**

The `.S8` file contains the original simulation model and requires SIMUL8 to open.

## Note

This was completed before I began using LaTeX/Overleaf for academic reports, so I have kept the report in its original submitted format rather than retrospectively reformatting it.

---

**Cardiff University | BSc Financial Mathematics**
