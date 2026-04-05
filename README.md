# Multilevel-Hybrid-Transport-Methods-Data
This repository contains supplemental data for the dissertation "Multilevel Hybrid Deterministic/Monte Carlo Methods for Neutral Particle Transport".
# Computational Test Descriptions 
## Test 1 
The problem domain is a $X = 1$ cm long slab with $\Sigma_t(x) = 1.0$, $\Sigma_s(x) = 0.9$, and $q(x) = 1.0$ for all $x \in [0,1]$.
## Test 2
The problem domain is a $X = 1$ cm long slab with $\Sigma_t(x) = 1.0$, $\Sigma_{s,1}(x) = 0.9$, $\Sigma_{s,2}(x) = 0.1, 0.5$, and $q(x) = 1.0$. 
Region 1 is defined as $x \in [0,0.5]$ and region 2 is $x \in [0.5,1.0]$.
## Test 3
The problem domain is a $X = 1$ cm long slab with $\Sigma_t(x) = 1.0$, $\Sigma_{s,1}(x) = 0.9$, $\Sigma_{s,2}(x) = 0.5$, $\Sigma_{s,3} = 0.1, and $q(x) = 1.0$.
Region 1 is $x \in [0,0.25]$, region 2 is $x \in [0.25,0.75]$, and region 3 is $x \in [0.75,1.0]$.
## Test 4
| Region | x [cm]     | $\Sigma_{t,i}$ | $\Sigma_{s,i}$ | $q_{i}$ |
|--------|------------|----------------|----------------|---------|
| 1      | $[0,5]$    | 1.0            | 0.8            | 1.0     |
| 2      | $[5,10]$   | 1.0            | 0.8            | 0.0     |
| 3      | $[10, 12]$ | 5.0            | 4.0            | 0.0     |
| 4      | $[12, 20]$ | 1.0            | 0.8            | 0.0     |

# MLMC Results Description
The data file contains MLMC-FE method run data showing results from 10 independent runs of the MLMC-FE-LOQD and MLMC-FE-LD-LOQD algorithms for Tests 1-3, and 1 run for Test 4.
There are also results for the time optimization algorithm presented for Tests 1 and 3, using the average runtime of the original MLMC algorithm. 
See the dissertation for more details.
