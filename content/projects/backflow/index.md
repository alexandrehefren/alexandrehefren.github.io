---
title: "Quantum Backflow"
description: "Interactive visualisation of quantum backflow in the jump defect — the phenomenon where positive-momentum quantum states can carry a negative probability current."
date: 2024-01-01
math: true   # the body uses $$...$$ - without this KaTeX never loads
draft: true
---

## Quantum Backflow in the Presence of Defects

Quantum backflow is a striking quantum phenomenon: a free particle with **strictly positive momentum** can nevertheless produce a **negative probability current** in some spatial region. This means the particle is, in a well-defined sense, flowing backwards — not because of any negative-momentum component, but as a purely quantum effect with no classical counterpart.

This was the subject of my doctoral thesis at the University of York: *[Quantum backflow in the presence of defects](https://etheses.whiterose.ac.uk/id/eprint/30009/)*, supervised within the context of integrable quantum field theory.

### The Jump Defect

The visualisation below shows the **backflow parameter** β_V(*f*), the most negative value the probability current expectation can take, for a particle scattering off a **jump defect** — a localised, purely transmitting phase-shifting potential with transmission coefficient:

$$T(k) = \frac{k + i\alpha}{k - i\alpha}, \qquad |T(k)| = 1$$

The defect introduces no reflection and no momentum change — only a phase. The right panel shows this phase shift φ(*k*) = 2 arctan(α/*k*) as a function of momentum *k*. The left panel shows how β_V(*f*) varies with the position *x*₀ of the spatial window *f*(*x*), for several values of the potential strength α.

Where β_V(*f*) < 0, backflow occurs.

---

<!--
  The interactive visualisation lives at _private/interactive/backflow.html
  while this page is a draft. Static files are published regardless of
  draft status, so it was moved out of static/ to keep it off the live site.

  To see it while working on this page, put it back temporarily:
      mv _private/interactive static/interactive
      hugo server -D

  When publishing this page for real, move it back permanently and delete
  the _private folder.
-->
<div style="position:relative; width:100%; padding-bottom:52%; overflow:hidden; border-radius:8px; background:#0d1117; margin: 1.5rem 0;">
  <iframe
    src="/interactive/backflow.html"
    style="position:absolute; top:0; left:0; width:100%; height:100%; border:none;"
    loading="lazy"
    title="Quantum Backflow — Jump Defect interactive visualisation"
  ></iframe>
</div>

*Hover over curves to read values. Use the legend to toggle individual α traces. The camera icon saves a high-resolution PNG.*

---

### About the Computation

The backflow parameter is the **smallest eigenvalue** of an *N* × *N* Hermitian basis matrix whose (*i*, *j*) element is:

$$M_{ij} = \frac{P_{\rm cut}}{N} \int f(x)\, j\!\left(x;\, p_i, q_j\right) dx$$

where *j*(*x*; *k*₁, *k*₂) is the Schrödinger bilinear probability current and *f*(*x*) is a Gaussian spatial window. The Fortran implementation is available at [github.com/Alexandre-Hefren/Backflow_Defects](https://github.com/Alexandre-Hefren/Backflow_Defects).

<!--
  The visualisation above is generated in Python from the Fortran output.
  That code is not published yet — if it is released, mention it here and
  add `python` back to this project's tags in content/projects/_index.md.
-->


**Reference:** Bostelmann, Cadamuro and Lechner (2017), *Quantum backflow and scattering*, Phys. Rev. A **96**, 012112.
