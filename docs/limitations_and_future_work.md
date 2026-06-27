# Limitations and Future Work

## Limitations

### 1. Uniform pallet loading focus

The paper focuses on the uniform pallet loading problem, where boxes are identical. Mixed-size pallet loading would require additional modeling.

### 2. Summary data in repository

This repository includes summary and demonstration datasets based on reported paper values. The full operational datasets are not included.

### 3. Operational assumptions

Dynamic compression strength depends on factors such as humidity, storage time, pallet surface, orientation, and interlock stacking. Real deployment would require organization-specific validation.

### 4. Optimization software

The original mathematical model was solved using CPLEX. Organizations without access to commercial solvers may need open-source alternatives or heuristic-only implementations.

## Future work

Potential extensions include:

- Mixed pallet loading with heterogeneous box dimensions
- Integration with warehouse management systems
- Real-time humidity and storage condition monitoring
- Damage-risk prediction dashboards
- Cost-based optimization
- Robotic palletization integration
- Sustainability analysis of better cube utilization
