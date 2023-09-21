# SMT-Code-HW-HD
Accompanying source codes for the paper **A New Approach For Side Channel Analysis On Stream Ciphers And Related Constructions** (accepted in [IEEE-TC](https://ieeexplore.ieee.org/abstract/document/9650579))


Side channel attack of the three ciphers are considered; Lizard, Plantlet and Grain-128-AEAD. The Hamming weight leakage (from software) and the Hamming distance leakage (from hardware) are modelled through SMT. The formulated SMT instances are solved with the Z3 SMT solver. In this way, attacks during the initialisation as well as the pseudo-random generation phases are feasible.

## File Structure

### Noiseless
#### GRAIN-1228-AEAD
               Grain-128-AEAD_HD-Full_Noiseless.ipynb
               Grain-128-AEAD_HD-Reg_Noiseless.ipynb
               Grain-128-AEAD_HW-32_Noiseless.ipynb
               Grain-128-AEAD_HW-Full_Noiseless.ipynb
#### LIZARD
               Lizard_HD-Full_Noiseless.ipynb
               Lizard_HD-Reg_Noiseless.ipynb
               Lizard_HW-32_Noiseless.ipynb
               Lizard_HW-Full_Noiseless.ipynb
#### PLANTLET
               Plantlet_HD-Full_Noiseless.ipynb
               Plantlet_HD-Reg_Noiseless.ipynb
               Plantlet_HW-32_Noiseless.ipynb
               Plantlet_HW-Full_Noiseless.ipynb
### Noisy
     Grain-128-AEAD_HW-32_Noisy.ipynb
     Lizard_HW-32_Noisy.ipynb
     Plantlet_HD-Reg_Noisy.ipynb
     Plantlet_HW-32_Noisy.ipynb

## How to run

### Dependency
* Python3
* [Z3](https://github.com/Z3Prover/z3)


 
