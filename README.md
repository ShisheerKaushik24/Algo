<!-- Badges: -->
[![License](https://img.shields.io/github/license/ShisheerKaushik24/Quantum_projects.svg?logo=CreativeCommons&style=flat-square)](https://github.com/ShisheerKaushik24/Quantum_projects/blob/master/LICENSE)
[![Contributions](https://img.shields.io/badge/contributions-welcome-orange?style=flat-square)](https://github.com/ShisheerKaushik24/Quantum_projects/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ShisheerKaushik24/Quantum_projects/graphs/commit-activity)

<!-- Logo: -->
<div align="center">
  <a href="https://github.com/ShisheerKaushik24/Quantum_projects"><img src="https://github.com/ShisheerKaushik24/Algo/blob/master/algorithm.jpg"height="300" width="550" /></a>
</div>

*<p align="center"><small>Source: InvestoPedia</small></p>*

<!-- Title: -->
<div align="center">
  <h1> <a href="https://github.com/ShisheerKaushik24/Algo"> Quantum Algorithms </a></h1>
  <h2> All my Quantum Algorithms Implementations
</div>
<br>
  
<!-- Author: -->
<div align="center">
  <b>Developer: <a target="_blank" href="https://github.com/ShisheerKaushik24">¹Shisheer S Kaushik</a></b>
<br>
</div>


## Description:
This repository contains a collection of my algorithms implemetations related to quantum computing on various SDK's.

## Packages:</br>
The repository contains the algo implmented on following SDK's:</br>

**[Qiskit](https://qiskit.org/)**: A quantum computing software development framework used to build and execute quantum circuits.</br>
**[Pennylane](http://pennylane.ai/)**: An open-source software library for quantum machine learning, quantum computing, and optimization. Used in the Quantum Machine Learning project to demonstrate a quantum support vector machine.</br>
**[Cirq](https://quantumai.google/cirq)**: An open source framework for programming quantum computers. Cirq is a Python software library for writing, manipulating, and optimizing quantum circuits.</br>

Each folder includes detailed documentation and instructions on how to run the code. The repository is constantly updated with new algos as I explore more topics in quantum computing.

## Getting Started:
To get started with these projects, simply clone or download the repository to your local machine. Each project has its own folder containing the necessary code and instructions on how to run it. Some projects may require installation of additional packages, such as Qiskit or Pennylane, which can be easily installed using pip.

**First steps to run locally**

Create a conda environment with the required dependencies:
```bash
conda env create -n quantumproj environment.yml && conda activate quantumproj
```
Install qiskit, qiskit-nature and PySCF via pip. 

Install pip first:
```bash
conda install -yc conda-forge pip==22.1.2 && python3 -m pip install -U --upgrade pip
```
Installing qiskit[all] :
```bash
python3 -m pip install -U qiskit[all]
```
Installing pennylane :
```bash
python3 -m pip install -U pennylane --upgrade
```
PennyLane comes with high performance built-in simulators, such as `default.qubit`, `default.mixed`, and `lightning.qubit`. In addition, it supports additional quantum simulators and quantum hardware via an array of plugins. Visit the [plugins](https://pennylane.ai/plugins.html) page for details. As a instance, to use 'qiskit' :
```bash
python3 -m pip install -U pennylane-qiskit
```
More details on installation are in  the [document](https://github.com/quantumlib/Cirq). 
Manually installing cirq :
```bash
python3 -m pip install -U cirq
```
Final step, installing PySCF (no support for native Windows platform, see [issue #750](https://github.com/pyscf/pyscf/issues/750)):
```bash
python3 -m pip install -U qiskit-nature[pyscf]
```
<br>
## Contributions:
Contributions to the repository are always welcome! If you have any ideas for new projects or would like to contribute to an existing one, please feel free to open a pull request.

# License

This work is licensed under a [GNU General Public License v3.0](LICENSE) license.

<hr>

Created and maintained by [@Shisheer S Kaushik][1].

[1]: https://github.com/ShisheerKauhik24
