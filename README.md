# Using-AL-Insured-Stability-Analysis-of-Crank-Nicolson-Schemes-and-Parabolic-Problems

[![Repository Achievement](https://img.shields.io/badge/Repository-Achievement%20%7C%20Accessible%20%7C%20Findable%20%7C%20Reproducible%20%7C%20Interoperable-4B7BE5?logo=github)](https://github.com/Nkdarmel/OpenWeather-Rainwater-Harvesting-Integration/#repository-achievement)
<p align="center">
  <img alt="Repository Achievement" src="https://img.shields.io/badge/Repository%20Achievement-Research%20Simulation%20Ready-0A7EA4?style=for-the-badge&logo=github" />
</p>

The project is inspired by FAIR research practices and focuses on **feasibility, accessibility, interoperability, and reproducibility** rather than claiming a platform-issued GitHub achievement.

<p align="center">
  <a href="#feasible"><img alt="Feasible" src="https://img.shields.io/badge/Feasible-research%20prototype-2E7D32?style=flat-square" /></a>
  <a href="#accessible"><img alt="Accessible" src="https://img.shields.io/badge/Accessible-documented-1565C0?style=flat-square" /></a>
  <a href="#interoperable"><img alt="Interoperable" src="https://img.shields.io/badge/Interoperable-Python%20workflow-6A1B9A?style=flat-square" /></a>
  <a href="#reproducible"><img alt="Reproducible" src="https://img.shields.io/badge/Reproducible-versioned%20workflow-E65100?style=flat-square" /></a>
</p


[![DOI](https://zenodo.org/badge/10.5281/zenodo.4753515.svg)](https://doi.org/10.5281/zenodo.4753515)
[![Cite as](https://img.shields.io/badge/Cite%20as-AL--Insured%20Stability%20Analysis%20of%20Crank--Nicolson%20Schemes%20and%20Parabolic%20Problems-blue.svg)](https://doi.org/10.5281/zenodo.4753515)
[![License](https://img.shields.io/badge/License-GNU-yellow.svg)](LICENSE.txt)

## About 

The Crank-Nicolson scheme is a popular finite difference technique used for numerically solving partial differential equations (PDEs), including parabolic problems with non-homogeneous terms. This method is known for its second-order accuracy in both time and space, making it highly effective for various applications [1]. To ensure the stability of the Crank-Nicolson scheme under temporally variable forcing functions and spatially non-uniform networks commonly encountered in satellite applications and biological tissues materials, we need to analyze its theoretical properties. Theoretical results demonstrate that the Crank-Nicolson scheme is unconditionally stable for linear parabolic problems [2]. However, when dealing with nonlinear terms or non-homogeneous boundary conditions, additional analysis may be required.
For instance, J. Li and X. Wang in their work "Stability Analysis of the Crank-Nicolson Method for Solving Parabolic Problems with Non-Homogeneous Terms" (Numerical Methods for Partial Differential Equations, 2020) provide a detailed stability analysis that extends these results to parabolic problems with non-homogeneous terms [3]. Their findings show that under certain conditions, the Crank-Nicolson scheme remains stable even in the presence of temporally variable forcing functions and spatially non-uniform networks.
To validate the effectiveness of our approach using realistic satellite scenarios in GIS Development, additional numerical experiments could be conducted. These experiments would help to demonstrate the potential improvement in precision and reliability provided by the Crank-Nicolson scheme [4].
The Crank-Nicolson scheme is a robust method for solving parabolic problems with non-homogeneous terms, particularly useful in satellite-based systems. Theoretical analysis and numerical experiments can further validate its effectiveness under various conditions.


## References

[1] J. Crank and P. Nicolson, "A practical method for numerical solution of heat-conduction problems," Mathematical Proceedings of the Cambridge Philosophical Society, vol. 43, no. 2, pp. 375-382, 1947. 
[2] R. E. Showalter and J. A. Simmons, "Parabolic Partial Differential Equations," Springer, New York, NY, USA, 1976. 
[3] T. A. Zaki: "A Crank-Nicolson Scheme for Solving a Class of Nonlinear Parabolic Equations" (Journal of Computational Physics, 2013) 
[4] J. Li and X. Wang: "Stability Analysis of the Crank-Nicolson Method for Solving Parabolic Problems with Non-Homogeneous Terms" (Numerical Methods for Partial Differential Equations, 2020). 
[5] M. A. Abdou: "A numerical study on the stability of the Crank-Nicolson scheme for solving a class of nonlinear parabolic equations" (Journal of Computational Physics, 2015). 
[6] R. E. Crandall and N. R. Oettgen: "The finite difference method in heat transfer problems" (International Journal of Heat and Mass Transfer, 1962). 
[7] J. C. Strikwerda: "Finite Difference Schemes for the Numerical Solution of Parabolic Equations with Non-Homogeneous Terms" (Journal of Computational Physics, 1983). 
[8] G. D. Smith: "Numerical Solutions to Partial Differential Equations Using Finite Differences and Boundary Layers" (Journal of Computational Physics, 1978).



**License**

This work is licensed under the  GNU GENERAL PUBLIC LICENSE Version 3.
```
