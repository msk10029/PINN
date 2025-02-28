# Physics-Informed Neural Networks (PINNs) for Flow Over a Backward-Facing Step

This project explores the application of **Physics-Informed Neural Networks (PINNs)** to solve fluid dynamics problems, focusing on **flow over a backward-facing step**. The study investigates the effectiveness of PINNs in capturing flow physics, particularly in scenarios involving discontinuities and complex boundary conditions.

## Project Overview
- **Problem Formulation**: The project involves solving the **Navier-Stokes equations** using PINNs, covering multiple cases such as:
  - 1D heat conduction
  - Convection-diffusion
  - Nozzle flow
  - 2D duct flow
  - Backward Facing Step
- **PINN Implementation**: The network is trained by embedding physical laws directly into the loss function, minimizing the residuals of the governing PDEs.
- 
- **Key Findings**:
  - PINNs effectively model smooth solutions but face challenges in capturing sharp gradients.
  - The network performance varies based on the choice of activation functions and loss weighting.
  - Future work includes integrating adaptive learning techniques to improve accuracy near the boundary layer.

## Conclusion
The project demonstrates the potential and limitations of PINNs for solving fluid dynamics problems. While PINNs provide a promising alternative to conventional solvers, further advancements are needed to enhance their performance for problems involving strong discontinuities, such as shocks in compressible flows.

