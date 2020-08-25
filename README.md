# RED-function-alchem
Pre-requests: pymbar, alchemlyb

This python script is used to calculate the free energy difference based on 
RED function.

For the first several steps used to calculate the restraint free energy, the 
probability distributions of ΔU were first fitted by RED function. Based on the 
fitted function, the a series of ΔU were generated. The newly generated ΔU values 
were then provided to BAR.

For other steps, BAR was directly used.

In the given example, the restraint was added by one-step perturbation. The 
restraint steps was specified by "-r 1" option, which means only the forward 
and backward calculation results of the first step were fitted by RED function.
