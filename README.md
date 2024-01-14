# Rabi-model

This folder contains various Mathematica notebooks that I used to study the quantum Rabi model, in particular multiphoton resonances and the quantum dynamics

**(1) Diagonalizing_Rabi_model.nb**

Setting up and diagonalizing the Rabi model with a two-level atom coupeld to a single cavity photon mode

By inputting the maximum number of photons in the truncated Hilbert space, the Mathematica notebook sets up the Rabi model in the matrix form. The same program also contains the     commands to set up the corresponding Jaynes-Cummings model (i.e., dropping the counter-rotating terms in the Rabi model by the rotating-wave approximation). Depending on the need, the user can choose the number of eigenstates to be obtained. Then, both Rabi and Jaynes-Cummings Hamiltonian are diagonalized at different values of the photon frequency. The eigenvalues are displayed in the form of an energy spectrum versus the photon frequency. Note that it is straightforward to display other information and use the notebook to study other properties by slightly modifying the codes.

**(2) Diagonalizing_Three-level-two-mode-Rabi-model.nb**

Setting up and diagonalizing the Rabi model with a three-level atom coupeld to two different cavity photon modes. In the example, a Lambda-type atom is considered. It is straightforward to modify the codes to study other types of three-level atom, such as cascade-type and V-type.

**(3) Dynamics_Rabi-triangle.nb**

Setting up and diagonalizing the Rabi triangle with three cavities. Each cavity has a two-level atom coupeld to a single photon mode. The dynamics is obtained from linear superposing the eigenvectors of the Hamiltonian. The code enables a simple generalization to system with an arbitrary number of cavities.

**(4) Rabi-model_classical-drive.nb**

Setting up the Rabi model with a classical drive to the two-level atom. This notebook is a simple exercise for solving Schrodinger equation numerically in Mathematica. Since the classical drive is time-dependent, method of diagonalization is not employed here.

**Related Publications:**

(1) **K. K. W. Ma** and C. K. Law, Phys. Rev. A **92**, 023842 (2015) <br>
(2) **K. K. W. Ma**, Phys. Rev. A **102**, 053709 (2020)
