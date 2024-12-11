# Awesome Quantum Security

[![LinkCheck](https://github.com/QuantumVillage/awesome-quantum-security/actions/workflows/linkCheck.yml/badge.svg)](https://github.com/QuantumVillage/awesome-quantum-security/actions/workflows/linkCheck.yml) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a repository for Quantum and Security related items that go into details about the security of, as well as threats from, quantum technologies. 

**NB** we aren't [awesome post quantum](https://github.com/veorq/awesome-post-quantum/), that's over there!

## Contents

- [PQC](#pqc)
- [Threats From Quantum Technologies](#threats-from-quantum-technologies)
- [Attacks on Quantum Algorithms](#attacks-on-quantum-algorithms)
- [Defending Quantum Algorithms](#defending-quantum-algorithms)
- [Threat Modelling Quantum Technologies](#threat-modelling-quantum-technologies)
- [QKD](#qkd)
- [Quantum for Cybersecurity](#quantum-for-cybersecurity)

## PQC

There's a existing awesome list fo this! Go look over at [awesome post quantum](https://github.com/veorq/awesome-post-quantum/).

## Threats From Quantum Technologies

* [Introduction to Shor's Algorithm](https://www.udemy.com/course/introduction-to-quantum-computing-zero-to-shors-algorithm/) - An free introductory short course on Udemy.
* [Introduction to Grover's Search](https://learn.microsoft.com/en-us/azure/quantum/concepts-grovers) - A short overview article from Azure Quantum about Grover's Search algorithm, with a deep dive on the mathematics and its geometric interpretation.

## Attacks on Quantum Algorithms

- [All Your Base Are Belong To Us: Stealing VRP Secrets from Quantum Circuit Structures](http://dx.doi.org/10.1109/HOST55342.2024.10545404) - 2024-05-06 - By exploiting information leakage, say from side channels, during QAOA execution, attackers can potentially breach security and retrieve sensitive input (here for vehicle routing problems, or VRPs) details, posing profound implications for civilian and national security.
- [QDoor: Exploiting Approximate Synthesis for Backdoor Attacks in Quantum Neural Networks](https://doi.org/10.1109/QCE57702.2023.00124) - 2023-09-17 - Improving attack success rate against Quantum Machine Learning algorithms whilst evading known detection techniques.

## Defending Quantum Algorithms

- [Towards an Antivirus for Quantum Computers](http://dx.doi.org/10.1109/HOST54066.2022.9840181) - 2022-06-27 - A compile-time technique can be designed to scan quantum computer programs for malicious or suspicious code patterns before they are compiled into quantum circuits that run on a quantum computer.
- [Dynamic Pulse Switching for Protection of Quantum Computation on Untrusted Clouds](http://dx.doi.org/10.1109/HOST55342.2024.10545385) - 2024-05-22 - This work presents a basic architecture that employs pulse switching, and an extended architecture that includes use of dummy qubits for increased execution protection on quantum computers.

## Threat Modelling Quantum Technologies



## QKD

* [Hacking QKD - Vadim Makarov](https://www.youtube.com/watch?v=Phh-jO--bDU) - Quantum Village, DEF CON 33 - Talk from Prof. Makarov demonstrating a full security analysis of a QKD system, including how the vendor tried to fix it and how these patches were circumvented. Demonstrates several physics-based attacks on quantum key distribution systems.
* [Quantum Hacking](http://www.vad1.com/c/qcommce/2022/Makarov/slides/qcommce-l12-20221207.pdf) - slides from a talk given by Prof. Makarov in 2022 giving a broad overview of attacks against QKD.

## Quantum for Cybersecurity

Sometimes quantum technologies can be useful for helping solve problems in cybersecurity.

* [Cutting Medusa's Path](https://arxiv.org/abs/2211.13740) - 2022-11-24 - Paper exploring how quantum computing might help solve patch management.
