---
title: Interactive Physics-driven 4D World Models (DeformMaster, DeformSmith)
date: 2025-09-01 00:00:00.000000000 +00:00
project_order: 1
role: Research Intern
organization: "<a href='https://www.a4x.io/'>A4x</a>, Hangzhou, China"
period: 2025.09 -- 2026.09
collection: portfolio
permalink: "/portfolio/world-model/"
---
<ul>
<li><strong>3D reconstruction and dynamics:</strong> Recover deformable objects' geometry, appearance, and motion from videos, combining differentiable rendering (Gaussian Splatting), differentiable physics (MPM, spring–mass), and neural dynamics to model deformation, physical properties, and motion.</li>
<li><strong>Interactive simulation and novel-view rendering:</strong> Simulate motion and deformation under new actions with reconstructed physics-driven 4D world models, supporting real-time online rollouts, novel-view rendering, and material parameter adjustment for deformable-object manipulation. See <a href="https://can-lee.github.io/deformmaster-web/">DeformMaster</a>.</li>
<li><strong>Physics-driven 3D asset generation:</strong> Build a Physics Harness-guided Planner–Designer–Critic agent framework to generate interactive, reusable 3D assets from text or a single image, progressively constructing and validating geometry, physical models, material behavior, and robot interactions. See <a href="https://can-lee.github.io/deformsmith-web/">DeformSmith</a>.</li>
</ul>

<div class="project-image-pair">
  <img src="{{ '/images/physics-grounded_wm_fig_1.jpg' | relative_url }}" alt="Multi-camera capture setup with deformable objects on a table" loading="lazy">
  <img src="{{ '/images/physics-grounded_wm_fig_2.jpg' | relative_url }}" alt="Robot manipulator lifting a cloth in the multi-camera setup" loading="lazy">
  <img src="{{ '/images/DeformMaster_robot_cloth_demo.gif' | relative_url }}" alt="DeformMaster robot cloth manipulation demo" width="640" height="480">
</div>

<div class="project-image-pair project-image-pair--demos">
  <video controls autoplay loop muted playsinline preload="metadata" aria-label="DeformSmith robot manipulation: full scene">
    <source src="{{ '/assets/videos/deformsmith-robot-scene.mp4' | relative_url }}" type="video/mp4">
  </video>
  <video controls autoplay loop muted playsinline preload="metadata" aria-label="DeformSmith robot manipulation: object close-up">
    <source src="{{ '/assets/videos/deformsmith-robot-closeup.mp4' | relative_url }}" type="video/mp4">
  </video>
</div>
