
## Motor Oil Blend Optimization

This project focuses on optimizing the blend of motor oil grades produced by a petroleum company to maximize profit. The company produces three grades of motor oil—Super, Premium, and Extra—from three components. The objective is to determine the optimal mix of components for each grade of motor oil while satisfying various constraints and maximizing profit.

### Key Components:
- **Decision Variables**: The quantities of each component used in producing each grade of motor oil.
- **Constraints**: These include availability constraints for each component, grade specifications ensuring the quality of each grade, and demand constraints to meet the minimum production requirements for each grade.
- **Objective Function**: The objective is to maximize profit, which is calculated based on the selling prices of each grade of oil and the cost of components.

### Optimization Techniques:
- **Linear Programming**: The problem is formulated as a linear programming model and solved using optimization libraries such as IBM CPLEX and Google OR-Tools. This approach efficiently finds the optimal solution that maximizes profit while satisfying all constraints.
- **Monte Carlo Simulation**: Additionally, a Monte Carlo simulation is conducted to analyze the impact of varying selling prices of different oil grades on the optimal solution and maximum profits. The simulation provides insights into the robustness of the solution under different pricing scenarios.

### Results:
- The optimization model provides the optimal mix of components for each grade of motor oil and the maximum achievable profit.
- The Monte Carlo simulation offers insights into how changes in selling prices affect the optimal production mix and profits, providing valuable decision-making information for the petroleum company.
