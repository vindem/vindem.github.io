---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
permalink: /teaching/qml-uol/
---
# Quantum Machine Learning

**CO7263 | MSc elective | University of Leicester | Semester 2, 2026/27**

Quantum Machine Learning explores what happens when methods from quantum computing are applied to problems in machine learning and data analysis.

The module introduces quantum computing from first principles before examining quantum kernel methods, variational quantum circuits, quantum neural networks, learning theory, benchmarking, and hybrid quantum-classical systems. The emphasis is not simply on implementing quantum models, but on understanding what they can represent, how they should be evaluated, and what evidence would be required to establish a meaningful advantage over classical methods.

The module is worth **15 credits** and is coordinated by **Dr Vincenzo De Maio**. It combines lectures, computer laboratories, tutorials, independent study, and a practical programming project.

## Who is this module for?

The module is intended for MSc students in Computer Science, Artificial Intelligence, Data Science, and related disciplines who are interested in emerging computational technologies.

**No previous knowledge of quantum computing or quantum mechanics is assumed**. Quantum-computing concepts are introduced from first principles, and the module includes a review of the relevant mathematical foundations.

Students should nevertheless be comfortable with:

- Python programming
- Basic linear algebra
- Elementary probability
- Fundamental machine-learning concepts

Students are expected to revise mathematical material with which they are unfamiliar and to engage actively with the practical exercises and recommended readings.

## What will you learn?

By the end of the module, students should be able to:

- Explain the foundations of quantum computing relevant to machine learning.
- Implement and evaluate quantum machine-learning methods.
- Compare quantum models with appropriate classical baselines.
- Analyse QML methods using concepts from learning theory.
- Design a hybrid quantum-classical machine-learning pipeline.
- Critically assess claims of performance improvement or quantum advantage.

These objectives reflect the approved module outcomes covering quantum-computing foundations, QSVMs and QNNs, PAC-learning analysis, and hybrid quantum-classical QML pipelines.

## Indicative lecture programme

1. **Introduction to Quantum Machine Learning**: The scope, history, motivations, limitations, and current research landscape of QML.
2. **Complex Linear Algebra**: Complex vectors, inner products, unitary and Hermitian matrices, eigendecomposition, and tensor products.
3. **Fundamentals of Quantum Computing**: Qubits, gates, measurement, entanglement, and the quantum-circuit model.
4. **Fundamental Quantum Algorithms**: Quantum interference, search, amplitude amplification, the quantum Fourier transform, and their relevance to data analysis.
5. **Quantum Kernel Methods**: Classical and quantum feature maps, kernel estimation, and quantum support vector machines.
6. **Variational Quantum Circuits**: Parameterised circuits, cost functions, gradient calculation, ansatz design, and hybrid optimisation.
7. **Quantum Neural Networks**: Variational quantum classifiers, quantum layers, data re-uploading, expressivity, inductive bias, and trainability.
8. **Learning Theory Basics**: Generalisation, model capacity, sample complexity, and the PAC-learning framework.
9. **Benchmarking Quantum Machine Learning**: Classical baselines, experimental design, reproducibility, statistical uncertainty, runtime, and sampling cost.
10. **Hybrid Quantum-Classical Systems**: Quantum-cloud execution, iterative workflows, orchestration, latency, shot budgets, and resource management.
11. **Quantum Data Analysis and Applications**: Scientific applications, learning properties of quantum systems, tomography, and classical shadows.
12. **The Future of Quantum Machine Learning**: Fault-tolerant computing, scalability, data-access bottlenecks, and open research questions.

## Practical work

The practical component uses Python and PennyLane, an open-source framework for quantum programming and QML. PennyLane provides learning materials, demonstrations, and integration with classical machine-learning software and multiple quantum-device backends. Indicative laboratory activities include:

- Constructing and simulating quantum circuits
- Preparing and measuring entangled states
- Implementing elementary quantum algorithms
- Building quantum feature maps and kernel matrices
- Comparing classical SVMs with quantum-kernel models
- Training variational quantum circuits
- Developing quantum neural-network classifiers
- Investigating generalisation and model capacity
- Benchmarking QML models against classical alternatives
- Profiling hybrid quantum-classical workflows
- Selected tutorials may also introduce the Fourier interpretation of variational circuits, inductive bias, contextuality, and classical-shadow methods.

## Access to quantum computing platforms

The module is being developed with opportunities for students to experience contemporary quantum-software and hardware ecosystems.

Educational access to Quandela’s cloud platform is planned for suitable practical activities. This will allow selected experiments involving photonic quantum computing, quantum kernels, and hybrid workflows. Most development and testing will continue to use simulation, ensuring that the practical work does not depend on hardware availability.

The module also draws on PennyLane’s educational ecosystem, including its quantum machine-learning guide, demonstrations, documentation, and teaching resources. PennyLane describes QML as an evolving field spanning learning theory, practical benchmarks, quantum neural networks, and questions of quantum learning advantage.

## Assessment

The approved assessment structure is:
* Class test: 20%
* Programming project: 50%
* Online examination: 30%

The programming project requires students to implement and critically evaluate a QML application. Students are expected to compare quantum methods with credible classical alternatives and discuss limitations rather than report accuracy alone.

## Teaching philosophy

This module takes a critical and evidence-based approach to QML. Students will not be asked to assume that a quantum model is better simply because it uses a quantum computer. Instead, they will learn to ask:

- What is the appropriate classical baseline?
- What resources are required by each method?
- Is the comparison experimentally fair?
- Does the model generalise?
- Are runtime and data-loading costs included?
- Is the claimed advantage theoretical, empirical, or speculative?
- Can another researcher reproduce the result?

The objective is to prepare students to participate thoughtfully in quantum-computing research and development, while recognising both the possibilities and the present limitations of the field.

## Further information
Formal information concerning registration, timetabling, assessment deadlines, and University policies will be provided through the University of Leicester module catalogue and Blackboard. For academic enquiries about the module, please contact:
**Dr Vincenzo De Maio**
School of Computing and Mathematical Sciences
University of Leicester

