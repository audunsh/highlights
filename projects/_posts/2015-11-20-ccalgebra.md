---
layout: post
title: CCAlgebra
description: >
  Diagrammatic derivation of the Coupled-Cluster equations
image: assets/img/cc_diagrams.png
sitemap: false
---

## CCAlgebra - diagrammatic generation of Coupled-Cluster equations

The Coupled-Cluster (CC) equations at the triples level and beyond is generally cumbersome to work with due to the number of terms and complexity of the contractions. Both the book-keeping and the actual implementation of the contractions are prone to errors. 

In my master thesis, I derived and solved the CCSDT equations for the homogeneous electron gas (sometimes called the *jellium model*). For this task, I wrote a Python-module called CCAlgebra for the derivation and code-generation of CC-equations using the diagrammatic rules laid out for Feynmann-diagrams in Shavitt and Bartlett's *Many-body methods in chemistry and physics*. [1] 

I must admit I have mixed feelings for these rules, as they are very elegant and easy to work with, but at the same time I do not know how to derive the rules from "first principles", or how to generalize them much beyond the topic in question. Still, I believe they have some advantages when compared to the standard second-quantization Wick's theorem based approach, as I have found that the diagrammatic rules have lower computatonal demands in deriving the equations. (I may be mistaken, and will be happy to discuss this matter with you.)

The module is hosted <a href="https://github.com/audunsh/CCAlgebra">here on GitHub</a>, and you'll find a <a href="http://audunsh.github.io/ccalg_web.html">small tutorial here</a>. For more information and theoretical background, check out my <a href="https://www.duo.uio.no/handle/10852/49748">master thesis</a> or contact me directly.

[1] Shavitt, I., & Bartlett, R. J. (2009). Many-body methods in chemistry and physics: MBPT and coupled-cluster theory. Cambridge university press.