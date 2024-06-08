# Measurement Protection to Prevent Cyber-Physical Attacks against Power System State Estimation

This repository consists of an example code extracted from the paper entitled "Measurement Protection to Prevent Cyber-Physical Attacks against Power System State Estimation", available on the following [link](https://www.sciencedirect.com/science/article/abs/pii/S1874548223000562).

This paper presents an attack _prevention_ technique to ensure that attack vectors cannot be constructed. This is done through the concept of protected meters. A protected meter is defined as a measurement unit equipped with additional security measures against cyber-physical attacks whose data cannot be compromised.

The algorithm is based on an Integer Linear Programming (ILP) approach. The method selects a subset of measurements to be protected so the grid would be protected in its entirety. It does not rely on power flow equations but only on the topology of the grid and the measurement relations. It can be applied to both linear and nonlinear State Estimation, accomodates different measurement types, and imposes distinct protection costs for different measurement types.

The algorithm requires basic knowledge of the General Algebraic Modeling System (GAMS). It is explained in details in [Code Breakdown and Instructions.md](https://github.com/RonaldKfouri/Measurement_Protection_Against_CyberPhysical_Attacks_on_State_Estimation/blob/0a8394965c19cbbe35282d70fbef15a111bbf39f/Code%20Breakdown%20and%20Instructions.md).

If you want to cite this work:
``` bibtex
@article{margossian2023measurement,
  title={Measurement protection to prevent cyber--physical attacks against power system State Estimation},
  author={Margossian, Harag and Kfouri, Ronald and Saliba, Rita},
  journal={International Journal of Critical Infrastructure Protection},
  volume={43},
  pages={100643},
  year={2023},
  publisher={Elsevier}
}
```
