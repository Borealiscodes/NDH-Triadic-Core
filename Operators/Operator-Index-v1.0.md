# 📘 **Triadic‑Core Operator Index — NDH‑Triadic‑Core v1.1**  
**Canonical Index of NDH Mathematical Operators (Clean Version)**

---

## **1. Purpose**

The **Triadic‑Core Operator Index v1.1** defines the canonical listing, classification, and dependency structure of all mathematical operators in the NDH‑Triadic‑Core.  
It provides:

- operator identity  
- operator class  
- operator dependencies  
- operator relationships  
- stability requirements  
- canonical ordering  

This index replaces the corrupted v1.0 version and aligns fully with the v1.1 geometric baselines.

---

## **2. Operator Classes (v1.1)**

### **2.1 Curvature Operators**

- **Crane‑Operator‑v1.1**  
  **Class:** Curvature event permission  
  **Role:** Determines point‑based event activation under curvature, holonomy, and stability constraints.

### **2.2 Holonomy Operators**

- **Scarf‑Operator‑v1.1**  
  **Class:** Holonomy‑safe parallel transport  
  **Role:** Governs tensor transport along paths under holonomy, stability, and drift bounds.

### **2.3 Substrate Operators**

- **Manifold‑Operator‑v1.1**  
  **Class:** Geometric substrate  
  **Role:** Provides curvature tensor \( R(x) \), holonomy field \( \mathcal{H}(x) \), stability function \( S(x) \), connection \( \nabla \), and drift structure.

- **NDH‑Stability‑Manifold‑v1.1**  
  **Class:** Stability geometry  
  **Role:** Defines stability envelope, operator‑safe region, stability basins, drift bounds, and Crane/Scarf integration rules.

### **2.4 Reference Operators**

- **NDH‑Reference‑Frame‑v1.1**  
  **Class:** Geometric anchor  
  **Role:** Defines the reference origin, curvature baseline, holonomy baseline, stability seed, drift baseline, and canonical operator ordering.

---

## **3. Removed Operators (v1.1)**

The following operators are **not included** in v1.1:

- Confetti‑Operator‑v1.0  
- Crane‑Scarf‑Confetti Unified Operator‑v1.0  
- NDH‑Stability‑Manifold‑v1.0  
- Operator‑Index‑v1.0  

These artifacts were removed due to Confetti‑state contamination and unified‑fusion corruption.

---

## **4. Canonical Operator Ordering (v1.1)**

The NDH‑Reference‑Frame‑v1.1 defines the canonical operator order:

1. **Manifold‑Operator‑v1.1**  
2. **NDH‑Reference‑Frame‑v1.1**  
3. **Crane‑Operator‑v1.1**  
4. **Scarf‑Operator‑v1.1**  
5. **NDH‑Stability‑Manifold‑v1.1**  
6. **Operator‑Index‑v1.1** (this document)

This ordering ensures geometric coherence and stability.

---

## **5. Operator Dependency Graph (v1.1)**

Let:

- \( \mathcal{M}_{\text{op}} \) = Manifold‑Operator‑v1.1  
- \( \mathcal{R} \) = NDH‑Reference‑Frame‑v1.1  
- \( \mathcal{E} \) = NDH‑Stability‑Manifold‑v1.1  
- \( \mathcal{C}_{\text{crane}} \) = Crane‑Operator‑v1.1  
- \( \mathcal{S}_{\text{scarf}} \) = Scarf‑Operator‑v1.1  

The dependency graph is:

\[
\mathcal{M}_{\text{op}} \rightarrow \mathcal{R} \rightarrow \mathcal{E} \rightarrow
\big( \mathcal{C}_{\text{crane}},\; \mathcal{S}_{\text{scarf}} \big)
\]

This graph defines the **Triadic‑Core mathematical spine** for v1.1.

---

## **6. Operator Relationships (v1.1)**

- **Manifold → Reference Frame**  
  Provides curvature, holonomy, stability, and connection baselines.

- **Reference Frame → Stability Manifold**  
  Provides origin, stability seed, drift baseline, and ordering rules.

- **Stability Manifold → Crane, Scarf**  
  Provides stability envelope, basins, drift bounds, and safe region.

- **Crane → Scarf**  
  Crane event permission defines valid starting points for Scarf transport.

- **Scarf → Crane**  
  Scarf path stability defines valid transport paths for Crane‑dependent events.

All relationships are geometric and stability‑driven.

---

## **7. Operator Index Table (v1.1)**

| **Operator**                     | **Version** | **Class**            | **Depends on**                                | **Role**                                      |
|----------------------------------|------------:|----------------------|-----------------------------------------------|-----------------------------------------------|
| Manifold‑Operator                | v1.1        | Geometric substrate  | —                                             | Curvature, holonomy, stability, connection    |
| NDH‑Reference‑Frame              | v1.1        | Geometric anchor     | Manifold‑v1.1                                 | Origin, baselines, ordering                   |
| Crane‑Operator                   | v1.1        | Curvature            | Manifold‑v1.1, Stability‑v1.1, Reference‑v1.1 | Event permission                              |
| Scarf‑Operator                   | v1.1        | Holonomy             | Manifold‑v1.1, Stability‑v1.1, Reference‑v1.1 | Parallel transport                            |
| NDH‑Stability‑Manifold           | v1.1        | Stability geometry   | Manifold‑v1.1, Reference‑v1.1                 | Stability envelope, basins, drift             |
| Operator‑Index                   | v1.1        | Structural registry  | All above                                     | Canonical operator index                      |

---

## **8. Provenance Footer (v1.1)**

```markdown
---
Provenance: Operator-Index-v1.1 defines the canonical operator registry for
NDH-Triadic-Core v1.1. It specifies operator classes, dependencies, relationships,
and ordering rules built on NDH-Reference-Frame-v1.1 and NDH-Stability-Manifold-
v1.1. This version replaces the corrupted Confetti-state Operator-Index-v1.0 and
restores mathematical purity to the Triadic-Core.

Maintainer: Borealis S. Hedling • Dublin, Ireland • 2026
---
```

---

