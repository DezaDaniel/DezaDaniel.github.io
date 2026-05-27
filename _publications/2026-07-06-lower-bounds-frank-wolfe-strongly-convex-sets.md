---
title: "Lower Bounds for Frank-Wolfe on Strongly Convex Sets"
collection: publications
category: conferences
permalink: /publication/2026-lower-bounds-frank-wolfe-strongly-convex-sets
excerpt: 'We prove a constructive \(\Omega(1/\sqrt{\varepsilon})\) lower bound for Frank-Wolfe over smooth and strongly convex objectives and constraint sets.'
date: 2026-07-06
venue: 'ICML 2026'
paperurl: 'https://arxiv.org/abs/2602.04378'
citation: 'Halbey, J., D. Deza, M. Zimmer, C. Roux, B. Stellato, and S. Pokutta (2026). <i>Lower Bounds for Frank-Wolfe on Strongly Convex Sets.</i> ICML 2026.'
---

**_Abstract:_** We present a constructive lower bound of \(\Omega(1/\sqrt{\varepsilon})\) for Frank-Wolfe (FW) when both the objective and the constraint set are smooth and strongly convex, showing that the known uniform \(\mathcal{O}(1/\sqrt{\varepsilon})\) guarantees in this regime are tight. It is known that under additional assumptions on the position of the optimizer, FW can converge linearly. However, it remained unclear whether strong convexity of the set can yield rates uniformly faster than \(\mathcal{O}(1/\sqrt{\varepsilon})\), i.e., irrespective of the position of the optimizer. To investigate this question, we focus on a simple yet representative problem class: minimizing a strongly convex quadratic over the Euclidean unit ball, with the optimizer on the boundary. We analyze the dynamics of FW for this problem in detail and develop a novel computational approach to construct worst-case FW trajectories, which is of independent interest. Guided by these constructions, we develop an analytical proof establishing the lower bound.
