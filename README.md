The script ‘Value_function ‘ computes the V(x) value function according to x.
It saves these values in a Matrix in a file located in a repertory that must be defined at line 8.
The level of income aimed must also be entered line 18.

The script ‘Stochastic_viability_trajectories’ builds viable trajectories based on V(x) computed by the above script.
It must get the V(x) file in the repertory above defined.

The script ‘Simple_mgmt_rule_trajectory’ builds the ‘capping’ trajectories.
It can scan a variety of SFU_max values (if ‘replicate’ >1 on line 13) or compute detailed
statistics for a specific SFU_max (if ‘replicate’ = 1). If so the value of SFU_max must be entered line 17.
