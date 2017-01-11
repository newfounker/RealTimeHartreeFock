# RealTimeHartreeFock

RealTimeHatreeFock computes the dynamics of a quantum system following the real-time time-dependent Hartree-Fock equations. The code relies heavily on the library PyQuante (http://pyquante.sourceforge.net). A serial and a parallel versions are available. The parallel verion uses mpi4py to accelerate the calculations of the two-electrons integrals. The dynamics is calculated following  predictor-corrector approach for stability. Several options are available to specify the basis-set and the exciting field. 


![Alt text](illust.pdf?raw=true "Dynamics of Pyrazole")
