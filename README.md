# CR_Kforcing
periodic forcing of K in an R-M CR model across time scales

code for Figures in "Stability of consumer-resource interactions in periodic environments" (paper under revision) by Carling Bieg, Gabriel Gellner and Kevin McCann.

We use an extension of the classic Rosenzweig-MacArthur consumer-resource (C-R) model where we force resource carrying capacity (i.e., productivity), K, to mimic fluctuations in productivity associated with environmental variability.
We also use a range of growth rates to mimic varying life strategies (i.e., slow to fast pace of life) to test the generality of our results and suggest implications for future global change scenarios, as it is known that various anthropogenic stressors associated with global change (i.e., climate change, harvesting, land development, etc.) are simultaneously selecting for faster life strategies. The speed of life strategies (i.e., growth rates) also dictates the speed of underlying dynamics in C-R systems (i.e., the periodicity of limit cycles), which we will show has an interactive effect with the speed of environmental forcing.

We compare all simulation results to an unforced model (A = 0). Numerical simulations were run in Wolfram Mathematica (v 12.3.1), and numerical results (i.e., coefficient of variation (CV) in R or C densities) were taken after a sufficiently long transient period to reach an asymptotic state. As we vary the forcing speed (parameter p), the simulation length varied such that we could ensure our results captured sufficient information. For CV calculation, mean and standard deviation were calculated over either 4 full forcing periods (4/p) or 1000 time units, whichever was larger.

