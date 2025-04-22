---
layout: post
title: "A new way of using quantum memory speeds up recursive quantum algorithms"
---

Our first venture into quantum algorithms explored the possibility of reducing the circuit depth of recursive quantum algorithms at the expense of using extra quantum memory. It is now accepted for publication in PRL!

Quantum computers have the potential to outperform classical computers but not all classical programming paradigms can be easily adopted in quantum computing. A particular challenge is the use of recursions which involves remembering and reusing intermediate results. This is difficult because storing and reading quantum information is largely at odds with wanting to make use of quantum mechanical evolutions in computations. Our new approach tackles this hurdle by using quantum memories without reading the information stored; instead, we use them quantum-mechanically as instructions for the quantum computer. This allows quantum computers to perform computations of material properties or optimization using a wider array of quantum algorithms. Our approach requires preparing multiple copies of the quantum memory, which means needing larger quantum computers to achieve improved runtimes of recursions. While this presents a trade-off between computation speed and computer size, our technique constitutes a particularly appealing use case for quantum computations involving multiple smaller quantum computers distributed in a network.

https://arxiv.org/abs/2403.09187

