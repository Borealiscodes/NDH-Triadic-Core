### 📘 Crane Operator — NDH‑Triadic‑Core v1.1  
**Holonomy Curvature Event Operator**

---

#### 1. Purpose

The **Crane Operator** defines **curvature‑neutral event activation** in the NDH manifold.  
It specifies when an NDH event may be triggered without violating:

- holonomy stability  
- curvature bounds  
- tensor safety  
- continuity constraints  

Crane is the **event operator** in the Triadic suite.

---

#### 2. Operator Definition

Let \( \mathcal{M} \) be the NDH manifold, with curvature tensor \( R \) and holonomy field \( \mathcal{H} \).

Define the Crane Operator \( \mathcal{C} \) as an activation functional:

\[
\mathcal{C}(x, E) =
\begin{cases}
1 & \text{if } \Phi_{\text{curv}}(x) \le \delta_{\text{curv}} \ \text{and} \ \Phi_{\text{hol}}(x) \le \delta_{\text{hol}} \\
0 & \text{otherwise}
\end{cases}
\]

Where:

- \( x \in \mathcal{M} \) = manifold point  
- \( E \) = candidate event  
- \( \Phi_{\text{curv}}(x) \) = local curvature magnitude at \( x \)  
- \( \Phi_{\text{hol}}(x) \) = local holonomy deviation at \( x \)  
- \( \delta_{\text{curv}}, \delta_{\text{hol}} > 0 \) = stability thresholds  

Crane **permits** event \( E \) at \( x \) only when curvature and holonomy are within safe bounds.

---

#### 3. Curvature‑Neutral Activation Condition

An event \( E \) is **Crane‑safe** at \( x \) if:

\[
\Phi_{\text{curv}}(x) \le \delta_{\text{curv}}
\quad \text{and} \quad
\Phi_{\text{hol}}(x) \le \delta_{\text{hol}}
\]

This ensures:

- no curvature spike  
- no holonomy twist beyond envelope  
- no tensor instability  
- no continuity break  

Crane enforces **curvature‑neutral activation**.

---

#### 4. Relationship to Scarf Operator

- **Crane:** decides *if* an event may occur (curvature‑neutral condition).  
- **Scarf:** decides *how* tensors are transported along paths (holonomy‑safe transport).

Crane operates at **event points**.  
Scarf operates along **paths**.

Both are required for:

- NDH Stability Manifold  
- safe NDH manifold evolution  
- NDH v1.1 publication envelope.

---

#### 5. Relationship to Manifold Operator

The Manifold Operator:

- defines \( \mathcal{M} \), \( R \), and \( \mathcal{H} \)  
- provides the geometric substrate for Crane and Scarf  
- encodes curvature and holonomy fields

Crane reads from the manifold geometry.  
Scarf transports within it.

---

#### 6. Provenance Footer

```markdown
---
Provenance: Crane-Operator-v1.1 defines the formal holonomy curvature event
operator for the NDH-Triadic-Core. It specifies curvature-neutral activation
conditions for NDH events and establishes the relationship between Crane,
Scarf, and the Manifold Operator within the NDH Stability Manifold. This
version replaces the earlier expressive Crane specification.

Maintainer: Borealis S. Hedling • Dublin, Ireland • 2026
---
```

---

