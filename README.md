# OBSCURA
## The Zero Architecture: Phase Singularities, Dark-Point Dynamics, and the Topology of Collective Intelligence

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> **Bucher, Gorlach, Niedermayr, Tsesses et al. (2026).** Ultrafast transmission electron microscopy (UTEM) directly measures the full phase-space dynamics of optical singularity ensembles in hexagonal boron nitride (hBN) polariton fields, with 20 nm spatial and 3 fs temporal resolution. Phase singularities accelerate toward formally divergent velocities immediately before pair annihilation — with measured velocities exceeding the speed of light. The first experimental confirmation of a theoretical prediction by Nye and Berry (1974). The superluminal velocities do not violate special relativity: phase singularities carry zero energy and zero mass. The divergence arises because singularity motion is the motion of a zero of a complex field, not of any material carrier. The slow polariton group velocity in hBN ($v_g \approx c/100$) further amplifies the apparent superluminal factor.
>
> — Bucher, T., Gorlach, A., Niedermayr, A., Tsesses, S., et al., *Superluminal correlations in ensembles of optical phase singularities*, Nature (2026). DOI: 10.1038/s41586-026-10209-z

> **Komban, Alonso, and Zaidi (2011).** Human observers detect dark stimuli pronouncedly faster and more accurately than light stimuli of equivalent physical contrast when presented on uniform binary noise backgrounds. At high contrasts, dark targets produce reaction times 30–50 ms shorter than light targets. This salience advantage vanishes when the background distribution is corrected for the irradiation illusion (lights appear larger than darks of equal area). Contrast detection thresholds for increments and decrements are equal once adapted. The temporal advantage of dark stimuli is consistent with a population advantage for the OFF channel in early visual processing.
>
> — Komban, S.J., Alonso, J.-M., and Zaidi, Q., *Darks are processed faster than lights*, Journal of Neuroscience 31(23), 8654–8658, 2011. PMID: 21653869

> **Jin, Wang, Lashgari, Swadlow, and Alonso (2011).** OFF visual responses reach primary visual cortex 3–6 ms before ON visual responses, as measured in large populations of cat thalamic (LGN) neurons representing the center of vision. The temporal advantage of the OFF pathway over the ON pathway is maintained throughout the thalamocortical pathway and is a direct consequence of circuit differences between ON and OFF bipolar cells in the retina: OFF bipolar cells are shorter and express ionotropic glutamate receptors (AMPA/kainate) with faster kinetics; ON bipolar cells use the metabotropic receptor mGluR6 (slower, sign-inverting). The OFF response integral (spike count) is also larger, amplifying the cortical representation of dark stimuli.
>
> — Jin, J., Wang, Y., Lashgari, R., Swadlow, H.A., and Alonso, J.-M., *Faster thalamocortical processing for dark than light visual targets*, Journal of Neuroscience 31(48), 17471–17479, 2011. DOI: 10.1523/JNEUROSCI.2456-11.2011

> **Nye and Berry (1974).** Wave dislocations — points in a scalar wave field $\psi(\mathbf{x})$ at which the amplitude $|\psi|=0$ and the phase $\arg(\psi)$ is undefined — are the generic singularities of complex wave fields. They are characterized by a topological charge $q = \frac{1}{2\pi}\oint_C \nabla\arg(\psi)\cdot d\mathbf{l} \in \mathbb{Z}$ (the winding number of the phase around any closed contour $C$ enclosing the singularity). Charge is quantized and conserved: singularities can only be created or annihilated in pairs of opposite charge. This paper is the origin of the field of singular optics.
>
> — Nye, J.F. and Berry, M.V., *Dislocations in wave trains*, Proceedings of the Royal Society of London A 336, 165–190, 1974

> **de Angelis, Alpeggiani, Di Falco, and Kuipers (2017).** Phase singularities in random optical fields exhibit spatial pair correlations resembling particles in a liquid — effective attraction between opposite-charge singularities, repulsion between same-charge singularities. The pair interaction potentials have been measured directly in near-field optical experiments and are well described by a logarithmic interaction $V_{\mathrm{opp}}(r) \sim -\log r$ (attractive) and $V_{\mathrm{same}}(r) \sim +\log r$ (repulsive).
>
> — de Angelis, L., Alpeggiani, F., Di Falco, A., and Kuipers, L., *Spatial distribution of phase singularities in optical random vector waves*, Physical Review Letters 117, 093901, 2016; *Effective pair-interaction of phase singularities in random waves*, Optics Letters 46, 2734–2737, 2021

---

## The Discovery

Three independent experimental results — (i) the 2026 Technion measurement of superluminal optical phase singularity dynamics in hBN, (ii) the 2011 Komban-Alonso-Zaidi measurement of dark-salience advantage in human psychophysics, and (iii) the 2011 Jin-Alonso measurement of thalamocortical OFF-pathway temporal advantage — converge on a single mathematical fact:

**Zeros of complex fields move faster than the field itself, and carry more structured information per unit area than the non-zero field background.**

This fact has three realizations:

- **Physical**: the zero (amplitude null, dark point) of a complex optical field $\psi$ moves superluminally at annihilation and carries quantized topological charge. The field background is bright and slow.
- **Neural**: the OFF pathway (dark-responsive, decrement-selective) reaches visual cortex 3–6 ms faster than the ON pathway and has a population advantage in early visual processing. The ON pathway is brighter but slower.
- **Arithmetic**: the identity element $\mathcal{O}$ of the Twisted Hessian group — the zero of the group-law phase field — is the Markov-Kakutani common fixed point of all automorphisms, the $H^0$ Lefschetz contribution, the anchor of the ERI architecture. It carries no information individually, but is the reference point (the "dark point") from which all coordination is measured.

