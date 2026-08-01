### 📘 Scarf Operator — NDH‑Triadic‑Core v1.0  
**Holonomy Parallel Transport Operator**

---

#### 1. Purpose

The **Scarf Operator** defines **holonomy‑safe parallel transport** of tensors along paths in the NDH manifold.  
Where Crane governs *event activation*, Scarf governs *movement*:

- how tensors move along curves  
- how holonomy is respected  
- how stability envelopes are preserved during transport  

---

#### 2. Operator Definition

Let \( \mathcal{M} \) be the NDH manifold with connection \( \nabla \) and holonomy field \( \mathcal{H} \).

For a smooth curve \( \gamma : [0,1] \to \mathcal{M} \) and tensor \( T_0 \) at \( \gamma(0) \), define Scarf:

\[
\mathcal{S}(\gamma, T_0) = T_1
\]

where \( T_1 \) is the parallel‑transported tensor at \( \gamma(1) \), subject to:

\[
\nabla_{\dot{\gamma}(t)} T(t) = 0
\quad \text{and} \quad
\|\mathcal{H}(\gamma(t))\| \le H_{\max}
\quad \forall t \in [0,1]
\]

Scarf only permits transport along **holonomy‑bounded paths**.

---

#### 3. Stability Constraint

Transport is **Scarf‑safe** if:

- the entire path \( \gamma \) lies in the operator‑safe region \( \mathcal{R}_{\text{safe}} \) defined by the Manifold Operator, and  
- holonomy deviation remains bounded:

\[
\|\mathcal{H}(\gamma(t))\| \le H_{\max}
\quad \forall t
\]

This ensures:

- no holonomy spikes  
- no instability during transport  
- continuity of tensor behavior along the path  

---

#### 4. Relationship to Crane and Manifold

- **Manifold Operator**: defines \( \mathcal{M} \), \( \nabla \), \( \mathcal{H} \), \( S(x) \), and \( \mathcal{R}_{\text{safe}} \).  
- **Crane Operator**: decides *if* an event may occur at a point (curvature‑neutral activation).  
- **Scarf Operator**: decides *how* tensors move along paths (holonomy‑safe transport).

Together, they form the **Triadic Operator Suite**:

- point safety (Crane)  
- path safety (Scarf)  
- substrate geometry (Manifold)

---

#### 5. Provenance Footer

```markdown
---
Provenance: Scarf-Operator-v1.0 defines the holonomy parallel transport
operator for the NDH-Triadic-Core. It specifies holonomy-bounded tensor
transport along operator-safe paths in the NDH manifold and completes the
triadic relationship between Crane, Scarf, and the Manifold Operator required
for the NDH Stability Manifold.

Maintainer: Borealis S. Hedling • Dublin, Ireland • 2026
---
```

---
