# Optimal Electricity Generation Strategies – Multi-Criteria Decision Making (MCDM)

This project was developed for the course **ENG 686X – Multi-Criteria Decision Making** during Fall 2023 at UMass Amherst. It focuses on evaluating different electricity generation inputs by balancing environmental and economic objectives.

### Project Overview

The goal of this project is to identify optimal strategies for electricity generation while maintaining a fixed per capita demand of 9 kWh. Three input options were considered:

- **Imports**
- **Coal with Carbon Capture**
- **Natural Gas**

Each option was evaluated based on:
- Net cost (generation cost + CO₂ emission damages)
- Local pollution
- Uncertainty in environmental impact

### Methods Used

To evaluate and compare portfolios of electricity inputs, the following methods were used:

- **Nonlinear Optimization**: For minimizing net cost while meeting energy demand.
- **Pareto Analysis**: To explore trade-offs between objectives.
- **Weighting and Constraint Methods**: To generate non-dominated portfolios based on policy preferences.
- **Additive Value Function**: For comparing multiple portfolios with weighted objectives.
- **Stochastic Dominance Analysis**: To evaluate uncertainty and rank portfolios based on expert opinions.

### Key Findings

- Coal with carbon capture was the most cost-effective option when minimizing only net cost.
- Imports were preferred when minimizing local pollution.
- Balanced scenarios included a mix of coal and imports, with limited use of natural gas.
- Portfolio choices depend strongly on the decision-maker’s preferences and weighting of objectives.
- Stochastic dominance analysis supported excluding some dominated portfolios.

### Tools Used

- Microsoft Excel Solver (for nonlinear programming)
- Visualization techniques (Pareto charts, cumulative probability plots)

### Learning Outcomes

This project helped in understanding how different decision-making methods can be applied to real-world sustainability problems, and how trade-offs are handled in multi-criteria environments. It also demonstrated the importance of considering uncertainty and the role of expert opinions in policy planning.


