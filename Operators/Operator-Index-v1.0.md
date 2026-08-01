# 📘 Triadic‑Core Operator Index — NDH‑Triadic‑Core v1.0  
**Canonical Index of NDH Mathematical Operators**

---

## 1. Purpose

The **Triadic‑Core Operator Index** defines the canonical listing and structural relationships of all mathematical operators in the NDH‑Triadic‑Core. It provides:

- **operator identity**  
- **operator classification**  
- **operator dependencies**  
- **operator relationships**  
- **stability requirements**

This index is the formal entry point for NDH v1.1 mathematical publication.

---

## 2. Operator classes

### 2.1 Curvature operators

- **Crane‑Operator‑v1.1**  
  **Class:** Curvature event permission  
  **Role:** Determines point‑based event activation under curvature, holonomy, and stability constraints.

### 2.2 Holonomy operators

- **Scarf‑Operator‑v1.1**  
  **Class:** Holonomy‑safe parallel transport  
  **Role:** Governs tensor transport along paths under holonomy, stability, and drift bounds.

### 2.3 Celebration geometry operators

- **Confetti‑Operator‑v1.0**  
  **Class:** Celebration geometry  
  **Role:** Determines curvature‑neutral, holonomy‑safe celebration activation at stable points.

---

## 3. Substrate operators

### 3.1 Manifold‑Operator‑v1.1

**Class:** Geometric substrate  
**Role:** Provides:

- curvature tensor \( R(x) \)  
- holonomy field \( \mathcal{H}(x) \)  
- stability envelope \( S(x) \)  
- connection \( \nabla \)  
- operator‑safe region  
- drift structure

All Triadic‑Core operators depend on this substrate.

### 3.2 NDH‑Stability‑Manifold‑v1.0

**Class:** Stability geometry  
**Role:** Defines:

- stability basins  
- drift bounds  
- stability envelope  
- operator‑safe region  
- integration rules for Crane, Scarf, and Confetti

---

## 4. Unified operators

### 4.1 Crane‑Scarf‑Confetti‑Unified‑Operator‑v1.0

**Class:** Unified event–transport–celebration geometry  
**Role:**

- integrates Crane, Scarf, and Confetti  
- enforces shared curvature, holonomy, and stability constraints  
- defines unified activation conditions for event, path, and celebration  
- operates on the Manifold‑Operator‑v1.1 and NDH‑Stability‑Manifold‑v1.0 substrate

---

## 5. Operator dependency graph

Let:

- \( \mathcal{M}_{\text{op}} \) = Manifold‑Operator‑v1.1  
- \( \mathcal{E} \) = NDH‑Stability‑Manifold‑v1.0  
- \( \mathcal{C}_{\text{crane}} \) = Crane‑Operator‑v1.1  
- \( \mathcal{S}_{\text{scarf}} \) = Scarf‑Operator‑v1.1  
- \( \mathcal{C}_{\text{confetti}} \) = Confetti‑Operator‑v1.0  
- \( \mathcal{U}_{\text{triadic}} \) = Crane‑Scarf‑Confetti‑Unified‑Operator‑v1.0  

The dependency graph is:

\[
\mathcal{M}_{\text{op}} \rightarrow \mathcal{E} \rightarrow
\big( \mathcal{C}_{\text{crane}},\;
\mathcal{S}_{\text{scarf}},\;
\mathcal{C}_{\text{confetti}} \big)
\rightarrow
\mathcal{U}_{\text{triadic}}
\]

- **Manifold‑Operator‑v1.1** provides geometric quantities.  
- **NDH‑Stability‑Manifold‑v1.0** provides stability structure.  
- **Crane‑v1.1**, **Scarf‑v1.1**, **Confetti‑v1.0** operate on this substrate.  
- **Unified‑Operator‑v1.0** integrates all three.

This graph defines the **Triadic‑Core mathematical spine**.

---

## 6. Operator relationships

- **Manifold → Crane, Scarf, Confetti, Unified**  
  All operators read curvature, holonomy, stability, and connection.

- **Stability Manifold → Crane, Scarf, Confetti, Unified**  
  All operators must operate within stability basins and drift bounds.

- **Crane → Confetti, Unified**  
  Confetti and Unified activation require Crane permission at event points.

- **Scarf → Confetti, Unified**  
  Confetti and Unified activation must not violate Scarf path stability.

- **Confetti → Unified**  
  Unified operator uses Confetti’s celebration geometry under shared constraints.

---

## 7. Operator index table

| **Operator**                                      | **Version** | **Class**              | **Depends on**                                      | **Role**                                      |
|---------------------------------------------------|------------:|------------------------|-----------------------------------------------------|-----------------------------------------------|
| Crane‑Operator                                    | v1.1        | Curvature              | Manifold‑v1.1, Stability‑v1.0                       | Event permission at points                    |
| Scarf‑Operator                                    | v1.1        | Holonomy               | Manifold‑v1.1, Stability‑v1.0, Crane‑v1.1          | Holonomy‑safe parallel transport              |
| Confetti‑Operator                                 | v1.0        | Celebration geometry   | Manifold‑v1.1, Stability‑v1.0, Crane‑v1.1, Scarf‑v1.1 | Curvature‑neutral celebration activation      |
| Manifold‑Operator                                 | v1.1        | Geometric substrate    | —                                                   | Curvature, holonomy, stability, connection    |
| NDH‑Stability‑Manifold                            | v1.0        | Stability geometry     | Manifold‑v1.1                                      | Stability basins, drift bounds, safe region   |
| Crane‑Scarf‑Confetti‑Unified‑Operator             | v1.0        | Unified geometry       | Crane‑v1.1, Scarf‑v1.1, Confetti‑v1.0, Manifold‑v1.1, Stability‑v1.0 | Unified event–transport–celebration geometry |

---

## 8. Provenance footer

```markdown
---
Provenance: Operator-Index-v1.0 defines the canonical index of all mathematical
operators in the NDH-Triadic-Core. It specifies operator classes, dependencies,
relationships, and unified structures required for NDH v1.1 mathematical
publication.

Note: The NDH‑Triadic‑Core contains no internal citations. All interpretive,
literature, and provenance references are handled by the Reflection Layer in
Zen‑AI‑Design‑Architecture, which maintains the citation ontology and merged
citation blocks.

Maintainer: Borealis S. Hedling • Dublin, Ireland • 2026
---
```

---


