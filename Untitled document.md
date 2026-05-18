# **1\. Introduction**

Galaxies rotate too fast. Their outer stars move at speeds that cannot be explained by Newtonian gravity sourced by visible matter alone. This empirical fact appears in three equivalent forms: the flattening of rotation curves, the baryonic Tully–Fisher relation (BTFR), and the radial acceleration relation (RAR). All three point to a characteristic acceleration scale

a0  ≈ 1.2 x 10-10m/s2

which emerges with a precision that suggests an underlying physical origin rather than coincidence.

The standard explanations fall into two broad categories. In the first, additional unseen matter supplies the missing gravitational field. In the second, the law of gravity is modified at low accelerations. Both approaches reproduce many observations, but neither explains why the same acceleration scale appears across independent galactic relations, nor why its numerical value is close to the cosmological quantity cH0. These coincidences motivate a third possibility: that the vacuum itself contributes to the gravitational source term in a way that depends on the global gravitational environment.

Vacuum energy already contributes to curvature in general relativity. If the vacuum is not a fixed background but a medium whose state depends on the depth and structure of the surrounding potential well, then a galaxy may imprint structure onto the vacuum, and this structure may manifest as an effective gravitational field. No existing relativistic field equation describes such a mechanism, so we explore it phenomenologically by constructing a nonlocal source operator in the Newtonian limit. The operator acts on the baryonic density as a proxy for the curvature field and produces an effective density distribution determined by a kernel K. The goal is not to modify gravity but to model how the vacuum might respond to matter through a causal, nonlocal process.

This approach leads to six structural results.

1. Any kernel with infrared behavior K(k)∝1/k produces an effective density profile ρeff(r)∝1/r2, yielding flat rotation curves as a theorem.  
2. A unique nonlinear normalization proportional to Ψ−1/2, where Ψ is the global potential depth, produces the BTFR without tuning.  
3. Causality requires a retarded evolution equation for Ψ, introducing assembly‑history memory and predicting a measurable suppression of the effective potential in disturbed systems.  
4. The framework is consistent with cosmological constraints and possesses a de Sitter fixed point.  
5. The kernel is identified with the retarded Green’s function of the conformally coupled scalar field on de Sitter space, fixed by four independent constraints.  
6. The entire structure reduces to a single dimensionless quantity, the **Sitter number**  
   **S \=a0cHΛ**

which measures the ratio between the acceleration at which matter imprints structure on the vacuum and the acceleration at which the vacuum becomes thermally active due to the de Sitter horizon.

The remainder of the paper develops these results in sequence. The framework is complete up to the Sitter number. The remaining theoretical work is finite, computable, and testable with existing and forthcoming observations, including high‑redshift rotation curves from JWST. The Sitter number is the verdict.

# **2\. Motivation: Vacuum Response as a Physical Hypothesis**

The starting point for this work is the observation that vacuum energy contributes to spacetime curvature. In general relativity, the vacuum is not an inert backdrop but a stress–energy component capable of shaping geometry. This raises a natural question: **if the vacuum contributes to curvature, might its state depend on the gravitational environment?**

Galaxies provide deep, extended potential wells whose global structure is not captured by local curvature scalars alone. If the vacuum is sensitive to the *global* potential depth rather than only to local curvature, then a galaxy may imprint structure onto the vacuum, and this structure may manifest as an effective gravitational field. In this view, the “missing mass” phenomenon would arise not from additional matter but from the vacuum’s nonlocal response to the baryonic distribution.

No existing relativistic field equation describes such a mechanism.

To explore the idea phenomenologically, we therefore construct a **nonlocal source operator** in the Newtonian limit. The operator acts on the baryonic density as a proxy for the curvature field and produces an effective density distribution determined by a kernel K. The goal is not to modify gravity but to model how the vacuum might contribute to the gravitational source term through a causal, nonlocal response.

Two empirical clues motivate this approach:

**The acceleration scale is global.**  

1. The BTFR and RAR depend on the total baryonic mass and the global potential depth, not on local density. This suggests that any underlying mechanism must be sensitive to the integrated gravitational environment.

**The acceleration scale is cosmological.**  

2. Numerically,

