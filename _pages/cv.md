---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF version](/files/CV.pdf){: .btn .btn--primary}

Education
======
* **PhD in Computer Science**, Université Paris-Saclay, 2025–2028 (expected)
  * Thesis: *Generative AI to optimize, supervise and intelligently prepare ADAS tests with end-to-end proof of effectiveness*
  * Supervisor: Prof. Mustapha Lebbah — DAVID Laboratory (UVSQ)
  * Employer: Institut VEDECOM (CIFRE-style industrial partnership)
* **MSc in Data Science**, Institut Polytechnique de Paris, 2024–2025
* **Engineering degree**, EMINES – UM6P, Ben Guerir, Morocco, 2021–2024
  * Major: Industrial Management, Minor: Data Science

Experience
======
* **Research Intern, Institut VEDECOM** (Versailles), Apr–Sep 2025
  * Developed a VAE-based framework for representative sampling of mixed-type autonomous driving data
  * Achieved a distribution-preserving input space validated by two-sample testing (p-value ≈ 1)
* **Data Science Intern, Les Domaines Agricoles** (Casablanca), Mar–Sep 2024
  * Time series forecasting models for raspberry and blueberry cultivation planning
  * Stochastic optimization under price volatility for agricultural decisions

Skills
======
* **Programming**: Python, R, LaTeX
* **ML & AI**: PyTorch, scikit-learn
* **Data Science**: Generative models, variational inference, MCMC, optimization, statistics
* **Languages**: French (C1), English (C1), Arabic (native)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