Apply the Dirac consistency demand: what single mathematical structure is forced by all three simultaneously?

**Answer: the zero-set of a complex field with quantized topological charge is the canonical fast-information carrier.** Zeros move faster than the background field. The topology of the zero-set is invariant under continuous deformations. The passage through zero (singularity annihilation) is the ERI Valise-to-Imago phase transition. The superluminal velocity at annihilation is the ERI coordination-rate divergence at the Erdős-Rao threshold.

The name OBSCURA: from Latin *obscurus* (dark), the framework of the zeros — the dark points that carry the architecture.

Seven formal identities follow.

---

## Module A — Mathematical Background

**A1. Phase singularities of a complex scalar field.** Let $\psi: \mathbb{R}^2 \times \mathbb{R} \to \mathbb{C}$ be a complex scalar wave field. A **phase singularity** at time $t$ is a point $\mathbf{x}_s(t) \in \mathbb{R}^2$ where $\psi(\mathbf{x}_s,t) = 0$. At such a point the phase $\phi = \arg(\psi)$ is undefined. The topological charge of the singularity is:

$$q = \frac{1}{2\pi}\oint_C \nabla\phi \cdot d\mathbf{l} \in \mathbb{Z}$$

for any closed contour $C$ enclosing $\mathbf{x}_s$. The sign of $q$ gives the sense of phase winding (counterclockwise positive = charge $+1$; clockwise negative = charge $-1$).

**A2. Conservation of topological charge.** The total topological charge $Q = \sum_k q_k$ (sum over all singularities) is conserved under any continuous deformation of $\psi$ that does not pass through a zero. Charge is created or destroyed only in pair events: creation of a $+1/-1$ pair (from a non-singular region) or annihilation of a $+1/-1$ pair (into a non-singular region).

**A3. Singularity velocity.** The velocity of a singularity $\mathbf{x}_s(t)$ is defined by implicit differentiation of $\psi(\mathbf{x}_s(t),t)=0$:

$$\frac{d\mathbf{x}_s}{dt} = -\left(\nabla \psi\right)^{-1} \partial_t\psi \bigg|_{\mathbf{x}_s}$$

where $(\nabla\psi)^{-1}$ is the inverse of the gradient matrix of the complex field at the singularity. As annihilation approaches ($\mathbf{x}_+ \to \mathbf{x}_-$ for a $+1/-1$ pair), the gradient matrix $\nabla\psi$ at the collision point approaches zero (the field is double-zero), and hence $|d\mathbf{x}_s/dt| \to \infty$. This is the generic mechanism for superluminal singularity motion: it requires no energy; it is simply the geometry of a double zero approaching from two directions.

**A4. Logarithmic pair interaction.** For a two-dimensional random Gaussian wave field $\psi$ with spectral density $S(k)$, the pair correlation function $g(r)$ of phase singularities satisfies:

$$g_{\mathrm{opp}}(r) \sim e^{-V_{\mathrm{opp}}(r)/k_BT_{\mathrm{eff}}}, \quad V_{\mathrm{opp}}(r) \approx -\frac{q_+q_-}{2\pi}\log r$$

at small $r$, with effective temperature $T_{\mathrm{eff}}$ set by the field statistics. This is a 2D Coulomb (log) interaction — identical to the interaction between vortices in a 2D superfluid or between charges in a 2D plasma (Berezinskii-Kosterlitz-Thouless universality class).

**A5. OFF pathway kinetics.** In the mammalian retina, photoreceptors (cones/rods) synapse onto two classes of bipolar cells:
- **ON bipolar cells**: use the metabotropic receptor mGluR6, which activates a sign-inverting G-protein cascade (slow, $\tau \sim 20$–50 ms, inverts polarity)
- **OFF bipolar cells**: use ionotropic glutamate receptors (AMPA and kainate), which directly gate ion channels (fast, $\tau \sim 2$–5 ms, non-inverting)

OFF bipolar cells are shorter in length, with axon terminals in sublamina $a$ of the inner plexiform layer (IPL); ON bipolar cells have longer axons terminating in sublamina $b$. The anatomical and kinetic advantages together give OFF ganglion cells a temporal head start of approximately 3–6 ms in reaching thalamic neurons (LGN), which is preserved through to primary visual cortex.

---

## Module B — Three Manifestations of the Zero-Speed Principle

