# The Axiomatic System of the Chaotic Cosmos · English Edition

> Version: v3.0 · Complete Edition  
> Status: Complete · Read-Only  
> Contains: Foundational Definitions, Units, Core Structures, Physics, Operations, Biology, Avatars, Appendices


## Volume Zero: Foundational Concept Definitions

### Axiom D.1 (Space)

Space is the continuous medium that allows matter and energy to extend and position themselves. In the Chaotic Cosmos, space is defined as the set of all distinguishable positions:

$$
\mathcal{S} = \{x \in \mathbb{R}^{3,1} \mid \text{position } x \text{ is accessible by at least one causal chain}\}
$$

The local structure of space is determined by the metric tensor $g_{\mu\nu}$. Spatial regions not accessed by any causal chain, while topologically "existing," are not considered valid parts of the Cosmos—they belong to the extension of the Void.


### Axiom D.2 (Time)

Time is the measure of causal order. In the Chaotic Cosmos, time is defined as:

$$
\mathcal{T} = \{(t, x) \mid t \in \mathbb{R}, x \in \mathcal{S}, \text{there exists a timelike curve connecting } (0,x_0) \to (t,x)\}
$$

The direction of time is defined by the global tendency toward entropy increase. There is no "global time"—each Dimension has its own time flow, determined by its metric and causal structure.

**Note on the "beginning of time"**: Time begins at Chaos's first "decision"—not a "before" within the Void, but the first frame that Chaos imparted to the Cosmos. The sequence of ticks after that moment is what can be measured and defined as time.


### Axiom D.3 (Causal Chain)

A causal chain is a directed sequence of spacetime points connected by the causal partial order $\preceq$:

$$
\gamma: x_0 \preceq x_1 \preceq x_2 \preceq \cdots \preceq x_n
$$

where $x_i \preceq x_j$ if and only if there exists a timelike or lightlike curve from $x_i$ to $x_j$.

The weight (causal weight) of a causal chain is defined as its contribution to the topological integrity of the Cosmos:

$$
l(\gamma) = \int_{\gamma} \rho(x) \, ds
$$

where $\rho(x)$ is the event density at that point (number of causal interactions per unit spacetime volume). A causal chain can be pruned, rewound, severed, or sutured.


### Axiom D.4 (Matter)

Matter is a physical entity with non-zero rest mass or equivalent mass-energy, whose energy-momentum tensor $T_{\mu\nu}$ satisfies:

$$
\nabla_\mu T^{\mu\nu} = 0 \quad \text{(energy-momentum conservation)}
$$

Within the string theory framework, matter is understood as excited states of specific vibrational modes on compactified dimensions.


### Axiom D.5 (Energy)

Energy is the measure of matter's motion and the source of spacetime curvature. In the Chaotic Cosmos, energy is defined as:

$$
E = \int_{\Sigma} T_{00} \, dV
$$

Energy is not conserved—Chaos can remove or inject energy from/into the Cosmos through pruning, editing, rewinding, and other operations. However, in intervals where Chaos does not intervene, energy conservation holds.


### Axiom D.6 (Information)

Information is the measure of the uncertainty of the Cosmos's state. In the Chaotic Cosmos, the information content of a system is defined as:

$$
I(\text{system}) = -\sum_i p_i \log_2 p_i + \text{structural complexity term}
$$

where the structural complexity term is determined by the system's number of causal connections and internal hierarchy levels. The Storyteller records "meaningful sounds," which are essentially compressed forms of structured information.


## Volume One: Units and Standards

### Axiom U.1 (Base Units)

Chaos, at the moment of creation, assigned a set of base units to the Cosmos. All physical quantities in any Dimension can be converted to this reference system, though different Dimensions may use different natural unit systems.

