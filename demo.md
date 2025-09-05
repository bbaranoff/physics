---
output:
  pdf_document: 
    latex_engine: xelatex
  html_document: default
---

Author Bastien Baranoff

E=hv -> E=mc²

# A) Hypothèses de départ

1. **Heisenberg (espace–moment)** : $\Delta x\,\Delta p \ge \hbar/2$.
2. **Causalité (vitesse max)** : rien ne va plus vite que $c$.
3. **Quantique (Planck)** : $E=\hbar\omega=h\nu$.
4. (Fourier) **Temps–fréquence** : $\Delta t\,\Delta\omega \ge 1/2$.

---

# B) Étapes clefs (6 pas)

1. **Heisenberg** : $\Delta x\,\Delta p \ge \hbar/2$.

2. **Causalité ⇒ borne sur $\Delta p$** (paquet “au repos” $\langle p\rangle=0$)

   $$
   \Delta v \simeq \frac{\Delta p}{m} \le c \ \Rightarrow\ \boxed{\Delta p \le m\,c}.
   $$

3. **Combiner (1) et (2) ⇒ masse vs localisation**

   $$
   \Delta x \ge \frac{\hbar}{2\,\Delta p} \ge \frac{\hbar}{2\,m\,c}
   \ \Rightarrow\ 
   \boxed{\,m \ge \frac{\hbar}{2\,c\,\Delta x}\,}.
   $$

   (La meilleure localisation $\Delta x_{\min}$ **fixe** la masse.)

4. **Causalité (trajet) ⇒ borne sur $\Delta t$**

   $$
   \boxed{\,\Delta t \ge \frac{\Delta x}{c}\,}.
   $$

5. **Fourier + $E=\hbar\omega$ ⇒ énergie minimale**

   $$
   \Delta t\,\Delta\omega \ge \tfrac12
   \ \Rightarrow\ 
   \Delta\omega \ge \frac{1}{2\Delta t} \ge \frac{c}{2\Delta x}
   \ \Rightarrow\ 
   \boxed{\,E_0 \ge \hbar\,\Delta\omega \ge \frac{\hbar c}{2\,\Delta x}\,}.
   $$

6. **Éliminer $\Delta x$ (avec l’étape 3)**
   À la **saturation** $\Delta x=\hbar/(2mc)$ :

   $$
   E_0 = \frac{\hbar c}{2\Delta x} = m c^{2}
   \quad\Rightarrow\quad
   \boxed{\,E_0 = m\,c^{2}\,}.
   $$

   (On **retrouve** $E=mc^2$ sans l’avoir postulé.)

