---
title: 4D Gaussian Reconstruction from Monocular Dynamic Videos
date: 2025-02-01 00:00:00.000000000 +00:00
project_order: 4
role: Research Intern
organization: "<a href='https://www.a4x.io/'>A4x</a>, Hangzhou, China"
period: 2025.02 -- 2025.08
collection: portfolio
permalink: "/portfolio/4d-gaussian-reconstruction/"
redirect_from:
  - /portfolio/tactile-manipulation/
---
<ul>
<li><strong>Foundation-model priors:</strong> Use VGGT to initialize geometry and camera poses; combine SAM 2 video segmentation, CoTracker point tracking, and Depth Anything depth estimation to constrain monocular dynamic Gaussian reconstruction and recover geometry, appearance, and motion.</li>
<li><strong>Motion fields and dynamic rendering:</strong> Fit Gaussians' global SE(3) motion and local non-rigid deformation in stages using local residual motion control points. Adaptively add/prune these motion control points to refine local motion and deformation, enabling dynamic novel-view rendering and dense 3D trajectory extraction.</li>
</ul>
