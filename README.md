# Differential-Geometry-Calculator
This repository contains two Jupyter notebooks that use Sympy to compute fundamental forms, Christoffel symbols, curvatures, and related differential-geometric quantities for surfaces defined by parametric immersions:

1) CalculatesEverything.ipynb: Computes the first and second fundamental forms, Christoffel symbols, Gaussian curvature, and mean curvature for parametric immersions (currently illustrated by the standard parametrization of the sphere).

2) Calculate_Christoffel_symbols_and_Codazzi_Mainardi.ipynb: Provides a more general setup for computing Christoffel symbols and the Codazzi–Mainardi equations from a given metric and second fundamental form (currently illustrated by considering a general conformal parametrization if a general conformal factor $\lambda$

Note: These notebooks do not account for the specific domains of parametric surfaces. For instance, when a parameter lies strictly in a range where $\sin⁡(u)$ is always positive or negative, one can simplify expressions like $\sin⁡(u)/∣\sin⁡(u)∣$ by hand. The user should apply any domain-specific conditions as needed.