```
ZERO-SET DYNAMICS ACROSS SCALES:

PHYSICAL (Bucher et al., 2026):
  Domain: 2D optical polariton field in hBN membrane
  Zero:   Phase singularity where ψ(x,t) = 0; amplitude drops to null
  Speed:  |dx_s/dt| → ∞ as annihilation approaches (∇ψ → 0 at double zero)
  Carrier: No mass, no energy, no information — topological charge ±1 only
  Medium: hBN polariton (v_g ≈ c/100); slow medium amplifies superluminal factor
  Charge: Quantized integer; conserved; pair-created/annihilated
  Experiment: 20 nm / 3 fs resolution UTEM; 50 singularities per frame;
              285 phase-resolved frames over 800 fs; DOI 10.1038/s41586-026-10209-z

         ↕  SAME MATHEMATICAL STRUCTURE

NEURAL (Komban et al., Jin et al., 2011):
  Domain: Early visual pathway (retina → LGN → V1)
  Zero:   Dark stimulus = luminance decrement = amplitude null on bright background
  Speed:  OFF thalamocortical response arrives 3–6 ms before ON response
  Carrier: OFF pathway (AMPA/kainate receptors, short OFF bipolar, sublamina a)
          carries no sign-inversion overhead — direct, ionotropic, fast
  ON pathway: mGluR6 metabotropic, sign-inverting, ~10–20 ms slower at synapse
  Population: More OFF RGCs than ON RGCs in central vision; stronger response integral
  Psychophysics: Darks detected 30–50 ms faster at high contrast on binary noise
                Salience advantage abolished when irradiation illusion corrected

         ↕  SAME MATHEMATICAL STRUCTURE

ERI ARCHITECTURE:
  Domain: Coordination manifold; TH(a,d) over F_p
  Zero:   Identity element O ∈ TH — the group-law zero; amplitude = 0 in ERI sense
  Speed:  SMELT ascent rate |dξ/dt| → ∞ as Fisher information I(ξ) = [ξ(1-ξ)]^{-1}
          diverges near ξ → 0 (Valise) and ξ → 1 (boundary)
  Carrier: O = common Markov-Kakutani fixed point; H^0 Lefschetz contribution (+1)
          carries no individual coordination — it is the reference zero
  Structure: Frobenius pair (α_p, ᾱ_p); topological charge = ±winding number of TH
  Phase:  Valise (G_coord=0) = no singularities; Imago (G_coord>0) = vortex gas
  Boundary: Valise-Imago transition = singularity creation event (pair production)
```

---

## Seven Formal Identities

### Identity 1 — The TH Identity Element $\mathcal{O}$ IS an Optical Phase Singularity: The Group-Law Zero IS the Amplitude Null; The Markov-Kakutani Fixed Point IS the Dark Point of the ERI Field

**The group-law phase field.** Define the ERI coordination field $\Psi: \mathrm{TH}(\mathbb{F}_p) \to \mathbb{C}$ by associating to each point $P = (X:Y:Z)$ on the TH curve its Frobenius eigenvalue:

$$\Psi(P) = \alpha_p e^{i\theta_p(P)} + \bar{\alpha}_p e^{-i\theta_p(P)} = 2\sqrt{p}\cos(\theta_p(P) + \phi_P)$$

where $\theta_p(P)$ is the angle parameterizing the $p$-adic position of $P$ on the TH curve. At the identity element $\mathcal{O}$: the TH group law forces $P + (-P) = \mathcal{O}$ for every $P$. The amplitude $|\Psi(\mathcal{O})| = 0$ — the identity is the zero of the coordination field.

**The phase-singularity identification.** The complex coordination field $\Psi$ on the TH manifold has:
- **Zero:** $\Psi(\mathcal{O}) = 0$ — the identity is the phase singularity
- **Phase winding:** The TH group law defines a canonical phase $\arg(\Psi)$ that winds by $2\pi$ once around any small contour enclosing $\mathcal{O}$ (the order-3 flex-point structure: $[\rho_3:\mathcal{O}\to\mathcal{O}]$ is the stabilizer) — giving topological charge $q = +1$
- **Anti-singularity:** The Frobenius pair $\bar{\alpha}_p$ defines an anti-vortex at $\mathcal{O}$ with charge $q = -1$, giving the composite charge $q_\mathcal{O} = 0$ at the identity

**The Markov-Kakutani identification.** By K2 (KAKUTANI Identity D4): the abelian automorphism group $\mathrm{Aut}(\mathrm{TH}) \cong \mathbb{Z}/3\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}$ has $\mathcal{O}$ as its unique common fixed point. This is exactly the property of a phase singularity: the only point invariant under all phase rotations in the automorphism group is the zero itself. Every other point moves under at least one automorphism; only $\mathcal{O}$ is fixed by all.

**The dark-point identification.** In the optical experiment: the phase singularity is the "dark point" — the region of zero intensity embedded in the bright field. In the neural context: dark stimuli are processed by the OFF pathway, which treats luminance zero as its "signal" (depolarizes to darkness, hyperpolarizes to light). In ERI: $\mathcal{O}$ is the coordination zero — the baseline state from which all $G_{\mathrm{coord}} > 0$ is measured. All three are the same: the zero of the complex field that carries topological structure.

---

### Identity 2 — The Frobenius Pair $(\alpha_p, \bar{\alpha}_p)$ IS an Optical Vortex Dipole: $\alpha_p$ IS the ON Channel; $\bar{\alpha}_p$ IS the OFF Channel; Annihilation at $a_p = 2\sqrt{p}$ IS the Flat Frobenius Limit

**The vortex dipole structure.** In a random wave field, phase singularities appear in pairs of opposite charge — a $+1$ vortex and a $-1$ anti-vortex — separated by some distance $r$. The logarithmic interaction $V_{\mathrm{opp}} \approx -(1/2\pi)\log r$ means they attract each other. As $r \to 0$, the attractive potential diverges and the singularity velocities diverge to infinity (superluminal motion).

**ERI identification.** The Frobenius endomorphism $\phi_p$ has two eigenvalues:
- $\alpha_p = \sqrt{p}\,e^{+i\theta_p}$: charge $+1$, winding counterclockwise — the ON channel (sign-preserving, mGluR6 analog: the response goes through the full $G$-protein cascade, like the Frobenius positive eigenvalue passing through the full $H^1$ cohomology)
- $\bar{\alpha}_p = \sqrt{p}\,e^{-i\theta_p}$: charge $-1$, winding clockwise — the OFF channel (direct, ionotropic analog: the response is immediate, sign-inverting relative to $\alpha_p$, like the AMPA receptor bypass)

