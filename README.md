# TensorNetworks-CQTA-DESY
Implementations of three tensor network algorithm in Julia from my time at the CQTA at DESY.

Matrix Product States (MPS) provide a simple wavefunction ansatz for N sites on a line. By mapping field theories onto a 1D lattice we can use tensor network algorithms to efficiently simulate these systems and study high energy physics models.

While a summer student at the Center for Quantum Technologies and Applications at DESY in Zeuthen, I implemented the TCI, DMRG and TEBD algorithms in Julia (partially using the iTensors library https://arxiv.org/pdf/2007.14822) and used them to simulate spin models like the Ising and Heisenburg models, and high energy physics models like the Schwinger model of QED with one fermion flavour.

## Algorithms:
Tensor Cross Interpolation (TCI) - finds compressed MPS representations of tensors
Density Matrix Renormalisation Group (DMRG) - finds the ground state MPS and ground state energy of a Hamiltonian expressed as a Matrix Product Operator
Time Evolving Block Decimation (TEBD) - time evolves a state according to a hamiltonian by applying small tensors to an MPS

You can find a detailed overview of the algorithms in my report and also at tensornetwork.org, including the TCI page (https://tensornetwork.org/mps/algorithms/tci/) which I wrote!

A massive thank you to my supervisor Takis Angelides for his brilliant help across the summer and to everyone at the CQTA for their help.
