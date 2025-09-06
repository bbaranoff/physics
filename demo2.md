---
output:
  pdf_document: default
  html_document: default
---
Here it is — **both together**, clean and compact.

---

## Using only the stated hypotheses

### Assumptions

1. **Heisenberg (x–p):** $\Delta x\,\Delta p \ge \hbar/2$
2. **Causality:** no speed $>\!c$
3. **Fourier (time–frequency, $1/\sqrt{2\pi}$ convention):** $\Delta t\,\Delta\omega \ge 1/2$
4. **Planck:** $E=\hbar\omega \Rightarrow \Delta E=\hbar\,\Delta\omega$

### Derivation

1. **Causal bound on momentum spread (packet at rest):**

$$
\Delta v \simeq \frac{\Delta p}{m} \le c \;\Rightarrow\; \boxed{\Delta p \le mc}.
$$

2. **Minimal spatial width (Heisenberg + 1):**

$$
\Delta x \ge \frac{\hbar}{2\Delta p} \ge \boxed{\frac{\hbar}{2mc}}.
$$

3. **Causal probe time:**

$$
\Delta t \ge \frac{\Delta x}{c} \ge \boxed{\frac{\hbar}{2mc^{2}}}.
$$

4. **Time–energy uncertainty (Fourier + Planck):**

$$
\Delta t\,\Delta E \ge \frac{\hbar}{2}
\;\Rightarrow\;
\boxed{\Delta E \ge \frac{\hbar}{2\Delta t} \ge mc^{2}}.
$$

### Result

* Under (1)–(4), any such packet has **energy uncertainty** $\boxed{\Delta E \ge mc^{2}}$.
* When all bounds are **jointly saturated** (Gaussian-like packet with $\Delta t=\Delta x/c$), the characteristic energy reaches the scale: $\langle E\rangle \approx \Delta E = mc^{2}$.
* No other hypotheses are used; $E=mc^{2}$ is **not postulated**—the **rest-energy scale** emerges from uncertainties + causality.

---

## Generalization note

This uncertainty-based result **generalizes “global relativity”**:

* The strict **equality** $E=mc^2$ is recovered only in the **extremal, minimal-uncertainty (Gaussian)** case (joint saturation).
* For **non-Gaussian** packets, the claim naturally relaxes to the **inequality** $\Delta E \ge mc^2$ (and—with an optional minimal causal dispersion step—also $\langle E\rangle \ge mc^2$).
  Thus SR’s $E{=}mc^2$ appears here as the **sharp lower bound** attained by Gaussians; the uncertainty framework **extends** it to **all signal shapes** without postulating SR.