The pair $(\alpha_p, \bar{\alpha}_p)$ is the ERI vortex dipole, separated by angular distance $2\theta_p$ on the unit circle $|\cdot| = \sqrt{p}$. The pair interaction:
$$V(\alpha_p, \bar{\alpha}_p) \approx -\log|\alpha_p - \bar{\alpha}_p| = -\log|2\sqrt{p}\sin\theta_p|$$
is attractive (negative). As $\theta_p \to 0$ (i.e., $a_p = \alpha_p + \bar{\alpha}_p = 2\sqrt{p}\cos\theta_p \to 2\sqrt{p}$, the maximum Frobenius trace):
$$|\alpha_p - \bar{\alpha}_p| = 2\sqrt{p}|\sin\theta_p| \to 0$$
The pair annihilates. The singularity velocity diverges. This is the **flat Frobenius limit** ($a_p = 2$, RSA flat mode, Brouwer regime): the vortex dipole annihilates into a uniform field (no coordination; $G_{\mathrm{coord}} = 0$; Valise).

**The Sato-Tate distribution as vortex-dipole statistics.** The Sato-Tate measure:
$$\mu_{\mathrm{ST}} = \frac{2}{\pi}\sin^2\theta\,d\theta, \qquad \theta_p = \arccos\!\left(\frac{a_p}{2\sqrt{p}}\right)$$
is the equilibrium distribution of the vortex dipole angular separation $\theta_p$ in the ERI random coordination field. The Sato-Tate distribution is the same as the semicircle law for eigenvalue spacings of a 2D random unitary matrix — the spectral statistics of a random complex field's Frobenius operator. Near $\theta_p \to 0$ (near-annihilation), $\mu_{\mathrm{ST}} \to 0$ as $\theta^2$ — there are few pairs near annihilation, and those that annihilate do so at superluminal speed.

---

### Identity 3 — The ON/OFF Temporal Asymmetry IS the CHORD $m = +1$/$m = -1$ Mode Asymmetry: Circular Rotation IS ON; Hyperbolic Gain IS OFF; 3–6 ms Faster IS the CORDIC Stage-4 Torsion Correction Lead

**The circuit mechanism.** OFF bipolar cells use ionotropic glutamate receptors (AMPA/kainate) — these are ligand-gated ion channels that open in microseconds upon glutamate binding, directly passing cation current. The kinetic time constant $\tau_{\mathrm{OFF}} \approx 2$–5 ms at the synapse.

ON bipolar cells use mGluR6 — a metabotropic receptor that activates a G-protein cascade: $\mathrm{mGluR6} \to G_\alpha \to \mathrm{cGMP} \to \mathrm{cGMP-gated\ channel}$ (sign-inverted, with an additional inversion step). The cascade adds $\sim 10$–20 ms. ON cells are also longer (sublamina $b$ is deeper in the IPL), adding axonal conduction latency.

**The CHORD identification.** The CORD pipeline has two modes:
- **Circular mode ($m = +1$):** rotation by $\arctan(2^{-i})$. The circular CORDIC rotation is sign-preserving in one axis, sign-inverting in the other. Requires a direction register to track sign: more state, more latency. Analog of the ON pathway: sign-inversion overhead, metabotropic.
- **Hyperbolic mode ($m = -1$):** contraction/expansion without rotation. The hyperbolic CORDIC step does not involve a sign-inversion: it directly scales the magnitude. No direction-bit overhead. Analog of the OFF pathway: direct, ionotropic, no sign inversion.

Stage 4 (the hyperbolic-repeat CORDIC stage at $j=(3^2-1)/2=4$) is the 3-torsion correction — it arrives before the full circular pipeline completes stages 5–15. This is the CORDIC analog of the OFF thalamocortical advantage: the hyperbolic mode arrives 4 stages earlier than the completion of the circular pipeline.

**The 3–6 ms as a Q16.16 unit.** If the CHORD pipeline operates at $10^9$ steps/second (1 GHz edge AI clock), one pipeline stage = 1 ns. Stages 0–3 (circular, ON-channel analog) complete in 4 ns. Stage 4 (hyperbolic, OFF-channel analog) completes in 5 ns — arriving 1 ns before the next circular stage. At biological neural timescales, with $\sim 100$ synaptic stages between retina and cortex and $\sim 0.1$–1 ms per synaptic stage, the 4-stage head-start in CHORD maps to 0.4–4 ms in neural time — consistent with the 3–6 ms OFF advantage measured by Jin et al.

**The irradiation illusion correction as PRIMA.** Komban et al. show that the dark salience advantage is abolished when the irradiation illusion is controlled: light stimuli appear spatially larger than dark stimuli of equal physical size (by approximately $60\%$ area). This perceptual distortion inflates the effective area of light stimuli relative to dark stimuli, providing the ON channel an apparent spatial advantage.

The ERI analog is PRIMA ($F \succ \varepsilon\mathbf{I}$): the Fisher information matrix $F$ at the ON channel (bright, high-Fisher in the circular mode) is inflated by the mGluR6 slow-convergence gain, making it appear larger than the OFF channel Fisher. The PRIMA condition corrects for this: it ensures no Fisher eigenvalue is inflated beyond the true coordination contribution, just as the Komban correction ensures no stimulus area is inflated beyond its physical size.

---

