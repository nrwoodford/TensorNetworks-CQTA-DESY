# tensornetworks-for-hep
Implementations of three tensor network algorithm in Julia from my time at the CQTA at DESY

Matrix Product States (MPS) provide a simple wavefunction ansatz for N sites on a line. By mapping field theories onto a 1D lattice we can use tensor network algorithms to efficiently simulate these systems and study high energy physics models.
While a summer student at the Center for Quantum Technologies and Applications at DESY in Zeuthen, I implemented the TCI, DMRG and TEBD algorithms in Julia (partially using the iTensors library https://arxiv.org/pdf/2007.14822) and used them to simulate simple spin models like the Ising and Heisenburg models, and the Schwinger model of QED with one fermion flavour.

A massive thank you to my supervisor Takis Angelides for his brilliant help across the summer and to everyone at the CQTA for their help.
