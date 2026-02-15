# Scaling Equality Model
## Micro–Macro Resolution Equivalence

---

## 1. Overview

本モデルは、観測スケール（Resolution Parameter λ）によって、
同一状態が異なる構造として現れることを定義する。

Micro と Macro は「別物」ではなく、
スケール変換による写像可能な構造である。

---

## 2. Mathematical Formulation

### State Space

S ∈ 𝒮  （宇宙の状態空間）

### Observation Operator

O_λ : 𝒮 → ℛ_λ

- λ_small  → Micro（高解像度・局所構造）
- λ_large  → Macro（低解像度・集合構造）

### Scale Relation

O_λ1(S) ≠ O_λ2(S)

ただし、スケール変換 T が存在する場合：

T(O_λ1(S)) ≈ O_λ2(S)

これを Structural Mapping と呼ぶ。

---

## 3. Conceptual Diagram

```mermaid
flowchart LR

    S[State Space S]

    M1[Micro Scale]
    M2[Macro Scale]

    S -->|lambda small| M1
    S -->|lambda large| M2

    M1 -. Structural Mapping .-> M2
```　　