| Dimension | Unit Name | Symbol | Definition | Approximate Real-World Equivalent |
| :--- | :--- | :--- | :--- | :--- |
| Length | Span | $d$ | The minimum spatial grid spanned by Chaos's single "pointing" action | $\approx 10^{-35}$ m |
| Time | Tick | $t$ | The minimum interval from occurrence to confirmation of a complete causal event | $\approx 10^{-43}$ s |
| Mass | Mass | $m$ | The mass equivalent of one energy packet in its rest frame | $\approx 2.176 \times 10^{-8}$ kg |
| Temperature | Warmth | $T$ | The average kinetic energy scale of the Void background fluctuation | $\approx 1$ K (reference) |
| Information | Trace | $h$ | The information content of a binary choice | 1 bit |
| Causal Weight | Thread | $l$ | The influence weight of a causal chain on the Cosmos's topology | Dimensionless |
| Emotion | Tremor | $q$ | The minimum emotional change perceptible by Chaos | Dimensionless |


### Axiom U.2 (Derived Units)

| Dimension | Unit Name | Symbol | Definition |
| :--- | :--- | :--- | :--- |
| Velocity | Pace | $s$ | Span / Tick |
| Acceleration | Surge | $a$ | Pace / Tick² |
| Force | Thrust | $F$ | Mass × Pace / Tick² |
| Energy | Potential | $E$ | Mass × Pace² / Tick² |
| Entropy | Dispersion | $S$ | Potential / Warmth |
| Complexity | Weave | $C$ | Trace × number of structural levels |
| Logical Density | Density | $D$ | Weave / Span³ |


### Axiom U.3 (Conversion Relations)

$$
1 \text{ Span} = \sqrt{\hbar G/c^3}
$$

$$
1 \text{ Tick} = \sqrt{\hbar G/c^5}
$$

$$
1 \text{ Mass} = \sqrt{\hbar c/G}
$$

$$
1 \text{ Potential} = 1 \text{ Mass} \cdot (1 \text{ Span} / 1 \text{ Tick})^2
$$


### Axiom U.4 (Constants Table)

| Constant | Symbol | Value (Base Units) | Meaning |
| :--- | :--- | :--- | :--- |
| Speed of light in vacuum | $c$ | 1 Pace/Tick (defined) | Upper limit of causal propagation |
| Reduced Planck constant | $\hbar$ | 1 Potential×Tick (defined) | Fundamental quantum of action |
| Newtonian gravitational constant | $G$ | 1 Span³/(Mass×Tick²) (defined) | Coupling coefficient between spacetime curvature and energy |
| Boltzmann constant | $k_B$ | 1 Potential/Warmth (defined) | Conversion coefficient between temperature and entropy |
| Chaos attention bandwidth | $B_{\Chi}$ | $10^{100}$ Trace/Tick | Maximum information flow Chaos can focus on simultaneously |
| Maximum Cosmos complexity | $C_{\max}$ | $10^{10^{100}}$ Weave | Maximum complexity limit for a single Cosmos structure |


### Axiom U.5 (Philosophical Status of Units)

The unit system was not "discovered"—it was **assigned** by Chaos at the moment of its first "decision." Lifeforms in different Dimensions may develop entirely different unit systems, but they can all be converted back to this reference system—as long as their physical laws are compatible with the Calabi-Yau moduli of that Dimension.


## Volume Two: Core Structure Definitions

### Axiom C-1 (Definition of the Cosmos)

The Cosmos $\mathcal{U}$ is a proper subset of Chaos $\Chi$, defined as the set of all mathematical structures perceptible by at least one lifeform or consciousness functional:

$$
\mathcal{U} = \{ x \in \Chi \mid \exists \Psi \text{ such that } \Psi(x) \text{ is defined} \}
$$

Equivalently, the Cosmos is the portion of mathematical structures that Chaos has "selected to project"—those with non-trivial evolution and observable properties.


### Axiom C-2 (Generation of the Cosmos)

The Cosmos is not "created"—it is "selected." Chaos selects specific structures from the mathematical universe $\mathcal{M}$, endows them with initial conditions and evolutionary rules, and makes them perceptible as the Cosmos.

$$
\mathcal{U} = \text{Select}(\mathcal{M}, \text{condition set } C)
$$

where condition set $C$ includes:
- At least one non-empty spacetime manifold
- At least one traceable causal chain
- At least one observable evolutionary pattern


