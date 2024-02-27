# modulus-examples-with-notes
重新整理并完善的NVIDIA Modulus Examples，包含必要中文注释（zh-cn）。

## Env

* 硬件：NVIDIA GTX 4090
* 开发环境：NVIDIA Modulus 24.01 (with docker)
    * `docker pull nvcr.io/nvidia/modulus/modulus:24.01`

## TODO List

- [ ]  Modulus Core
    - [ ]  Weather and Climate
        - [ ]  AFNO
        - [ ]  DLWP
        - [ ]  GraphCast
    - [ ]  CFD
        - [ ]  AeroGraphNet for aerodynamic
        - [ ]  MeshGraphNet for transient vortex shedding
        - [ ]  FNO for Darcy Flow
        - [ ]  NFNO for Darcy Flow
        - [ ]  RNN for 2D N-S
        - [ ]  RNN for 3D Gray Scott System
    - [ ]  Healthcare
        - [ ]  MeshGraphNet
    - [ ]  Molecular Dynamics
        - [ ]  GNN
- [ ]  Modulus Sym
    - [x]  [1D Wave Equation](./01_1D_Wave/main_script.ipynb)
    - [x]  [2D Wave Equation](./02_2D_Wave/main_script.ipynb)
    - [x]  [Spring Mass ODE](./03_ODE_SpringMassSystem/main_script.ipynb)
    - [x]  [2D LDC - Laminar](./04_2D_LDC_Laminar/main_script.ipynb)
    - [x]  [Zero Equation Turbulence](./05_2D_LDC_ZeroEquationTurbulence/main_script.ipynb)
    - [x]  [Scalar Transport](./06_2D_AdvectionDiffusion/main_script.ipynb)
    - [x]  [Inverse 1D Wave Equation](./07_1D_Wave_Inverse/main_script.ipynb)
    - [x]  [1D Wave with Causal Training](./08_1D_Wave_Causal/main_script.ipynb)
    - [ ]  Linear Elasticity
    - [ ]  Inverse Problem
    - [ ]  Variational Examples
    - [ ]  Complex Geo
    - [ ]  Time Window Training
    - [ ]  2D Waveguide Cavity
    - [ ]  2D Dielectric slab waveguide
    - [ ]  3D waveguide cavity
    - [ ]  3D Dielectric slab waveguide
    - [ ]  2D N-S (Turbulent Channel)
    - [ ]  TSR (Turbulence Super Resolution)
    - [ ]  Conjugate Heat Transfer
    - [ ]  3D Fin Parameterization
    - [ ]  Heat Transfer with High Conductivity
    - [ ]  FPGA
    - [ ]  Industrial Heat Sink