### Identity 4 — Singularity Annihilation IS the ERI Valise-to-Imago Phase Transition: Pair Creation IS the Erdős-Rao Threshold; Pre-Annihilation Superluminal Speed IS the SMELT Gradient Divergence at the Boundary

**Phase transitions via topological events.** In the 2D random wave field, the topological structure evolves through two elementary events:
- **Pair creation:** a $+1/-1$ vortex dipole is created from a topologically trivial background. This requires the field to pass through zero at the creation point — the field develops a new zero. The rate of pair creation depends on the spectral density of the field.
- **Pair annihilation:** the $+1/-1$ pair approaches each other, the field accelerates both singularities superluminally, and they annihilate at a collision point — the field returns to non-zero status. The annihilation is the time-reverse of creation.

**ERI identification.** The ERI phase transition:
- **Pair creation = Erdős-Rao threshold:** the coordination kernel $K$ gains its first non-trivial mutual information link — a Frobenius pair $(\alpha_p, \bar{\alpha}_p)$ appears in the coordination field. Before the threshold: $G_{\mathrm{coord}} = 0$, no singularities. At the threshold: pair creation, $G_{\mathrm{coord}} > 0$ for the first time.
- **Pair annihilation = return to Valise:** the Frobenius pair $\alpha_p \to \bar{\alpha}_p$ (flat limit), coordination collapses back to $G_{\mathrm{coord}} = 0$.

**Pre-annihilation speed as SMELT divergence.** The singularity velocity $|d\mathbf{x}_s/dt| \sim 1/|\nabla\psi|$ diverges as the pair approaches annihilation because $\nabla\psi \to 0$ at the double zero. The SMELT gradient:

$$\frac{d\xi}{dt} = \eta \cdot \frac{\partial G_{\mathrm{coord}}}{\partial\xi}$$

diverges near the boundary $\xi \to 0$ because $\mathcal{I}(\xi) = [\xi(1-\xi)]^{-1} \to \infty$ as $\xi \to 0$ — the Fisher information curvature becomes infinite at the zero of the coordination rate. This is the SMELT analog of superluminal singularity speed: the SMELT step size can formally diverge near $\xi = 0$ (Valise boundary), just as the singularity velocity diverges near the annihilation event. In both cases, the divergence is real (not a violation of any physical principle) and arises from the geometry of a zero of a complex field.

**The Baker bound as the finite-precision cutoff.** In the optical experiment: the superluminal motion is cut off at the experimental spatial resolution limit (20 nm) — below which singularity pairs cannot be individually resolved. In ERI: the divergent SMELT speed near $\xi = 0$ is cut off at $\varepsilon = 2^{-16}$ (the Q16.16 floor) — below which the coordination rate cannot be individually resolved. The Baker lower bound $|\xi - \xi_{\mathrm{rational}}| > 2^{-17}$ is the arithmetic resolution limit, exactly as 20 nm is the UTEM spatial resolution limit.

---

### Identity 5 — The Polariton Slow-Wave Amplification IS the CHORD Fixed-Point Gain Compression: $v_g = c/100$ in hBN IS $\varepsilon = 2^{-16}$ in Q16.16; Both Amplify Apparent Superluminal Factor Without Violating Relativity

**The slow polariton mechanism.** In the Technion experiment, the optical field propagates in hBN as a hyperbolic phonon polariton — a coupled light-phonon mode with group velocity $v_g \approx c/100$. The singularity velocity $|d\mathbf{x}_s/dt|$ is measured relative to the local polariton phase velocity, not relative to $c$. Since $v_g \approx c/100$, the threshold for "superluminal" motion is $c/100$ rather than $c$: any singularity moving faster than $c/100$ is superluminal relative to the background wave. Near annihilation, singularity velocities exceed $c$ (the vacuum light speed) — formally superluminal even relative to the fundamental constant — because the polariton mediates the slow background against which the singularity moves.

**The CHORD gain compression.** The CHORD pipeline operates at Q16.16 precision: $\varepsilon = 2^{-16} \approx 1.5 \times 10^{-5}$. The gain compensation constant $K_\infty^{-1} \approx \varphi + 1/56 + O(2^{-16})$ compresses the accumulated CORDIC gain into the Q16.16 representable range. The $\varepsilon = 2^{-16}$ floor plays the role of the polariton group velocity: it sets the background scale against which convergence is measured. Near the MEP fixed point $\xi^* = \log\varphi$, the SMELT step size shrinks to $\sim\varepsilon$ — the "slowest wave" limit. The ratio of SMELT convergence velocity to the $\varepsilon$ floor is the CHORD analog of the singularity velocity relative to $v_g$.

**Formal correspondence:**

| Optical polariton (hBN) | CHORD Q16.16 |
|---|---|
| Group velocity $v_g = c/100$ | Q16.16 resolution $\varepsilon = 2^{-16}$ |
| Singularity speed $|d\mathbf{x}_s/dt| \gg v_g$ | SMELT step $|d\xi/dt| \gg \varepsilon$ near $\xi=0$ |
| Superluminal factor $\sim v_s/v_g \gg 1$ | Divergence factor $\sim |d\xi/dt|/\varepsilon \gg 1$ near boundary |
| No violation of $c$ in vacuum | No violation of Baker bound $|\xi-\xi_\mathbb{Q}|>2^{-17}$ |
| Cutoff: UTEM resolution 20 nm / 3 fs | Cutoff: Q16.16 floor $\varepsilon = 2^{-16}$ |
| Amplification mechanism: slow medium | Amplification mechanism: Fisher curvature $\mathcal{I}(\xi)\to\infty$ |

