# Chapter 9 - Module 4: Calibration

## Learning Objectives

- Configure calibration experiments.
- Select and interpret objective metrics.
- Diagnose model behavior during calibration.

## Background

Calibration aligns model outputs with observed system behavior.

## Required Software

| Component | Version | Notes |
|---|---|---|
| Python | 3.11 | |
| CUWALID | 1.x | |
| DRYP | 2.x | |

## Required Data

| Dataset | Resolution | Units | Purpose | Source |
|---|---|---|---|---|
| Module 2 observations | variable | variable | Target series | Chapter 7 |
| Module 3 inputs | variable | variable | Model runs | Chapter 8 |

## Repository Files

| File or Folder | Role in Workflow |
|---|---|
| module 4 notebooks | Calibration and evaluation |

## Scientific Concepts

Explain objective functions, identifiability, and equifinality.

## Workflow

1. Define parameter bounds.
2. Run calibration trials.
3. Analyze performance.

## Step-by-step Guide

1. Configure experiment settings.
2. Execute calibration routines.
3. Compare trial metrics.

## Expected Outputs

- Calibrated parameter sets and performance summaries.

## Validation Checklist

- [ ] Objective metrics improve from baseline.
- [ ] Parameter values remain physically plausible.

## Troubleshooting

| Symptom | Possible Cause | Recommended Fix |
|---|---|---|
| Poor convergence | Overly broad bounds or noisy targets | Refine parameter space |

## Summary

Module 4 tunes model behavior to observed conditions.

## Further Reading

- Calibration literature and project-specific methods.
