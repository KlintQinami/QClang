# QClang: High-Level Quantum Computing Language

QClang is a high-level, imperative programming language intended for the 
implementation and rapid prototyping of quantum algorithms. Its features 
include user-defined functions, unitary gates, quantum and classical data 
built-ins, and vectorized operators. The QClang compiler semantically enforces 
quantum restrictions, like the no-cloning theorem, through substructural typing.
QClang code is compiled to the Open QASM intermediate representation and thus 
can be freely executed on various simulators and physical quantum machines, 
including the IBM Quantum Experience. Its syntax closely resembles that of the 
C programming language and other modern languages. These features, coupled with 
its higher-level control flow and abstraction, allow for a large reduction in 
the number of statements required to implement sophisticated quantum computing
algorithms when compared to an equivalent implementation in Open QASM.

The regression test suite included offers examples of valid and invalid QClang
programs.
