# Method Overview

## Goal

This project refines initialized hand-object interaction results through stage-wise optimization.

## Main Idea

The pipeline improves HOI quality progressively instead of solving all objectives at once.

## Key Design

- initialized HOI inputs
- stage-wise refinement
- hand-part-based optimization control
- object-aware geometric losses

## Outputs

Each run saves a structured set of outputs for analysis and comparison, including:

- a saved configuration snapshot (`config.yaml`)
- optimization logs
- loss curve visualization
- optimized result files (`.npz`)
- visualization outputs before optimization
- visualization outputs after optimization
