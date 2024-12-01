---
title: Projects
permalink: /projects/
# modified: 2024-09-23
layout: single
author_profile: true
---


## C++ Tensor Expression Templates
Under the mentorship of [Professor Nils Deppe](https://nilsdeppe.com/), I developed C++20 expression templates for evaluating vectorized tensor arithmetic in [SpECTRE](https://github.com/sxs-collaboration/spectre) to enable developers to write tensor equations in C++ with syntax that more closely resembles index notation used in general relativity. This is currently being used to implement new equations and systems in SpECTRE (e.g. [[2]](https://arxiv.org/abs/2410.22290)).

Examples:

$$\Pi_a{}^b = g^{bc}\Pi_{ac}$$
```
auto pi_up = evaluate<ti::a, ti::B>(
    g(ti::B, ti::C) * pi(ti::a, ti::c));
```

&nbsp;

$$\alpha = \sqrt{\beta^i g_{it} - g_{tt}}$$
```
auto lapse = evaluate(
    sqrt(shift(ti::I) * g(ti::i, ti::t) -  g(ti::t, ti::t)));
```

Here is a talk I gave on this project at the APS April 2024 Meeting:
<iframe width="560" height="315" src="https://www.youtube.com/embed/5AmWSoib2h8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Improvements to SpECTRE's Binary Black Hole Domain
Under the mentorship and design of [Dr. Marceline Bonilla](https://moiretomarceline.com/), I implemented [a new feature](https://spectre-code.org/classdomain_1_1CoordinateMaps_1_1Wedge.html#autotoc_md416) of the computational mesh used to simulate binary black hole mergers in [SpECTRE](https://github.com/sxs-collaboration/spectre) that made the mesh more flexible near the horizon and played a key part in getting our binary black hole simulations to robustly merge [[1]](https://arxiv.org/abs/2410.00265).

## Modeling LIGO's Astronomical Range with Sensor Data
I developed a tool for the gravitational-wave detector characterization python package [GWDetChar](https://github.com/gwdetchar/gwdetchar) that uses lasso regression to model LIGO's astronomical range with environmental sensor data to help diagnose sources of noise in the detector [[4]](https://iopscience.iop.org/article/10.1088/1361-6382/aae593). I also automated this modeling to run daily for the LIGO scientists and commissioners that maintain and improve the detector.
