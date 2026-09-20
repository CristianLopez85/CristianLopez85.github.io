---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
---

My research focuses on using weak-form scientific machine learning methods for system identification and parameter estimation from noisy and limited measurements, and applying the resulting models to prediction and control.

## Prediction and Control

<div class="row">
  <div class="col-md-5">
    <img src="/assets/img/Figure1.svg" alt="Flowchart of WSINDY-MPC" class="img-fluid" />
  </div>

  <div class="col-md-7">
    <p>
      This work integrates weak-form sparse identification of nonlinear dynamics with model predictive control to identify interpretable nonlinear dynamical models from noisy measurements and use them for prediction and closed-loop control. The framework was demonstrated in applications involving plasma physics for fusion, a drone, and a chaotic system.
      <em>PRSA</em>
      [<a href="https://doi.org/10.1098/rspa.2026.0413">DOI</a>]
      [<a href="https://arxiv.org/abs/2604.23269">arXiv</a>]
      [<a href="https://github.com/MathBioCU/WSINDY-MPC">code</a>]
    </p>

  </div>
</div>

## Data-driven Discovery of Governing Equations

<div class="row">
  <div class="col-md-7">
    <img src="/assets/img/WmSINDy_EDDI.svg" alt="WmSINDy and EDDI methods for governing equation discovery" class="img-fluid" />
  </div>

  <div class="col-md-5">
    <p>
      <strong>WmSINDy.</strong> The Weak-form modified Sparse Identification of Nonlinear Dynamics method combines WSINDy and mSINDy to identify parsimonious nonlinear dynamical models from noisy measurements while simultaneously characterizing the measurement noise.
      <em>JCP.</em>
      [<a href="https://doi.org/10.1016/j.jcp.2025.114410">DOI</a>]
      [<a href="https://arxiv.org/abs/2410.17838">arXiv</a>]
      [<a href="https://github.com/CristianLopez85/WmSINDy">code</a>]
    </p>

    <p>
      <strong>EDDI.</strong> Energy-based dual-phase dynamics identification uses the mechanical energy of a system to identify nonlinear damping and stiffness, enabling discovery of governing equations directly from free-response measurements.
      <em>MSSP.</em>
      [<a href="https://doi.org/10.1016/j.ymssp.2025.112341">DOI</a>]
      [<a href="https://arxiv.org/abs/2410.17845">arXiv</a>]
      [<a href="https://github.com/KeeganJMoore/EDDI">code</a>]. EDDI was also applied to detect clearance nonlinearities [<a href="https://link.springer.com/article/10.1007/s11071-025-11098-z">DOI</a>], extended to forced systems [<a href="https://www.sciencedirect.com/science/article/pii/S0888327026005777">DOI</a>], and to two-degree-of-freedom sytems[<a href="https://arxiv.org/abs/2607.29404">arXiv</a>]. Additionally, using generative models, we developed the System identification via validation and adaptation (SIVA) technique for parametric system identification. We applied in nonlinear oscillators [<a href="https://link.springer.com/article/10.1007/s11071-025-12185-x">DOI</a>] and in a cantilever beam with nonlinear attachements [<a href="https://asmedigitalcollection.asme.org/computationalnonlinear/article/21/8/081005/1232331">DOI</a>].
    </p>

  </div>
</div>

## Hidden-State Estimation

...

## Reduced-Order Modeling

...

## Fault Diagnosis and Structural Health Monitoring

...
