[![DOI](https://zenodo.org/badge/1143791672.svg)](https://doi.org/10.5281/zenodo.18421615)
# UPMS Benchmark Instances
Benchmark dataset for the Unrelated Parallel Machine Scheduling (UPMS) problem with unrelated servers

## Problem

Schedule jobs on unrelated parallel machines with:
- 2 machines, 2 servers
- Machine-dependent processing times
- Machine-Server-dependent setup times

  
## Dataset Overview

**120 benchmark instances** across three size classes

### Instance Classes

| Class | Jobs (n) | Instances | Total |
|-------|----------|-----------|-------|
| Small | 10, 15, 20, 25 | 10 per size | 40 |
| Medium | 50, 60, 70, 80 | 10 per size | 40 |
| Large | 100, 150, 200, 250 | 10 per size | 40 |


### Instance Parameters

- **Machines**: 2
- **Servers**: 2
- **Processing times**: U(10, 40)
- **Setup times**: U(2, 10) — 25% of processing time (α = 0.25)