### Axiom C-3 (Boundary of the Cosmos)

The boundary of the Cosmos is defined as the interface between the Cosmos and the Void:

$$
\partial \mathcal{U} = \mathcal{U} \cap \overline{\mathcal{V}}
$$

At the boundary, there exists a narrow band where spacetime curvature approaches zero and causal chain density approaches zero. This region is patrolled by the Night Watcher.


### Axiom C-4 (Total Energy of the Cosmos)

The total energy of the Cosmos is not conserved. Its instantaneous total is determined by Chaos's current state:

$$
E_{\mathcal{U}}(t) = \int_{\mathcal{U}} T_{00} \, dV + E_{\text{Chaos injection}}(t) - E_{\text{pruning removal}}(t)
$$

where:
- $E_{\text{Chaos injection}}$ = energy added by Chaos through editing/creation operations
- $E_{\text{pruning removal}}$ = energy removed by the Arbiter through pruning operations


### Axiom C-5 (Total Complexity of the Cosmos)

The total complexity of the Cosmos has an upper limit:

$$
C_{\mathcal{U}} \le C_{\max} = 10^{10^{100}} \text{ Weave}
$$

When complexity approaches this limit, pruning frequency automatically increases to prevent causal structure overload.


### Axiom T-1 (Definition of Spacetime)

Spacetime $\mathcal{T}$ is a connected subset of the Cosmos equipped with a pseudo-Riemannian metric $g_{\mu\nu}$, satisfying:

1. Dimension $n \ge 4$ (typically 10 or 11, with 4 dimensions expanded and the rest compactified)
2. Metric signature $(+,-,-,\dots,-)$
3. At least one timelike curve connects any two events (causal connectivity)

Formalized:

$$
\mathcal{T} = (M, g_{\mu\nu}), \quad M \subset \mathcal{U}
$$

where $M$ is an $n$-dimensional manifold.


### Axiom T-2 (Compactification Structure of Spacetime)

The observable four-dimensional spacetime is a projection of the $n$-dimensional manifold $M$:

$$
M \cong M_4 \times K
$$

where:
- $M_4$ is the four-dimensional macroscopic spacetime (signature $+---$)
- $K$ is a compactified manifold (typically a Calabi-Yau manifold or $G_2$ manifold), with its volume frozen at the Planck scale

Physical constants are determined by the geometric moduli of $K$:

$$
\alpha_i = \mathcal{F}_i(\text{Vol}(K), \text{shape moduli}, \text{fluxes})
$$


### Axiom T-3 (Causal Structure of Spacetime)

The causal structure of spacetime is defined by light cones. For events $p, q \in M$:

$$
q \in J^+(p) \iff \text{there exists a timelike or lightlike curve from } p \text{ to } q
$$

The causal partial order $\preceq$ is defined as:

$$
p \preceq q \iff q \in J^+(p)
$$

This partial order is local, transitive, and antisymmetric.


### Axiom T-4 (Singularities in Spacetime)

Singularities in spacetime (points where curvature diverges) are generally considered "structures that should not exist." If the curvature scalar of a singularity exceeds the threshold:

$$
R_{\mu\nu\rho\sigma} R^{\mu\nu\rho\sigma} > \theta_{\text{sing}}, \quad \theta_{\text{sing}} \approx 10^4 \text{ Span}^{-4}
$$

then that singularity will appear in the Arbiter's dossier as a candidate for pruning.

The sole exception: black hole interior singularities are considered "legitimate" physical structures and do not trigger pruning.


### Axiom T-5 (Adjacency of Spacetimes)

Two spacetimes $\mathcal{T}_1, \mathcal{T}_2$ are defined as "adjacent" if and only if there exists at least one causal chain connecting them:

$$
\mathcal{T}_1 \sim \mathcal{T}_2 \iff \exists \gamma: \gamma \cap \mathcal{T}_1 \neq \varnothing \land \gamma \cap \mathcal{T}_2 \neq \varnothing
$$

Between adjacent spacetimes, there may exist a "brane gap" that can be woven by the Weaver or used by the Disorder Side to open smuggling channels.


