# Chapter 6 - Module 1: Climatological and Physiographic Datasets

## Learning Objectives

- Acquire required datasets.
- Understand dataset roles in DRYP setup.
- Prepare datasets for downstream modules.

## Background

Module 1 establishes all forcing and static inputs needed by subsequent workflows.

## Required Software

| Component | Version | Notes |
|---|---|---|
| Python | 3.11 | |
| CUWALID | 1.x | |

## Required Data

| Dataset | Resolution | Units | Purpose | Source |
|---|---|---|---|---|
| DEM | TBD | m | Terrain inputs | TBD |
| Climate inputs | TBD | variable | Forcing | TBD |

## Repository Files

| File or Folder | Role in Workflow |
|---|---|
| module 1 notebooks | Data acquisition and preprocessing |

## Scientific Concepts

Explain why each dataset matters for process representation.

## Workflow

1. Download datasets.
2. Harmonize projection and extent.
3. Validate data completeness.

## Step-by-step Guide

1. Run acquisition notebook sections.
2. Run clipping and reprojection steps.
3. Verify outputs.

## Expected Outputs

- Prepared dataset bundle for Module 2 and Module 3.

## Validation Checklist

- [ ] Extent and CRS are consistent.
- [ ] Missing values are identified and handled.

## Troubleshooting

| Symptom | Possible Cause | Recommended Fix |
|---|---|---|
| CRS mismatch | Mixed source projections | Reproject all layers to target CRS |

## Summary

Module 1 prepares the data foundation for all downstream modelling tasks.

## Further Reading

- Dataset source documentation.
