# GML MACAD 26 — Mahmoud Mohamed

**Graph Machine Learning** coursework for the MACAD programme — 3rd Semester.

## Overview

This repository contains Jupyter notebooks, assets, and assignments exploring Graph ML concepts applied to spatial and architectural data. Topics covered include graph construction, topological analysis, spatial intelligence, IFC/BIM semantic relationships, and graph-based machine learning (classification, regression, node classification).

## Repository Structure

```
assignments/
  assignment-01/        # Tower residential floor plan — initial analysis
  assignment-02/        # Tower residential floor plan — spatial intelligence & graph analysis
    deliverables/       # Exported images/outputs

Graph ML -- NOTEBOOKS/  # Course session notebooks (S02–S07)
  S02-xx  Primal/Dual, Metric/Topological, Adjacency/Access, Geometric & Spatial Representations, OBJ import
  S03-xx  Spatial Intelligence (grid overlays, slicing, centrality)
  S04-xx  IFC Semantic & Spatial Relationships, Models to Graphs
  S05-xx  Dataset & Feature Engineering
  S06-xx  GML Classification, Regression, Node Classification
  S07-xx  Neo4j, Ollama, GraphRAG

Asset/                  # OBJ/MTL geometry files used in notebooks
```

## Assignments

### Assignment 01 — Tower Residential Floor Plan Analysis
Baseline graph analysis of a residential tower floor plan. Constructs cell complexes from OBJ geometry, builds adjacency and aperture graphs, and visualises the topology.

### Assignment 02 — Spatial Intelligence
Extends assignment-01 with:
- De-triangulation of OBJ/BREP geometry using Shapely `unary_union`
- Grid overlay aligned to the largest floor face
- Graph centrality and spatial intelligence metrics
- Minimum Spanning Tree and complete graph construction

#### Deliverables

![01](assignments/assignment-02/deliverables/01.png)
![02](assignments/assignment-02/deliverables/02.png)
![03](assignments/assignment-02/deliverables/03.png)
![04](assignments/assignment-02/deliverables/04.png)
![05](assignments/assignment-02/deliverables/05.png)

## Environment

| Tool | Version |
|------|---------|
| Python | 3.10+ |
| topologicpy | ≥ 0.9.18 |
| Shapely | ≥ 2.0 |
| Jupyter / VS Code | latest |

### Setup

```powershell
# Activate virtual environment
Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned
& d:\MACAD\3rd-SM\GML\python\GML.26\.gmlenv\Scripts\Activate.ps1
```

## Author

**Mahmoud Mohamed** — MACAD, IAAC Barcelona