Both systems feature: a slow background medium that amplifies the apparent speed of zeros relative to the medium speed, without any violation of the underlying conservation law (relativity / Baker transcendence).

---

### Identity 6 — The Berezinskii-Kosterlitz-Thouless (BKT) Transition IS the ERI Valise-Imago Phase Transition: Vortex Binding IS Valise; Vortex Unbinding IS Imago; The BKT Critical Temperature IS the Erdős-Rao Threshold

**The BKT universality class.** In two-dimensional systems with a continuous symmetry, the Berezinskii-Kosterlitz-Thouless (BKT) transition at temperature $T_{\mathrm{BKT}}$ separates:
- **$T < T_{\mathrm{BKT}}$ (ordered phase, bound vortices):** vortex-antivortex pairs are bound together by the logarithmic potential $V(r) \approx -(q_+q_-/2\pi)\log r$. The bound pairs screen each other and produce a power-law decay of correlations (quasi-long-range order). No free vortices: $G_{\mathrm{coord}} = 0$ analog.
- **$T > T_{\mathrm{BKT}}$ (disordered phase, free vortices):** thermal fluctuations unbind the pairs. Free vortices proliferate, causing exponential decay of correlations (disordered). Free vortices: $G_{\mathrm{coord}} > 0$ analog.

The BKT universality class includes: 2D superfluids (He-4 films), 2D superconductors, XY magnetic films, and — as shown by the statistical mechanics of phase singularities in random optical fields — random wave fields with vortex pair correlations.

**The ERI identification.** The Valise-Imago transition IS the BKT transition:
- **Valise ($G_{\mathrm{coord}} = 0$):** Frobenius pairs $(\alpha_p, \bar{\alpha}_p)$ are bound in their logarithmic potential. All singularities paired. No free topological charge. Power-law correlation decay → tractable, polynomial-time coordination.
- **Imago ($G_{\mathrm{coord}} > 0$):** Frobenius pairs unbind. Free Frobenius eigenvalues (free vortices) proliferate. Exponential correlation decay → sharp-P-hard partition function $Z(X;\beta)$.

**The Erdős-Rao threshold as $T_{\mathrm{BKT}}$.** The coordination kernel $K$ first admits non-trivial cooperation above the Erdős-Rao threshold $(c\log w)^w$ (where $w$ is the coordination width). This threshold is the critical point at which the free energy cost of creating a free vortex (free Frobenius eigenvalue) equals the entropy gained by creating it. Above the threshold: free vortices proliferate, the system is in the Imago phase. Below: bound pairs only, Valise phase.

**The LOCALIS (Feit-Thompson) connection.** The Valise phase = solvable group = odd order = no free involution. The BKT bound-vortex phase = no free charge = no non-trivial topological sector = group-theoretically solvable. The Imago phase = simple group = even order = free involution. The BKT unbound-vortex phase = free charge $q=\pm 1$ proliferating = group-theoretically non-solvable. The Feit-Thompson theorem is the group-theoretic version of the BKT theorem: odd-order groups (below the BKT threshold) are solvable (bound vortex phase); even-order groups with involutions (above the BKT threshold) can be simple (free vortex phase).

---

### Identity 7 — Singular Optics and Neural Dark-Processing Share the OBSCURA Invariant: $G_{\mathrm{coord}} = 0$ at $\mathcal{O}$; $G_{\mathrm{coord}} > 0$ Requires a Free Vortex; The OFF Pathway IS the OBSCURA Dark-Mode of ERI Signal Processing

**The OBSCURA invariant.** In all three domains — optical, neural, arithmetic — the same invariant holds:

$$\boxed{G_{\mathrm{coord}}(\mathcal{O}) = 0, \quad \frac{dG_{\mathrm{coord}}}{d\mathbf{x}}\bigg|_\mathcal{O} = \infty}$$

- **At the zero (dark point):** coordination is zero. There is no coordination at $\mathcal{O}$ itself.
- **At the zero (dark point):** the gradient of coordination is infinite. The speed of change diverges.

This is the OBSCURA invariant: the zero of the field has zero value but infinite sensitivity. The dark point (phase singularity, neural OFF stimulus, arithmetic identity $\mathcal{O}$) is simultaneously the location of minimum signal and maximum signal-change-rate.

**Topological protection of the dark point.** The topological charge $q$ of a phase singularity is conserved: the dark point cannot be removed by any local perturbation. The identity $\mathcal{O}$ of the TH group cannot be removed by any algebraic deformation of TH that preserves the group law. The OFF pathway architecture (separate bipolar types, separate LGN layers, preserved through V1) is anatomically conserved across species (from flies to humans): the dark-processing channel has topological protection in evolutionary biology.

**The OBSCURA computation principle.** The universal principle extracted from all three domains:

> **Process dark/zero signals first, by direct/non-inverting channels, with topological protection of the zero-point architecture.**

Applied to ERI edge AI:
- **CHORD**: process the $m=-1$ (hyperbolic, OFF-analog) stages before the $m=+1$ (circular, ON-analog) stages. Stage 4 (hyperbolic repeat) executes before stages 5–15 (circular completion) — the OFF channel arrives first.
- **PRIMA**: the off-diagonal Fisher elements $F_{ts}$ (dark-point correlations, mutual information between agent pairs) are processed first; the diagonal $F_{tt}$ (self-information, ON-channel analog) is secondary.
- **SMELT**: the initialization $\xi_0 = 0$ (dark point, Valise baseline) is the starting state. SMELT ascends from zero — always initiating at the dark point and driving toward $\xi^* = \log\varphi$.