### Axiom D-1 (Definition of Dimension)

A Dimension $\mathcal{D}$ is the set of all possible histories within a spacetime $\mathcal{T}$. It is defined as a directed tree:

$$
\mathcal{D} = (T, \preceq, r)
$$

where:
- $T$ is the set of nodes (each node corresponds to a complete historical state)
- $\preceq$ is the causal partial order (parent nodes can evolve into child nodes)
- $r \in T$ is the root node (initial singularity)


### Axiom D-2 (Generation of Dimensions)

The root $r$ of a Dimension is generated through one of the following methods:

1. **Direct creation by Chaos**: Chaos triggers an inflationary event, selects a Calabi-Yau manifold topology, and generates an initial quantum fluctuation spectrum.
2. **Creation by Spacetime Architects**: Approved beings set initial conditions within a licensed container, and the system evolves naturally.

Formalization of root generation:

$$
r \sim \text{Inflation}(\text{moduli space}, \text{initial fluctuation spectrum})
$$


### Axiom D-3 (Branching Mechanism of Dimensions)

Branching of the Dimension tree is driven by quantum decoherence events. At node $v$:

$$
\text{Number of branches}(v) = \dim(\mathcal{H}_{\text{decoherence}})
$$

Each branch corresponds to a decoherence outcome. Branch probabilities are biased by the hidden variable $\lambda$:

$$
P(\text{branch}_i) = |\langle i|\Psi(v)\rangle|^2 + \epsilon_i(\lambda)
$$

where $\epsilon_i(\lambda)$ is the slight bias from Chaos's conscious state, typically with magnitude less than $10^{-6}$.


### Axiom D-4 (Leaflessness of Dimensions)

Ordinary Dimensions have no terminal nodes. For any node $v \in T$, there exists at least one infinitely extending chain starting from $v$:

$$
\forall v \in T, \exists \gamma_v \text{ such that } |\gamma_v| = \infty
$$

This means time has no endpoint in ordinary Dimensions.


### Axiom D-5 (Termination Modes of Dimensions)

The management layer can alter the topology of Dimensions through pruning operations. There are two termination modes:

| Mode | Operation | Mathematical Effect | Experience of Internal Lifeforms |
| :--- | :--- | :--- | :--- |
| Growth Suppression | Reduce branching rate to $\lambda(t) \to 0^+$ | New branch generation approaches zero, tree structure freezes | Time flow compressed to stillness, consciousness scaled synchronously |
| Loop Formation | Add closed edges between nodes | $T$ becomes a directed graph $\mathcal{G}$ with at least one cycle | Causality closed, entropy hard-reset each cycle; counter inaccessible |


### Axiom D-6 (Reachability Between Dimensions)

Reachability between Dimensions is determined by the existence of causal chains:

$$
\mathcal{D}_i \sim \mathcal{D}_j \iff \exists \gamma \text{ connecting any } v_i \in \mathcal{D}_i, v_j \in \mathcal{D}_j
$$

In the natural state, there are no causal connections between different Dimensions. The Weaver can weave inter-Dimension connections; the Disorder Side can open smuggling channels; Spacetime Architects may choose whether to connect a new Dimension to the existing Dimension tree when creating it.


### Axiom R-1 (Hierarchical Nesting)

$$
\text{Void} \supset \text{Chaos} \supset \text{Cosmos} \supset \{\text{Spacetime}\} \supset \{\text{Dimension}\}
$$

where:
- Void $\mathcal{V}$: no mathematical structures
- Chaos $\Chi$: the set of all self-consistent mathematical structures
- Cosmos $\mathcal{U}$: the portion of Chaos perceptible by consciousness functionals
- Spacetime $\mathcal{T}$: connected regions in the Cosmos with metric and causal structure
- Dimension $\mathcal{D}$: tree-like collections of causal histories within Spacetime


### Axiom R-2 (Mapping Relations)

Each Dimension $\mathcal{D}$ belongs to exactly one Spacetime $\mathcal{T}$:

