# Physics-Based Race Car Vehicle Dynamics Modelling and Lap-Time Simulation Framework

**An ongoing engineering project focused on developing a physics-based vehicle dynamics simulation framework for race car performance analysis and lap-time calculation.**

![Project Status](https://img.shields.io/badge/Status-In%20Progress-orange)
![Language](https://img.shields.io/badge/Language-Python-blue)
![Domain](https://img.shields.io/badge/Domain-Vehicle%20Dynamics-red)

## Overview

This project focuses on developing a computational vehicle dynamics modelling and lap-time simulation framework to investigate race car behaviour under different driving and operating conditions.

The objective is to establish a physics-based mathematical representation of a racing vehicle, incorporating fundamental vehicle dynamics, tyre characteristics, aerodynamic effects and vehicle performance constraints.

The framework aims to integrate quasi-static and dynamic simulation approaches to evaluate vehicle behaviour, investigate performance limitations and estimate lap times under defined track and vehicle conditions.

The model is currently under development, with ongoing efforts to improve physical model fidelity, numerical accuracy, computational efficiency and correlation between different simulation approaches.

## Project Objectives

- Develop mathematical and physical models representing fundamental race car dynamics.
- Implement longitudinal and lateral vehicle dynamics.
- Investigate tyre force characteristics and combined braking and cornering behaviour.
- Incorporate aerodynamic drag and downforce effects.
- Develop quasi-static lap-time calculation methods using track geometry and vehicle performance constraints.
- Implement dynamic vehicle models to investigate transient vehicle responses.
- Apply numerical integration techniques for solving vehicle dynamics equations.
- Investigate numerical optimisation methods for vehicle performance and lap-time improvement.
- Evaluate model sensitivity to changes in vehicle parameters and operating conditions.
- Continuously improve model accuracy through validation and refinement.

## Technical Scope

### 1. Vehicle Dynamics Modelling

Development of mathematical representations of vehicle motion, including:

- Longitudinal vehicle dynamics.
- Lateral vehicle dynamics.
- Yaw dynamics.
- Vehicle mass and inertia properties.
- Acceleration and braking characteristics.
- Vehicle motion under combined driving conditions.

### 2. Tyre Modelling

Investigation and implementation of tyre force characteristics, including:

- Longitudinal and lateral tyre forces.
- Tyre-road friction characteristics.
- Combined-slip behaviour.
- Friction circle and friction ellipse approaches.
- Tyre force limitations and vehicle handling constraints.

### 3. Aerodynamic Modelling

Incorporation of simplified aerodynamic effects:

- Aerodynamic drag.
- Aerodynamic downforce.
- Speed-dependent aerodynamic forces.
- Influence of aerodynamic parameters on vehicle performance.

### 4. Quasi-Static Lap-Time Simulation

Development of a quasi-static lap-time calculation approach involving:

- Track geometry and curvature representation.
- Track discretisation.
- Cornering speed limitations.
- Longitudinal acceleration and braking constraints.
- Forward and backward velocity propagation.
- Lap-time estimation.

### 5. Dynamic Vehicle Simulation

Development of dynamic vehicle models to investigate transient vehicle behaviour.

The planned scope includes:

- Dynamic bicycle modelling.
- State-space representation.
- Steering input and vehicle response.
- Lateral velocity and yaw-rate analysis.
- Numerical solution of vehicle dynamics equations.
- Comparison between quasi-static and dynamic simulation results.

### 6. Numerical Methods and Optimisation

Investigation and implementation of computational methods, including:

- Numerical integration using Euler and Runge-Kutta methods.
- Numerical optimisation techniques.
- Vehicle parameter sensitivity analysis.
- Speed-profile optimisation.
- Performance comparison under different vehicle configurations.

## Technology Stack

| Technology | Application |
|---|---|
| Python | Main simulation development |
| NumPy | Numerical computation |
| SciPy | Numerical integration and optimisation |
| Matplotlib | Simulation visualisation |
| Pandas | Data processing and analysis |
| MATLAB/Simulink | Mathematical modelling and independent simulation comparison |
| Git/GitHub | Version control and development |

## Development Status

**Project status: Work in Progress**

This framework is being developed incrementally, starting with fundamental mathematical models and progressively extending towards more representative full-vehicle simulation capabilities.

Current development priorities include:

- Establishing and refining the governing equations of vehicle motion.
- Improving tyre force representation and vehicle parameterisation.
- Developing and testing numerical solution methods.
- Implementing quasi-static lap-time calculation.
- Extending the framework towards dynamic vehicle simulation.
- Evaluating numerical stability, computational accuracy and physical consistency.

The current models are preliminary engineering implementations and are not intended to represent a fully validated professional motorsport simulation environment.

Particular emphasis is placed on continuously improving model fidelity, refining assumptions, investigating numerical accuracy and validating simulation behaviour against analytical expectations and available reference data.

## Repository Structure - under development*

```text
RaceCar-Dynamics-and-Lap-Time-Simulation/
│
├── data/
│   ├── vehicle_parameters.json
│   └── track_data.csv
│
├── models/
│   ├── vehicle_model.py
│   ├── tire_model.py
│   ├── aero_model.py
│   └── bicycle_model.py
│
├── simulation/
│   ├── numerical_integrator.py
│   ├── lap_time_solver.py
│   ├── speed_profile.py
│   └── track_model.py
│
├── optimization/
│   ├── parameter_optimization.py
│   └── sensitivity_analysis.py
│
├── validation/
│   └── model_validation.py
│
├── visualization/
│   └── simulation_plots.py
│
├── tests/
│   └── test_vehicle_model.py
│
├── results/
│
├── main.py
├── requirements.txt
└── README.md
```

*The repository structure represents the intended development architecture and will evolve as individual modules are implemented.*

## Engineering Approach

The development follows an incremental model-based engineering approach:

1. Mathematical formulation of vehicle dynamics.
2. Implementation of computational models.
3. Numerical solution and simulation.
4. Analysis of vehicle response and performance.
5. Verification of mathematical and numerical behaviour.
6. Model refinement and accuracy improvement.

The objective is to establish a modular, maintainable and computationally efficient framework that can progressively accommodate higher-fidelity vehicle dynamics models.

## Future Development

- Higher-fidelity tyre modelling.
- Extended full-vehicle dynamics representation.
- Improved aerodynamic and load-transfer models.
- More advanced lap-time optimisation methods.
- Dynamic simulation and transient handling analysis.
- Model correlation and validation using reference datasets.
- Improved computational performance and software architecture.

## Disclaimer

This is an independent engineering and research project developed for educational and technical exploration of vehicle dynamics, numerical simulation and motorsport performance modelling.

It is not affiliated with, endorsed by or representative any organisation.

---

**Author:** Dinesh Kumar Rajakumaran

**Background:** M.Sc. Automotive Mechatronics and Management | B.E. Automobile Engineering

**Areas of Interest:** Vehicle Dynamics | Mathematical Modelling | Numerical Simulation | Lap-Time Calculation | Control Systems | Motorsport Engineering