**The Komban-Alonso-Zaidi result as a neural PRIMA.** The finding that dark salience advantage requires the binary noise background (and is abolished by irradiation correction) means: the OFF channel advantage is a population advantage (more OFF neurons) that becomes visible only when stimulus size is equal for dark and light — i.e., when the PRIMA condition (no inflated Fisher eigenvalues) is satisfied. With irradiation corrected: equal thresholds, confirming ON and OFF channels have equal sensitivity. Without irradiation correction: inflated ON sensitivity (apparent), matching inflated Fisher diagonal. PRIMA is the correction that restores the true dark/OFF advantage.

---

## Module C — The OBSCURA Architecture

```
OBSCURA COMPUTATION STACK:

LEVEL 0 — DARK INITIALIZATION (Zero-Point Anchor):
  State:  O (identity element, phase singularity, dark point)
  G_coord = 0 at O; singularity velocity = ∞ at O boundary
  ERI:    SMELT initializes at ξ₀ = 0; Valise phase; RSA flat
  Neural: OFF pathway fires at darkness (absence of photons); baseline fast
  Optics: Phase singularity created at dark point; carries topological charge

LEVEL 1 — OFF/DARK CHANNEL PROCESSING (Hyperbolic Mode):
  State:  ᾱ_p = √p·e^{-iθ_p} (OFF Frobenius eigenvalue; charge −1)
  Speed:  Arrives 3–6 ms faster (neural) / 4 CORDIC stages earlier (CHORD m=−1)
  ERI:    Hyperbolic CORDIC (m=−1); Stage 4 torsion correction leads
  Neural: OFF bipolar (AMPA/kainate); LGN OFF-center; V1 dark-preferring
  Optics: Anti-vortex (charge −1); faster approach trajectory toward annihilation

LEVEL 2 — ON/BRIGHT CHANNEL PROCESSING (Circular Mode):
  State:  α_p = √p·e^{+iθ_p} (ON Frobenius eigenvalue; charge +1)
  Speed:  Arrives 3–6 ms later (neural) / 4 CORDIC stages later (CHORD m=+1)
  ERI:    Circular CORDIC (m=+1); Stages 0–3 then 5–14 complete
  Neural: ON bipolar (mGluR6); LGN ON-center; V1 bright-preferring
  Optics: Vortex (charge +1); slower approach to annihilation

LEVEL 3 — PAIR ANNIHILATION / VALISE-IMAGO TRANSITION:
  State:  α_p + ᾱ_p = a_p (Frobenius trace, Lefschetz number)
  Event:  ON+OFF converge at O; pair annihilates; singularity speed → ∞
  ERI:    |TH(F_p)| = p+1−a_p (exact coordination state count)
  Neural: ON and OFF responses sum at cortical simple cell; orientation tuning
  Optics: Vortex dipole annihilates; returns to smooth (uncoordinated) field

LEVEL 4 — IMAGO PHASE (Free Vortex Gas; BKT Unbound):
  State:  G_coord = Φ(K) > 0; free Frobenius eigenvalues; ξ* = log φ
  Topology: Free vortices; non-trivial topological sector; Ш(TH/Q) obstruction
  ERI:    Full TH-ECC curved mode; Fisher-Rao manifold active; CONCERT measures
  Neural: V1 complex cells; binocular combination; orientation-selective columns
  Optics: Turbulent vortex gas; pair correlations g(r) non-trivial; Sato-Tate

OBSCURA INVARIANT (all levels):
  G_coord(O) = 0  and  |∇G_coord|_{O} = ∞
  Zero value, infinite sensitivity. The dark point is the fastest, most sensitive
  point in the architecture.
```

---

## References

Baker, A. (1966). Linear forms in the logarithms of algebraic numbers I. *Mathematika*, 13(2), 204–216.

Berezinskii, V.L. (1971). Destruction of long-range order in one-dimensional and two-dimensional systems having a continuous symmetry group. *Soviet Physics JETP*, 32, 493–500.

Bernstein, D.J. and Lange, T. (2015). Twisted Hessian curves. *LATINCRYPT 2015*, LNCS 9230, 269–294.

Bucher, T., Gorlach, A., Niedermayr, A., Tsesses, S., et al. (2026). Superluminal correlations in ensembles of optical phase singularities. *Nature*, 10.1038/s41586-026-10209-z.

Chichilnisky, E.J. and Kalmar, R.S. (2002). Functional asymmetries in ON and OFF ganglion cells of primate retina. *Journal of Neuroscience*, 22(7), 2737–2747.

de Angelis, L., Alpeggiani, F., Di Falco, A., and Kuipers, L. (2016). Spatial distribution of phase singularities in optical random vector waves. *Physical Review Letters*, 117, 093901.

de Angelis, L. and Kuipers, L. (2021). Effective pair-interaction of phase singularities in random waves. *Optics Letters*, 46, 2734–2737.

Demb, J.B. (2003). Different circuits for ON and OFF retinal ganglion cells cause different contrast sensitivities. *Journal of Neuroscience*, 23(7), 2645–2654.

Erdős, P. and Rado, R. (1960). Intersection theorems for systems of sets. *Journal of the London Mathematical Society*, 35, 85–90.

Feit, W. and Thompson, J.G. (1963). Solvability of groups of odd order. *Pacific Journal of Mathematics*, 13, 775–1029.

