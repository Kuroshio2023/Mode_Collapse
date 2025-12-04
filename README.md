# Mode Collapse as an Optimal Transport Problem

This repository contains a theoretical framework that reframes **variational inference (VI)** as an **optimal transport (OT)** problem and uses this perspective to define, analyze, and characterize **mode collapse**. Instead of viewing collapse as a purely variational or parametric failure, we interpret it as the degeneracy of transport plans between the variational distribution and the target distribution.

## Overview
- Reformulates VI as minimizing a transport cost plus regularization over joint couplings between the variational distribution and the target.
- Introduces a **mode-covering transport plan**, formalizing when a variational distribution successfully captures each mode of the target.
- Defines **mode collapse** as the absence of any mode-covering plan between p and q.
- Connects collapse to geometric, mass-allocation, and routing failures within transport plans.

## Key Ideas
- **VI as OT:** Standard VI emerges as a special case where the transport cost is the negative log-density and the regularization is KL divergence.
- **Modes:** Defined using topological neighborhoods, ε-modes, or high-probability connected components.
- **Mode-Covering Plans:** Ensure each mode receives adequate mass, remains geometrically close, and is properly routed.
- **Mode Collapse:** Occurs when these conditions cannot be satisfied under any admissible transport plan from the variational family.

## Theoretical Directions (Ongoing)
- Characterizing when mode-covering plans exist and when collapse is inevitable.
- Identifying **critical mode separation** thresholds beyond which collapse cannot be avoided.
- Linking existence of a mode-covering plan to **bounded KL divergence**.
- Designing algorithms that explicitly search for or approximate mode-covering plans.

## Contents
- Formal definitions of modes  
- Definition of mode-covering transport plans  
- Full mathematical definition of mode collapse  
- Conjectures and theoretical goals  
- Algorithmic implications  

## Citation
```
@misc{modecollapse2025,
  title={Mode Collapse as an Optimal Transport Problem in Variational Inference},
  author={Akanksha Das},
  year={2025}
}
```
