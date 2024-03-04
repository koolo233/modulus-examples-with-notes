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
    - [x]  [2D LDC with Importance Sampling](./09_2D_LDC_Importance_Sampling/main_script.ipynb)
    - [x]  [2D LDC with Domain Decomposition](./10_2D_LDC_Domain_Decomposition/main_script.ipynb)
    - [x]  [2D LDC with FBPINN](./11_2D_LDC_FBPINN/main_script.ipynb)
    - [x]  [3D Taylor Green with Moving Time Window](./12_3D_TaylorGreenFlow_MovingTimeWindow/main_script.ipynb)
    - [x]  [3D Taylor Green with Causal Training](./13_3D_TaylorGreenFlow_Causal/main_script.ipynb)
    - [x]  [2D Cylinder - Laminar](./14_2D_Cylinder_NS/main_script.ipynb)
    - [x]  [2D Chip Solid-Solid Heat Transfer](./15_2D_ChipSolidSolid_HeatTransfer/main_script.ipynb)
    - [x]  [2D Chip Solid-Fluid Heat Transfer - Flow](./16_2D_ChipSolidFluid_Flow/main_script.ipynb)
    - [x]  [2D Chip Solid-Fluid Heat Transfer - Heat Transfer](./17_2D_ChipSolidFluid_HeatTransfer/main_script.ipynb)
    - [x]  [2D Waveguide Cavity](./18_2D_WaveguideCavity/main_script.ipynb)
    - [x]  [2D Dielectric Slab Waveguide](./19_2D_DielectricSlabWaveguide/main_script.ipynb)
    - [x]  [2D Helmholtz](./20_2D_Helmholtz/main_script.ipynb)
    - [x]  [2D Helmholtz with NTK](./21_2D_Helmholtz_NTK/main_script.ipynb)
    - [x]  [2D Helmholtz with HardBC](./22_2D_Helmholtz_HardBC/main_script.ipynb)
    - [x]  [2D Helmholtz with First Order](./23_2D_Helmholtz_FirstOrder/main_script.ipynb)
    - [x]  [2D Helmholtz with Adaptive Activation Functions](./24_2D_Helmholtz_AdaptiveActivationFunc/main_script.ipynb)
    - [ ]  3D Waveguide Cavity
    - [ ]  3D Dielectric Slab Waveguide
    - [ ]  Linear Elasticity
    - [ ]  Variational Examples
    - [ ]  Complex Geo
    - [ ]  2D N-S (Turbulent Channel)
    - [ ]  TSR (Turbulence Super Resolution)
    - [ ]  Conjugate Heat Transfer
    - [ ]  3D Fin Parameterization
    - [ ]  FPGA
    - [ ]  Industrial Heat Sink
