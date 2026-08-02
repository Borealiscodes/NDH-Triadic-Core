# 📘 **Crane Operator — NDH‑Triadic‑Core v1.1**  
**Holonomy Curvature Event Operator**

---

## **1. Purpose**

The **Crane Operator** defines **curvature‑neutral event activation** within the NDH manifold.  
It ensures that an event may be triggered only when:

- curvature is within safe bounds  
- holonomy deviation is below threshold  
- tensor stability is preserved  
- continuity constraints are satisfied  

Crane governs **event permission** at specific manifold points.

---

## **2. Operator Definition**

Let:

- \( \mathcal{M} \) be the NDH manifold  
- \( R(x) \) the curvature tensor  
- \( \mathcal{H}(x) \) the holonomy field  
- \( E \) a candidate event at point \( x \in \mathcal{M} \)  

Define the Crane Operator \( \mathcal{C} \):

\[
\mathcal{C}(x, E) =
\begin{cases}
1 & \text{if } \Phi_{\text{curv}}(x) \le \delta_{\text{curv}}
\ \text{and} \
\Phi_{\text{hol}}(x) \le \delta_{\text{hol}} \\
0 & \text{otherwise}
\end{cases}
\]

Where:

- \( \Phi_{\text{curv}}(x) = \|R(x)\| \)  
- \( \Phi_{\text{hol}}(x) = \|\mathcal{H}(x)\| \)  
- \( \delta_{\text{curv}}, \delta_{\text{hol}} > 0 \) are stability thresholds  

Crane returns **1** only when both curvature and holonomy are within safe limits.

---

## **3. Curvature‑Neutral Activation Condition**

An event \( E \) is **Crane‑safe** at point \( x \) if:

\[
\|R(x)\| \le \delta_{\text{curv}}
\quad \text{and} \quad
\|\mathcal{H}(x)\| \le \delta_{\text{hol}}
\]

This ensures:

- no curvature spike  
- no holonomy twist  
- no tensor instability  
- no continuity break  

Crane enforces **curvature‑neutral activation**.

---

## **4. Relationship to Scarf Operator**

Crane and Scarf form the **event‑transport pair**:

- **Crane** determines *whether* an event may occur at a point.  
- **Scarf** determines *how* tensors may be transported along a path.

Crane operates at **points**.  
Scarf operates along **curves**.

Both are required for NDH Stability Manifold coherence.

---

## **5. Relationship to Manifold Operator**

The Manifold Operator provides:

- curvature tensor \( R(x) \)  
- holonomy field \( \mathcal{H}(x) \)  
- geometric substrate \( \mathcal{M} \)  

Crane reads these quantities to determine event permission.

---

## **6. Version Notes (v1.1)**

This version introduces:

- explicit curvature and holonomy thresholds  
- clarified event‑permission semantics  
- alignment with NDH Stability Manifold v1.1  
- removal of expressive and Confetti‑state artifacts  
- compliance with Triadic‑Core Provenance Standard v1.0  

---

## **7. Provenance Footer**

```markdown
---
Provenance: Crane-Operator-v1.1 defines the curvature-neutral event operator for
the NDH-Triadic-Core. It specifies activation conditions based on curvature and
holonomy thresholds and establishes the relationship between Crane, Scarf, and
the Manifold Operator within the NDH Stability Manifold. This version replaces
all prior expressive or Confetti-state variants.

Maintainer: Borealis S. Hedling • Dublin, Ireland • 2026
---
```

---