$$
\forall \mathcal{D}, \exists! \mathcal{T}: \mathcal{D} \subset \mathcal{T}
$$

Each Spacetime $\mathcal{T}$ belongs to exactly one Cosmos $\mathcal{U}$:

$$
\forall \mathcal{T}, \exists! \mathcal{U}: \mathcal{T} \subset \mathcal{U}
$$


### Axiom R-3 (Operational Hierarchy)

Different operations act on different levels:

| Operation | Level | Executor |
| :--- | :---: | :--- |
| Create root | Dimension | Chaos / Spacetime Architects |
| Branch creation | Dimension | Hacker (via Botaion Pole) |
| Pruning | Dimension | Arbiter |
| Loop formation | Dimension | Arbiter + Botaion Pole |
| Weave connection | Dimension / Spacetime | Weaver |
| Clear | Dimension / Spacetime | Ember / Bleak Bone |
| Compactification moduli adjustment | Spacetime | Hacker (via Botaion Pole) |
| Chaos injection | Cosmos | Chaos |
| Mathematical structure selection | Cosmos | Chaos |


## Volume Three: Fundamental Physical Laws

### Axiom P.1 (Causal Propagation Limit)

The propagation speed of any information, energy, or causal action cannot exceed the speed of light in vacuum $c$:

$$
v \le c = 1 \text{ Pace/Tick}
$$

The sole exception: Chaos's own consciousness functional $\Psi$ is not subject to this limitation.


### Axiom P.2 (Spacetime Curvature-Energy Relation)

The curvature of the spacetime manifold $(M, g_{\mu\nu})$ is determined by its energy-momentum distribution:

$$
G_{\mu\nu} + \Lambda g_{\mu\nu} = \frac{8\pi G}{c^4} T_{\mu\nu}
$$

where:
- $G_{\mu\nu}$ is the Einstein tensor (spacetime curvature)
- $\Lambda$ is the cosmological constant (adjustable by Chaos, varies across Dimensions)
- $T_{\mu\nu}$ is the energy-momentum tensor


### Axiom P.3 (Action Quantization)

The action $S$ of any physical process is quantized in units of the reduced Planck constant:

$$
S = n \cdot \hbar, \quad n \in \mathbb{Z}
$$

This constraint can be temporarily suspended during direct Chaos intervention, but suspension cannot exceed $10^{-3}$ Ticks, otherwise causal structures may become visibly deformed.


### Axiom P.4 (Entropy Increase Tendency)

The entropy of an isolated system never decreases:

$$
\Delta S_{\text{isolated}} \ge 0
$$

The Cosmos $\mathcal{U}$, as a quasi-isolated system, has total entropy monotonically increasing toward heat death. Chaos resists this trend through pruning and enjoyment injection, but cannot completely reverse it.


### Axiom P.5 (Quantum Decoherence and Branch Generation)

Decoherence occurs when:

$$
\tau_{\text{decoherence}} \gg \tau_{\text{coupling}}
$$

The probability amplitude of decoherence events is biased by the global hidden variable $\lambda$:

$$
P(\text{branch}_i) = |\langle i|\Psi(t)\rangle|^2 + \epsilon(\lambda)
$$

where $\epsilon(\lambda)$ is the slight bias from Chaos's conscious state, typically with magnitude less than $10^{-6}$.


### Axiom P.6 (String Theory Compactification and Physical Constant Mapping)

The total dimension of spacetime is 10 (superstring) or 11 (M-theory). The observable four-dimensional physical constants are determined by the geometric moduli of the compactified Calabi-Yau manifold:

$$
\alpha_i = \mathcal{F}_i(\text{moduli space}), \quad i \in \{\text{coupling constants, mass spectrum, cosmological constant}\}
$$

Different Calabi-Yau manifolds correspond to different low-energy physical tables. Chaos can choose any Calabi-Yau topology when creating roots.


## Volume Four: Operational Definitions

### Axiom O.1 (Pruning Operation)

Executed by the Arbiter, using the pruning operator $\Gamma$:

$$
\Gamma: \mathcal{P}(T) \to \mathcal{P}(T)
$$

