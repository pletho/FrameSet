# Strinum Ecosystem – Relationship Structure

## 1. Hierarchical View

SUL
  ↓
Strinum
  ↓
FrameSet
  ↓
Runtime
  ↑
S++MODE (Meta Control)

---

## 2. Dependency Model

SUL is independent.

Strinum depends on SUL.

FrameSet depends on Strinum output.

Runtime depends on FrameSet.

S++MODE controls all layers.

---

## 3. Open vs Closed Boundary

Open:
- Philosophy
- Specifications
- FrameSet Core Interface

Closed:
- Deterministic Execution Engine
- Memory Persistence System
- Advanced AI Runtime Layer
