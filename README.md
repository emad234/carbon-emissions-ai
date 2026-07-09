# Carbon Emissions AI

Research code from my National Olympiad for Scientific Creativity '24 project: an efficient, cost-effective model to mitigate factory carbon emissions using AI.

Conducted at King Fahd University of Petroleum and Minerals (KFUPM) under Dr. Abdulrahman Al-Ofi.

## The problem

Factories choose components under competing objectives: cost, productivity, and CO2 output. Exhaustive search over 1,000-component datasets is infeasible. This project treats it as constrained optimization.

## The approach

- **Genetic algorithm (Python)**: evolves component selections against a multi-objective fitness function, converging in 10 to 20 seconds on 1,000-component datasets
- **Deep neural network (MATLAB)**: predicts emissions outcomes, reaching R = 0.97 on the test set

## Results

| Metric | Result |
| --- | --- |
| Dataset size | 1,000 components |
| Optimization time | 10 to 20 seconds |
| DNN test accuracy | R = 0.97 |
| Cost and productivity | preserved within constraints |

## Status

🚧 Migrating code and paper from the original project. Repo structure landing soon.
