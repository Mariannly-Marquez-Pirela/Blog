---
title: Is The Universe A Quantum Computer?
published: 2026-08-14
description: "A brief History of Holographic Quantum Error Correction"
image: ""
tags: ["Quantum Computing", "Error Correction", "Holography"]
category: Physics
bibliography: QuantumErrorCorrection/References.bib
draft: false
---



author{Mariannly Marquez}
email{mariannly.marquez@yachaytech.edu.ec}
affiliation{School of Physical Sciences and Nanotechnology, Yachay Tech University, 100119-Urcuqui, Ecuador}

author{Duncan J. Mowbray}
email{dmowbray@yachaytech.edu.ec}
affiliation{School of Physical Sciences and Nanotechnology, Yachay Tech University, 100119-Urcuqui, Ecuador}




Quantum computing emerged as a revolutionary paradigm in the nineteen-eighties. In a 1985 paper, David Deutsch [@Deutsch_1985] proposed a universal computer based on quantum physics. It would have calculating powers that a classical computer, even in theory, could not simulate. In an interview [@nast_2011], Deutsch later recalled that the idea for his paper came from a conversation with the physicist Charles Bennet, of IBM, about computational complexity, i.e., the difficulty of a computational task. A comment by Bennett struck Deutsch deeply: "The fundamental computer is physics itself." If computational complexity is a statement about the physical laws, then it matters which laws we use. Classical physics, he realized, was an approximation. The true universal computer should run on the actual rules of the universe: quantum rules. 

Deutch's work was foundational for later progress in quantum computing. In 1994, Peter Shor [@Shor_1996] developed an algorithm for prime factorization, a problem that was intractable on a classical computer. This method promised exponential speedup over classical methods. He also demonstrated the algorithm's potential to break widely used cryptographic systems. However, Shor ended his paper by stating that building quantum computers faces significant challenges. This remains evident almost thirty years later, as the best implementations of his algorithm have only factored small two-digit composite numbers [@Mounica_2021, Skosana_2021, DeCusatis_2021].  

Quantum systems are fragile. They interact with their environment in unwanted ways which is often generalized as decoherence [@Nielsen_2011]. These interactions cause errors that threaten computation. The most studied errors are bit-flip and phase-flip errors but there are also depolarizing, damping, and even random errors.  Another source of errors is that quantum operations can only be implemented with limited accuracy.  These complications, among others, have significantly limited the physical realization of quantum computers. 

The following years brought some hope. Shor [@Shor_1995] himself proved quantum error correction was possible. Much like classical error correction codes protect data during transmission, quantum error correction codes (QECCs) shield quantum information. They encode logical qubits across several physical qubits. This redundancy allows errors to be detected and corrected [@Calderbank_1996]. By using ancillary qubits and measuring them, we can recover the original quantum state while preserving the important properties of superposition [@Nielsen_2011]. 

Shor's algorithm cleverly combines repetition codes to protect data from bit-flips and phase-flips errors when stored with certain limitations. It encodes a qubit in nine physical qubits, but it assumes the qubits decohere independently and it only works when one of the qubits in the tuple decoheres [@Shor_1995]. 

In a 1997 paper, Shor [@Shor_1997] proved that the protection of quantum information as it undergoes computation was also possible. He showed that fault-tolerant quantum error-correcting codes worked for error rates per operation that decrease polylogarithmically with the size of the computation. By 1996, Dorit Aharonov and Michael Ben-Or [@Aharonov_2008] had proved these codes could work when the error rate is smaller than a constant threshold. The race for more efficient codes began. New codes emerged with significant progress in code design, such as stabilizer codes [@Nielsen_2011]. These developments are crucial for bringing fault-tolerant quantum computing closer to physical realization. 

Over the past three decades, the pursuit of these codes has been ongoing. However, a surprising connection emerged from a completely different field in 2014.  Almheiri, Dong, and Harlow [@Almheiri_2015] found evidence of a deep connection between quantum error correction and the nature of spacetime itself. 

They focused on Anti-de Sitter (AdS) space, a simplified model of a universe with constant negative curvature. The remarkable property of AdS is its holographic nature. The AdS/CFT correspondence proposes that gravitational dynamics in the AdS bulk are fully encoded in a lower-dimensional conformal field theory (CFT) on the boundary [@Kibe_2021] just like in a hologram. Through this framework, they discovered that the emergence of approximate bulk locality, i.e., the idea that distant bulk operators approximately commute, can be understood as a manifestation of quantum error correction operating within the boundary theory [@Almheiri_2015].  

In particular, they [@Almheiri_2015] showed that bulk operators can be reconstructed in multiple, independent boundary regions. This suggests that the bulk is redundantly encoded, much like logical information in an error-correcting code. Operators located deeper in the bulk are better protected against erasures or errors in the boundary degrees of freedom. This reflects a natural hierarchy of protection that resembles the radial structure of AdS space. 

The HaPPY code, introduced in 2015, made holographic quantum error-correcting codes concrete. Pastawski, Yoshida, Harlow, and Preskill [@Pastawski_2015] constructed a code using three-level quantum systems or qutrits. The code is built using tensor networks, which are graphical representations that highlight how information and entanglement flow through a system [@Jahn_2022]. Their tensor network creates a mapping between bulk and boundary. It demonstrates how information in the bulk spacetime is protected from erasures of boundary regions.  

The development of holographic quantum error correction (HQEC) opened an unexpected path forward in different fields.  It offers new insights into the black hole information paradox. By modeling black hole interiors as encoded subspaces, HQEC frameworks suggest that information falling into a black hole is not destroyed but instead gets delocalized across the boundary, offering a potential route to information recovery through Hawking radiation [@Kibe_2021, Interior_2018]. 

These discoveries echo Deutsch and Bennett's early intuition: that physics itself is the ultimate computer. HQEC suggests that the fabric of reality may not just be describable by computation; it may be computation, encoded in the deepest structure of the cosmos. 

## References

<div id="refs"></div>