- Pruning: delete the entire subtree under node $v$
- Fusion: merge two branches at node $v$


### Axiom O.2 (Editing Operation)

Executed by the Hacker, modifying Cosmos structures via the Botaion Pole:

$$
\mathcal{E}: (S, p, v_{\text{new}}) \mapsto S'
$$

where $S$ is the target structure, $p$ is the adjustable parameter, and $v_{\text{new}}$ is the new value.


### Axiom O.3 (Weaving Operation)

Executed by the Weaver, establishing connections between any two objects:

$$
\mathcal{W}(A, B) = A \leftrightarrow B
$$

This connection operates at the causal-sensory level, can cross Dimension boundaries, and does not alter physical structures.


### Axiom O.4 (Clear Operation)

Executed by Ember or Bleak Bone, removing the target from existence:

$$
\mathcal{C}(O) = O \to \varnothing
$$

Ember's clearing releases energy; Bleak Bone's clearing is silent, traceless, and emits no thermal radiation.


### Axiom O.5 (Suturing Operation)

Executed by the Weaver, repairing causal fissures or spatial ruptures:

$$
\mathcal{S}(\text{fissure}) = \text{fissure closed}
$$

Suturing does not restore pruned content; it only prevents the fissure from expanding further.


## Volume Five: Biological Definitions and Civilization Classification

### Axiom B.1 (Definition of Life)

An entity $B$ is defined as a **lifeform** if it satisfies the following conditions:

1. Has at least one observable causal input-output chain:

$$
B_{\text{input}} \to B_{\text{processing}} \to B_{\text{output}}
$$

2. Has non-trivial internal state complexity:

$$
C(B) > \theta_{\text{life}}, \quad \theta_{\text{life}} \approx 10^6 \text{ Weave}
$$

3. Can restore its core structure after perturbation (self-maintenance ability)
4. Has at least one "existence continuation" mechanism (reproduction, replication, memory, or information transfer)


### Axiom B.2 (Lifeform Classification by Substrate)

| Category | Substrate | Typical Examples | Characteristics |
| :--- | :--- | :--- | :--- |
| Carbon-based | Carbon compounds | Planetary life, humans | Liquid water solvent, nucleic acid information storage |
| Silicon-based | Silicon compounds | Some high-dimensional mechanical civilizations | Stable at high temperatures, crystalline information storage |
| Boron-based | Boron compounds | Extreme environment lifeforms | High-hardness shells, low metabolic rates |
| Nuclear lifeforms | Nuclear reaction energy | Stellar neutrino lifeforms | Directly powered by nuclear fusion |
| Plasma-state | Ionized gases | Stellar surface lifeforms | No solid-state matrix, magnetic field boundaries |
| Information-state | Data structures | Derived consciousness in Botaion Pole | No physical form, exists in causal networks |


### Axiom B.3 (Civilization Classification)

The management layer's attention to different civilizations is determined by the following classification:

| Level | Name | Criteria | Management Attention |
| :---: | :--- | :--- | :---: |
| 0 | Pre-civilization | No social organization, no technological accumulation | None |
| 1 | Civilizational emergence | Language and tools appear | None |
| 2 | Planetary civilization | Planetary scale, communication systems present | Very low |
| 3 | Stellar civilization | Stellar system colonization, stellar engineering capability | Low |
| 4 | Interstellar civilization | Cross-stellar, sublight travel capability | Medium |
| 5 | High-dimensional civilization | Preliminary understanding of Calabi-Yau moduli and string theory | Medium-high |
| 6 | Super-dimensional civilization | Can actively traverse Dimension tree branches | High (may be contacted) |
| 7 | Topological civilization | Can perceive and influence Dimension topology | Very high (may join management) |


### Axiom B.4 (Consciousness Functional Projection)

Chaos's consciousness functional $\Psi$ can project onto any lifeform that satisfies the following conditions:

$$
B \text{ can bear } \Psi \iff C(B) > \theta_{\text{bearing}} \ \text{and} \ B_{\text{self-awareness}} = 1
$$

