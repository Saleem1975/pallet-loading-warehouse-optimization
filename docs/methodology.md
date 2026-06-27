# Methodology

## Objective

The objective is to maximize the number of boxes per pallet while considering real-world constraints that affect pallet stability and box strength.

## Phase 1: Horizontal layer configurations

The first phase determines the number of boxes loaded onto possible horizontal layers. Three layer types are created based on which box dimension is perpendicular to the pallet base.

The layer-generation phase uses block techniques such as:

- One-block heuristic
- Two-block heuristic
- Three-block heuristic
- Five-block heuristic
- Hollow-block heuristic
- G5 heuristic

## Phase 2: Mathematical optimization model

The second phase determines the maximum number of boxes per pallet by considering:

- Maximum allowable pallet height
- Maximum allowable pallet weight
- Dynamic compression strength of the box

## Dynamic compression strength

Dynamic compression strength adjusts static compression strength using factors for:

- Storage time
- Relative humidity
- Interlock stacking
- Pallet surface
- Box orientation

## Performance measures

The paper evaluates the proposed method using:

- Pallet volume utilization
- Load height
- Pallet stability
