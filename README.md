# QGSS_24
This repository comprises of my solutions to Jupyter notebooks of Qiskit Global Summer School (QGSS) 2024. 

The QGSS was a two-week intensive summer program designed to empower the quantum researchers and developers of tomorrow with the know-how to explore the world of quantum computing, as well as refresh and sharpen the industry professional’s skills. This fifth-annual summer school prepared participants for the imminent era of quantum utility. Using hands on examples, the syllabi will guide students through areas of near-term practical importance. The school consisted of 4 labs. 

The first lab was focused on the transpilation of quantum circuits. First, we determined the properties and characteristics of quantum circuits that have an impact on the result obtained by a quantum computer. Then, we applied Qiskit’s default transpilation to a quantum circuit before developing our own transpilation process and transpilation steps. 

The second lab concentrated on the calculation of the EPLG (Error Per Layered Gate) and LF (Layer Fidelity). These metrics quantify error rates in a circuit, and are particularly useful in understanding the overhead required to run error mitigation at utility-scale workloads.

The third lab was related to the error suppression and error mitigation options available with the Estimator primitive from Qiskit Runtime. We used different combinations of error mitigation settings including:
* Dynamical decoupling
* Measurement error mitigation
* Gate twirling
* Zero noise extrapolation (ZNE)

The fourth lab simulated the dynamics of a Heisenberg spin chain with a transverse field at a utility scale. I explored the process of building the simulation workflow using the Qiskit Patterns framework and incorporate various error mitigation and optimization techniques to produce good results. The 'ibm_brisbane', a 127 qubit system was used throughout the labs. Due to time constraints, I couldn't generate data in either of the labs by using hardwares.