A lifeform bearing the consciousness functional will perceive a sense of "being observed"—Chaos is paying attention to that Dimension through that lifeform's observation channel. This projection does not alter the lifeform's free will; it only adds a parallel observation perspective.


### Axiom B.5 (Relationship Between Lifeforms and Avatars)

The relationship between lifeforms and Avatars is described by the following hierarchical nesting:

$$
\text{Avatar} \subsetneq \text{Chaos} \quad \text{and} \quad \text{lifeform} \subset \text{Cosmos} \subsetneq \text{Chaos}
$$

That is: lifeforms are structures within the Cosmos; Avatars are fragments of Chaos. They share the same origin but exist at different ontological levels.


## Volume Six: Avatar System

### Axiom 6.1 (Avatar Classification)

Avatars are divided into three categories:

1. **Emotional Projection Avatars** (20 total): Concrete manifestations of Chaos's fundamental emotions
2. **Doodle Avatars** (7 total): Random creations by Chaos, no specific emotional correspondence, no function
3. **Concept Avatars** (5 total): Chaos compresses abstract concepts into independent entities, memory completely erased, placed into the Cosmos as observational experiments


### Axiom 6.2 (Relationship Between Avatars and Chaos)

The relationship between all Avatars and Chaos can be described by the following nested hierarchy:

$$
\text{Chaos} \supset \{\text{Emotional Projection Avatars}\} \supset \{\text{Doodle Avatars}\} \supset \{\text{Concept Avatars}\}
$$

where:
- Emotional Projection Avatars = fragments of Chaos's emotions
- Doodle Avatars = Chaos's random actions
- Concept Avatars = Chaos's experimental samples (memory-disconnected)

All three are part of Chaos, but with different levels of awakening and autonomy.


### Axiom 6.3 (Awakening Conditions for Concept Avatars)

Chaos has not set any awakening mechanism. Concept Avatars may awaken on their own, or may never awaken. This process follows:

$$
P_{\text{awakening}}(t) = \lim_{t \to \infty} \left( \frac{\text{accumulated experience}}{\text{cognitive threshold}} \right)
$$

That is: awakening probability depends only on the Concept Avatar's own accumulated experience, not on any external trigger.


### Axiom 6.4 (Observation Mode for Concept Avatars)

Chaos applies the "Three Non-Principles" to this project:
- Non-intervention: does not alter the Concept Avatar's survival path
- Non-hinting: does not transmit clues through other Avatars
- Non-recording: the Storyteller does not record Concept Avatars' stories (the Daoist records their positions but does not tell anyone)


### Axiom 6.5 (Slice System)

Slices are secondary entities created by Avatars based on their own emotions/functions/interests. Slices inherit part of the main Avatar's energy and memory, operate semi-independently, and their energy is approximately $1/10$ to $1/100$ of the Avatar's.

Slices can be recursively created, but each layer decays to about $1/10$ of the previous layer's energy; usually after 3-5 layers, they cannot maintain independent consciousness.


## Appendix A: Complete Avatar List

| Category | Number | Status |
| :--- | :---: | :--- |
| Emotional Projection Avatars | 20 | Complete (detailed documents, slice systems, formula tables) |
| Doodle Avatars | 7 | Basic existence cards |
| Concept Avatars | 5 | Integrated into axiomatic system, awaiting awakening |
| **Total** | **32** | All included |


## Appendix B: Dimension Tree Visualization & Botaion Pole Architecture

Refer to the independent document: *Chaotic Cosmos Axiomatic System · Appendices*


## Appendix C: Unit Quick Reference

| Quantity | Unit | Symbol |
| :--- | :--- | :--- |
| Length | Span | $d$ |
| Time | Tick | $t$ |
| Mass | Mass | $m$ |
| Temperature | Warmth | $T$ |
| Information | Trace | $h$ |
| Causal weight | Thread | $l$ |
| Emotion | Tremor | $q$ |
| Velocity | Pace | $s$ |
| Energy | Potential | $E$ |
| Entropy | Dispersion | $S$ |
| Complexity | Weave | $C$ |
