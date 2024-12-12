# Awesome Quantum Security

[![LinkCheck](https://github.com/QuantumVillage/awesome-quantum-security/actions/workflows/linkCheck.yml/badge.svg)](https://github.com/QuantumVillage/awesome-quantum-security/actions/workflows/linkCheck.yml) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a repository for Quantum and Security related items that go into details about the security concerns surrounding quantum technologies. 

The two main core topics for this list are:
1. Threats _from_ quantum-enabled/capable attackers.
1. Threats _to_ the various proposed quantum technologies. 

## Contents

- [Threats From Quantum Technologies](#threats-from-quantum-technologies)
  - [Quantum Cryptanalysis](#quantum-cryptanalysis)
  - [Quantum Enabled Attacks](#quantum-enabled-attacks)
  - [PQC](#pqc)
- [Threats To Quantum Technologies](#threats-to-quantum-technologies)
  - [Attacks on Quantum Algorithms](#attacks-on-quantum-algorithms)
  - [Defending Quantum Algorithms](#defending-quantum-algorithms)
  - [Threat Modelling Quantum Technologies](#threat-modelling-quantum-technologies)
  - [QKD Attacks](#qkd-attacks)
- [Quantum for Cybersecurity](#quantum-for-cybersecurity)
- [Relevant Quantum Tech Awesome Lists](#relevant-quantum-tech-awesome-lists)

## Threats From Quantum Technologies

This section covers the threats arising from scaled quantum computing, as well as the various mitigations and risk analysis that is required in light of this new paradigm and the attacks it may enable.

### Quantum Cryptanalysis

How do quantum computers 'break cryptography'? This section's resources help to understand and answer this. 

- [Introduction to Shor's Algorithm](https://www.udemy.com/course/introduction-to-quantum-computing-zero-to-shors-algorithm/) - An free introductory short course on Udemy.
- [Introduction to Grover's Search](https://learn.microsoft.com/en-us/azure/quantum/concepts-grovers) - A short overview article from Azure Quantum about Grover's Search algorithm, with a deep dive on the mathematics and its geometric interpretation.
- [Post-Quantum considerations for Operational Technology](https://www.cisa.gov/sites/default/files/2024-10/Post-Quantum%20Considerations%20for%20Operational%20Technology%20%28508%29.pdf) - 2024-10 - Analytical study from CISA (part of DHS) that enumerates threats from cryptanalytically-relevant quantum computer (CRQC)-enabled intrusions.

### Quantum-Enabled Attacks

- [What To Expect In The Emerging Age Of Quantum Computing](https://www.milbank.com/a/web/131241/What-To-Expect-In-The-Emerging-Age-Of-Quantum-Computing.pdf) - 2020-04-21 - An overview from a law perspective of the coming potential threats, as well as benefits, from quantum computing.

### PQC

Post-Quantum Cryptography is the current proposal set for 'quantum safe' cryptographic primitives and protocols. As it happens, there's a existing awesome list fo this! Go look over at [awesome post quantum](https://github.com/veorq/awesome-post-quantum/).

## Threats To Quantum Technologies

Whilst the threats from quantum technologies are growing and get the most airtime, there are many threats _to_ quantum technologies (devices, algorithms, protocols, etc.) that need to be highlighted.

### Attacks on Quantum Algorithms

- [All Your Base Are Belong To Us: Stealing VRP Secrets from Quantum Circuit Structures](http://dx.doi.org/10.1109/HOST55342.2024.10545404) - 2024-05-06 - By exploiting information leakage, say from side channels, during QAOA execution, attackers can potentially breach security and retrieve sensitive input (here for vehicle routing problems, or VRPs) details, posing profound implications for civilian and national security.
- [QDoor: Exploiting Approximate Synthesis for Backdoor Attacks in Quantum Neural Networks](https://doi.org/10.1109/QCE57702.2023.00124) - 2023-09-17 - Improving attack success rate against Quantum Machine Learning algorithms whilst evading known detection techniques.
- [Quantum Hardware Hacking](https://www.youtube.com/watch?v=Gams7BAF7l8) - Quantum Village, DEF CON 30 - An overview of various attacks and malicious quantum circuit implants that are potentially useful to attackers against quantum computer stacks.

### Defending Quantum Algorithms

- [Towards an Antivirus for Quantum Computers](http://dx.doi.org/10.1109/HOST54066.2022.9840181) - 2022-06-27 - A compile-time technique can be designed to scan quantum computer programs for malicious or suspicious code patterns before they are compiled into quantum circuits that run on a quantum computer.
- [Dynamic Pulse Switching for Protection of Quantum Computation on Untrusted Clouds](http://dx.doi.org/10.1109/HOST55342.2024.10545385) - 2024-05-22 - This work presents a basic architecture that employs pulse switching, and an extended architecture that includes use of dummy qubits for increased execution protection on quantum computers.

### Threat Modelling Quantum Technologies

- [Classical Hardware Exploits Made Quantum](https://www.youtube.com/watch?v=Da146UQ9TRE) - Quantum Village, DEF CON 31 - An overview from Dr. Jamie Friel about possible attacks to QPUs, and a lively discussion of their possible mitigations. 

### QKD Attacks

The theoretical security of Quantum Key Distribution (QKD) is always at the mercy of real-world attacks. This is our selected reading/watching and reference list: 

- [Hacking QKD - Vadim Makarov](https://www.youtube.com/watch?v=Phh-jO--bDU) - Quantum Village, DEF CON 33 - Talk from Prof. Makarov demonstrating a full security analysis of a QKD system, including how the vendor tried to fix it and how these patches were circumvented. Demonstrates several physics-based attacks on quantum key distribution systems.
- [Quantum Hacking](http://www.vad1.com/c/qcommce/2022/Makarov/slides/qcommce-l12-20221207.pdf) - slides from a talk given by Prof. Makarov in 2022 giving a broad overview of attacks against QKD.
- [Experimental vulnerability analysis of QKD based on attack ratings](https://www.nature.com/articles/s41598-021-87574-4) - 2021-05 - A thorough analysis of QKD attacks with attack ratings that may be useful for _in situ_ analysis.
- [Hacking Quantum Key Distribution via Injection Locking](http://dx.doi.org/10.1103/PhysRevApplied.13.034008) - 2020-03 - Using the properties of near-frequency photons, the attack allows the reduction in the output distribution between Alice and Bob, thereby reducing the search space for an attacker significantly.
- [An approach for security evaluation and certification of a complete quantum communication system](https://www.nature.com/articles/s41598-021-84139-3) - 2021-03-03 - This paper presents a security evaluation and improvement protocol for complete quantum communication systems.
- [Quantum key distribution with distinguishable decoy states](https://doi.org/10.1103/PhysRevA.98.012330) - 2018-07-27 - Decoy states are a technique used in QKD to try to fool would-be attackers. However, their implementation can be flawed, and such decoy states are found to be discernible to an attacker, rendering the mitigation ineffective.
- [Creation of backdoors in quantum communications via laser damage](https://doi.org/10.1103/PhysRevA.94.030302) - 2016-09-15 - Using targeted high-energy laser damage to remove attack mitigations on QKD systems.
- [Attacks exploiting deviation of mean photon number in quantum key distribution and coin-tossing](http://doi.org/10.1103/PhysRevA.91.032326) - 2014-12 - Mean Photon Number deviations causing disclosure of information to Eve in QKD systems.
- [Invisible Trojan-Horse Attacks](https://www.nature.com/articles/s41598-017-08279-1) - 2017-11-22 - This paper demonstrates the experimental feasibility of a Trojan-horse attack that remains nearly invisible to the single-photon detectors employed in practical quantum key distribution (QKD) systems, such as Clavis2 from ID Quantique.
- [Trojan-horse attacks threaten the security of practical quantum cryptography](https://doi.org/10.1088/1367-2630/16/12/123030) - 2014-12 - An overview of Trojan Horse Attacks on QKD systems.
- [Preventing calibration attacks on the local oscillator in continuous-variable quantum key distribution](https://doi.org/10.1103/PhysRevA.87.062313) - 2013-06-13 - Analysis of calibration attacks against CV-QKD systems, with suggested countermeasures.
- [Wavelength-selected photon-number-splitting attack against plug-and-play quantum key distribution systems with decoy states](https://doi.org/10.1103/PhysRevA.86.032310) - 2012-08-10 - A wavelength-selected photon-number-splitting (WSPNS) attack scheme against plug-and-play QKD systems with the decoy-state method is proposed. Theoretical analysis shows that the eavesdropper can get full information about the key generated between the legitimate parties just like the Photon Number Splitting (PNS) attack was performed in plug-and-play QKD systems without the decoy-state method.
- [Attacking a practical quantum-key-distribution system with wavelength-dependent beam-splitter and multiwavelength sources](https://doi.org/10.1103/PhysRevA.84.062308) - 2011-12-14 - Abusing a wavelength-dependent property to compromise a QKD system from this practical implementation issue.
- [Quantum Eavesdropping without Interception: An Attack Exploiting the Dead Time of Single Photon Detectors](http://dx.doi.org/10.1088/1367-2630/13/7/073024) - 2011-07 - Using dead time of a SPD to gain >98% disclosure of a key from a QKD system, without being detected.
- [Device Calibration Impacts Security of Quantum Key Distribution](https://doi.org/10.1103/PhysRevLett.107.110501) - 2011-09-09 - Analysis of potential attacks arising from bad or lapsed calibration of QKD systems.
- [Passive Faraday-mirror attack in a practical two-way quantum-key-distribution system](https://doi.org/10.1103/PhysRevA.83.062331) - 2011-06-24 - Attack on QKD by judicious (ab)use of Faraday Mirrors
- [Full-field implementation of a perfect eavesdropper on a quantum cryptography system](https://doi.org/10.1038/ncomms1348) - 2011-05-11 - Detector Control attack on QKD systems.

## Quantum for Cybersecurity

Sometimes quantum technologies can be useful for helping solve problems in cybersecurity.

- [Cutting Medusa's Path](https://arxiv.org/abs/2211.13740) - 2022-11-24 - Paper exploring how quantum computing might help solve patch management.

## Relevant Quantum Tech awesome lists

If you're here for PQC let's 302 you to [awesome post quantum](https://github.com/veorq/awesome-post-quantum/).

If you want to learn more about Quantum Computing, there's the [awesome quantum computing](https://github.com/desireevl/awesome-quantum-computing) list!

If Quantum Machine Learning is your jam, then you can find loads of information over at [awesome quantum machine learning](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning).
