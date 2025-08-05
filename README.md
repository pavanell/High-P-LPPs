# Local pseudopotentials for very high pressure physics

 1) Generate new local pseudopotentials (LPPs) for OF-DFT calculations of very high pressure systems $P\sim 1$ TPa
    - `High_Pressure_PPs.ipynb`
    - OEPP pseudopotentials are used as zero-th order approximations
    - Cutoff radii are defined by the user and are a measure of how "deep" a LPP should be
 3) Use the LPPs to produce $P$ vs. $V/V_0$ plots
    - `DFTpy_get_pseudodensity_stress.ipynb`
