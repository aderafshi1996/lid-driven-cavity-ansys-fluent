# Lid-Driven Cavity Flow Simulation using ANSYS Fluent

## Overview

This project presents a two-dimensional computational fluid dynamics (CFD) simulation of the classical **lid-driven cavity flow** problem using **ANSYS Fluent**.

The lid-driven cavity is one of the most widely used benchmark problems in fluid mechanics and numerical simulation because of its simple geometry and well-documented reference solutions. In this study, the flow field inside a square cavity is analyzed for several Reynolds numbers and validated against the benchmark results reported by **Ghia et al. (1982)**.

The project includes:

* Geometry generation
* Structured mesh generation
* Fluent setup and boundary conditions
* Numerical solution of incompressible laminar flow
* Velocity and pressure contour visualization
* Streamline analysis
* Validation against benchmark data

---

## Problem Description

The simulation considers a square cavity filled with an incompressible Newtonian fluid.

### Boundary Conditions

* Top wall moves horizontally with constant velocity
* Remaining walls are stationary
* No-slip condition applied on all walls

The governing Reynolds number is defined as:

[
Re = \frac{V L}{\nu}
]

Where:

* (V) = lid velocity
* (L) = cavity length
* (\nu) = kinematic viscosity

---

## Software Used

* ANSYS Workbench
* ANSYS DesignModeler
* ANSYS Meshing
* ANSYS Fluent

---

## Geometry

A two-dimensional square cavity with dimensions:

[
1 \text{ m} \times 1 \text{ m}
]

was created in ANSYS DesignModeler.

### Geometry

![Geometry](images/Geometry.png)

---

## Mesh Generation

A structured quadrilateral mesh was generated to improve numerical accuracy and solution stability.

### Mesh

![Mesh](images/Mesh%201.png)
![Mesh](images/Mesh%202.png)
---

## Simulation Conditions

The simulations were performed for the following Reynolds numbers:

| Reynolds Number |
| --------------- |
| 100             |
| 400             |
| 1000            |
| 5000            |

The Reynolds number was controlled by changing the velocity of the moving lid.

---

# Results

## Reynolds Number = 100

### Pressure Contour

![Re100 Pressure](images/re100/Pressure%20Contour.png)

### Velocity Contour

![Re100 Velocity](images/re100/Velocity%20Contour.png)

### Streamlines

![Re100 Streamlines](images/re100/Velocity%20Streamline.png)

### u-Velocity Distribution

![Re100 u velocity](images/re100/U%20Velocity.png)

### v-Velocity Distribution

![Re100 v velocity](images/re100/V%20Velocity.png)

---

## Reynolds Number = 400

### Pressure Contour

![Re400 Pressure](images/re400/pressure-contour.png)

### Velocity Contour

![Re400 Velocity](images/re400/velocity-contour.png)

### Streamlines

![Re400 Streamlines](images/re400/streamlines.png)

### u-Velocity Distribution

![Re400 u velocity](images/re400/u-velocity.png)

### v-Velocity Distribution

![Re400 v velocity](images/re400/v-velocity.png)

---

## Reynolds Number = 1000

### Pressure Contour

![Re1000 Pressure](images/re1000/pressure-contour.png)

### Velocity Contour

![Re1000 Velocity](images/re1000/velocity-contour.png)

### Streamlines

![Re1000 Streamlines](images/re1000/streamlines.png)

### u-Velocity Distribution

![Re1000 u velocity](images/re1000/u-velocity.png)

### v-Velocity Distribution

![Re1000 v velocity](images/re1000/v-velocity.png)

---

## Reynolds Number = 5000

### Pressure Contour

![Re5000 Pressure](images/re5000/pressure-contour.png)

### Velocity Contour

![Re5000 Velocity](images/re5000/velocity-contour.png)

### Streamlines

![Re5000 Streamlines](images/re5000/streamlines.png)

### u-Velocity Distribution

![Re5000 u velocity](images/re5000/u-velocity.png)

### v-Velocity Distribution

![Re5000 v velocity](images/re5000/v-velocity.png)

---

## Validation

The obtained numerical results were compared with the benchmark data published by:

> Ghia, U., Ghia, K. N., & Shin, C. T. (1982).
> *High-Re solutions for incompressible flow using the Navier-Stokes equations and a multigrid method.*

The comparison showed good agreement between the simulation and reference data, confirming the validity of the numerical model.

---

## Conclusions

* The lid-driven cavity problem was successfully simulated using ANSYS Fluent.
* The numerical results captured the expected vortex structures and velocity distributions.
* Increasing Reynolds number led to stronger recirculation zones and secondary vortices near the corners.
* The simulation results showed acceptable agreement with benchmark solutions from the literature.

---

## Repository Structure

```text
lid-driven-cavity-ansys-fluent/
│
├── README.md
├── report/
├── images/
├── validation/
└── fluent-setup/
```

---

## Author

**Ali Darfashi**
Mechanical Engineering Student
CFD and Heat Transfer Enthusiast