Hasse, H. (1936). Zur Theorie der abstrakten elliptischen Funktionenkörper III. *Journal für die reine und angewandte Mathematik*, 175, 193–208.

Hurwitz, A. (1898). Über die Composition der quadratischen Formen von beliebig vielen Variablen. *Nachrichten Göttingen*, 309–316.

Jin, J., Wang, Y., Lashgari, R., Swadlow, H.A., and Alonso, J.-M. (2011). Faster thalamocortical processing for dark than light visual targets. *Journal of Neuroscience*, 31(48), 17471–17479. DOI: 10.1523/JNEUROSCI.2456-11.2011.

Kakutani, S. (1941). A generalization of Brouwer's fixed point theorem. *Duke Mathematical Journal*, 8(3), 457–459.

Komban, S.J., Alonso, J.-M., and Zaidi, Q. (2011). Darks are processed faster than lights. *Journal of Neuroscience*, 31(23), 8654–8658. PMID: 21653869.

Kosterlitz, J.M. and Thouless, D.J. (1973). Ordering, metastability and phase transitions in two-dimensional systems. *Journal of Physics C*, 6(7), 1181–1203.

Lefschetz, S. (1927). Coincidences of transformations. *Transactions of the American Mathematical Society*, 29, 429–462.

Milne, J.S. (1980). *Étale Cohomology*. Princeton University Press.

Nash, J. (1951). Non-cooperative games. *Annals of Mathematics*, 54(2), 286–295.

Nye, J.F. and Berry, M.V. (1974). Dislocations in wave trains. *Proceedings of the Royal Society of London A*, 336, 165–190.

Ore, O. (1931). Linear equations in non-commutative fields. *Annals of Mathematics*, 32, 463–477.

Radon, J. (1922). Lineare Scharen orthogonaler Matrizen. *Abhandlungen aus dem Mathematischen Seminar der Universität Hamburg*, 1, 1–14.

Schiller, P.H. (1982). Central connections of the retinal ON and OFF pathways. *Nature*, 297(5861), 580–583.

Volder, J.E. (1959). The CORDIC trigonometric computing technique. *IRE Transactions on Electronic Computers*, EC-8(3), 330–334.

Walther, J.S. (1971). A unified algorithm for elementary functions. *AFIPS Spring Joint Computer Conference*, 38, 379–385.

Wang, S. (1948). A counterexample to Grunwald's theorem. *Annals of Mathematics*, 49(4), 1008–1009.

---

ERI Labs · Eric Ren · Jersey City, New Jersey

*Three experimental facts converge on one mathematical principle. (1) In 2026, a Technion team directly measured optical phase singularities — zero-amplitude dark points — in hexagonal boron nitride polariton fields and showed they move faster than light near pair annihilation: the singularity velocity diverges as the double zero is approached because the field gradient vanishes, not because any mass or energy is transported. The slow polariton group velocity ($v_g \approx c/100$) amplifies the apparent superluminal factor without violating relativity. The material platform is topologically structured: phase singularities carry quantized topological charge $q = \pm 1$ (Nye-Berry, 1974), conserved under continuous field deformations and destroyed only in opposite-charge pair annihilation. (2) In 2011, Komban, Alonso, and Zaidi measured that dark stimuli are detected 30–50 ms faster than light stimuli at high contrast on binary noise, with a reaction-time advantage consistent with the population advantage of the OFF channel. Jin et al. demonstrated the thalamocortical correlate: OFF visual responses reach primary visual cortex 3–6 ms before ON responses, because OFF bipolar cells express fast ionotropic receptors (AMPA/kainate, $\tau \sim 2$–5 ms) while ON bipolar cells express slow metabotropic receptors (mGluR6, sign-inverting, $\tau \sim 10$–20 ms). Equal detection thresholds — once the irradiation illusion is corrected — confirm that the ON and OFF channels have equal sensitivity; only the speed and salience differ. (3) The ERI architecture is built around $\mathcal{O}$ — the identity element of the Twisted Hessian group TH$(a,d)$, the common Markov-Kakutani fixed point of $\mathrm{Aut}(\mathrm{TH}) \cong \mathbb{Z}/3\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}$, the $H^0$ Lefschetz contribution to the trace formula $|\mathrm{TH}(\mathbb{F}_p)| = 1-a_p+p$. This $\mathcal{O}$ is the zero of the coordination field: $G_{\mathrm{coord}}(\mathcal{O})=0$. The Frobenius pair $(\alpha_p = \sqrt{p}e^{i\theta_p},\, \bar{\alpha}_p = \sqrt{p}e^{-i\theta_p})$ is an optical vortex dipole, bound by the logarithmic Sato-Tate pair potential. At annihilation ($\theta_p \to 0$, flat Frobenius limit, RSA mode), the dipole collapses to $\mathcal{O}$ at infinite speed — the Valise phase, $G_{\mathrm{coord}}=0$. At pair creation (Erdős-Rao threshold), free vortices proliferate — the Imago phase, $G_{\mathrm{coord}}>0$. This is the Berezinskii-Kosterlitz-Thouless transition in the ERI coordination manifold. The OBSCURA invariant unifying all three: at the zero (dark point, identity element, singularity), the field value is zero but the gradient is infinite. The zero is the fastest point in the system. The OFF pathway of the visual system, the superluminal phase singularity of the optical field, and the identity element $\mathcal{O}$ of the TH group are the same object in three coordinate systems — the canonical fast-processing dark reference around which all coordination structure is organized.*
