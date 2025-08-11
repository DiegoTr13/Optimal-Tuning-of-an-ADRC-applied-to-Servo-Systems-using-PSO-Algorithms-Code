# Optimal-Tuning-of-an-ADRC-applied-to-Servo-Systems-using-PSO-Algorithms-Code
Here are available all the codes applied in the paper.

📁 Folder Structure

`Matlab_2023b-Code/`
This folder contains all the key MATLAB scripts required to run the PSO algorithms:

| File               | Description |
|--------------------|-------------|
| `simDyn.mlx`    | Defines the **dynamic simulation** function used as the objective for optimization. |
| `PSOND.mlx`        | Implements the **PSOT algorithm**, calling `simDyn` to evaluate each particle's fitness function. |
 `RPSOND.mlx`        | Implements the **RPSOT algorithm**, calling `simDyn` to evaluate each particle's fitness function. |
| `PSO_ADRC_Statistics.mlx` | Runs **multiple PSO simulations**, compiles **statistical results** and generates **visualizations** of both the optimization process and dynamic system behavior. |


🚀 How to Run

1. Open MATLAB.
2. Navigate to the Matlab_2023b-Code/ directory.
3. Run the main analysis script:
    
    PSO_ADRC_Statistics.mlx
    

This script will:
- Execute the selected PSO algorithm multiple times.
- Collect and display statistical results.
- Plot swarm behavior.
- Plot system dynamics.