a0\~cH0

hinting that the vacuum — whose properties are set by cosmological boundary conditions — may determine the scale.

These considerations motivate treating the vacuum as a medium with a causal, nonlocal response to matter. The simplest mathematical object with these properties is a **retarded Green’s function** on a curved background. Once this assumption is made, the kernel theorem, the BTFR normalization, the emergence of assembly‑history memory, the identification of the kernel with the conformally coupled scalar on de Sitter space, and the reduction to the Sitter number follow with little freedom.

# **3\. Methodological Note: Human–LLM Co‑Analysis**

The development of this framework did not follow the traditional path of a specialist working within a single subfield. Instead, it emerged from an iterative process that combined human conceptual exploration with large‑language‑model analytical assistance. The author is not a professional cosmologist or gravitational theorist; progress arose from a dialogic method in which human intuition, pattern recognition, and synthesis were paired with the LLM’s ability to rapidly examine mathematical structures, identify inconsistencies, and explore alternative formulations.

This approach did not automate theoretical reasoning — it amplified it.

The key structural results presented in this paper — the infrared kernel theorem, the uniqueness of the Ψ−1/2 normalization, the emergence of assembly‑history memory from the retarded equation, the identification of the kernel with the conformally coupled scalar Green’s function on de Sitter space, and the reduction of the framework to the Sitter number — were not generated by automated search. They arose from a cycle of:

1. human hypothesis formation,  
2. LLM‑assisted exploration of mathematical consequences,  
3. human interpretation and refinement, and  
4. repeated stress‑testing of assumptions.

This methodology is unusual in theoretical physics, but increasingly relevant as LLMs become capable of assisting with high‑dimensional conceptual exploration. The scientific claims of the paper stand independently of the method by which they were discovered, but transparency about the process is appropriate given the novelty of the approach.

# **4\. The Kernel Theorem**

A central structural result of this framework is that **any** nonlocal source operator whose kernel has infrared behavior

K(k) ∝ 1k (k0) 

produces an effective density profile

eff (r) ∝ 1r2(r)   

around compact sources. This result is independent of the detailed form of the kernel at finite k and does not rely on fitting or tuning. It follows from the mathematics of convolution and the Fourier transform.

### **4.1 Setup**

We model the vacuum response to baryonic matter through a nonlocal source operator acting on the baryonic density:

ρeff(r)=∫K(∣r−r′∣) ρ(r′) d3r′.

Here K(r) is a spherically symmetric kernel representing the vacuum’s response to the gravitational environment. The total gravitational potential is sourced by

ρtot=ρ+ρeff.

### **4.2 Fourier‑space argument**

The convolution theorem gives

ρ\~eff(k)=K\~(k) ρ\~(k),

where tildes denote Fourier transforms. For any compact baryonic source,

ρ\~(k)→constant(k→0).

Thus the large‑radius behavior of ρeff(r) is controlled entirely by the small‑k behavior of K\~(k).

If

K\~(k)∝1k,

then the inverse Fourier transform yields

K(r)∝1r2,

and therefore

ρeff(r)∝1r2(r→∞).

This is the unique radial profile whose enclosed mass grows linearly with radius:

Meff(r)∝r,

which in turn produces an asymptotically flat circular velocity:

v2(r)=GMeff(r)r=constant.

### **4.3 Interpretation**

This result shows that **flat rotation curves do not require dark matter halos or modified gravity**. They arise automatically from the infrared structure of the vacuum response kernel. The only requirement is that the kernel be sufficiently long‑ranged to produce a 1/k divergence at small k. The detailed short‑distance behavior of K(r) is irrelevant for the asymptotic dynamics.

### **4.4 Structural significance**

The Kernel Theorem is the first of the six structural pillars of the framework:

* It explains flat rotation curves without tuning.  
* It identifies the infrared behavior of the vacuum response as the key physical ingredient.  
* It constrains the form of any underlying relativistic theory: the kernel must have a 1/k infrared tail.  
* It sets the stage for the nonlinear normalization and the emergence of the BTFR.

The remainder of the paper builds on this result, showing how the normalization, causality, cosmology, and de Sitter geometry complete the structure.

