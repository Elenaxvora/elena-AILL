---
title: AILL Research
emoji: "🧠"
colorFrom: blue
colorTo: indigo
sdk: static
app_file: index.html
pinned: false
---

# AILL Research

Artificial Intelligence with Lifelong Learning.

## Private Project Note

The full AILL project remains private. This public README presents validated benchmark results and high-level research notes only. Private source code, training pipelines, checkpoints, datasets, and heavyweight runtime artifacts are not included.

## Monthly Research Updates

AILL is an active research project. Public updates will be added monthly when new validated results are available. Each update may include benchmark results, new visual charts, training status, architecture notes, and links to the public website.

- Live site: https://research.elenaxvora.com
- Latest update: April 2026 -- 1M SenzaAdam milestone
- Next planned update: 10M real-data run result, if validated

### April 2026 -- 1M SenzaAdam Milestone

- AILL baseline preserved
- GLIA isolated validation completed
- SenzaAdam 1M real-data brain passed
- recall_score = 0.9767
- anti_forgetting_score = 1.0000
- active_cells_avg = 1.00
- brain file = 487.44 MB
- no Adam
- no global backward

### Next Updates

- 10M real-data run result, if validated
- 100M real-data plan
- full dataset streaming plan
- read-only AILL <-> SenzaAdam integration test

## Featured Benchmark Screenshots

### SenzaAdam 1M Summary

<p align="center">
  <img src="./assets/benchmarks/senza_adam_1m_summary.png" alt="SenzaAdam 1M Summary" width="1100">
</p>

Validated 1M real-data milestone summary for the Adam-free persistent memory track.

### GLIA Core v2 Metrics

<p align="center">
  <img src="./assets/benchmarks/glia_core_v2_metrics.png" alt="GLIA Core v2 Metrics" width="1100">
</p>

Isolated GLIA non-Transformer memory validation metrics.

### AILL Biological Benchmark Summary

<p align="center">
  <img src="./assets/benchmarks/aill_biological_benchmark_summary.png" alt="AILL Biological Benchmark Summary" width="1100">
</p>

Public biological benchmark summary for the active AILL baseline.

### Retrieval Query Metrics

<p align="center">
  <img src="./assets/benchmarks/retrieval_query_metrics.png" alt="Retrieval Query Metrics" width="1100">
</p>

Validated retrieval benchmark metrics for controlled query behavior.

## At a Glance

| Area | Status | Scope |
| --- | --- | --- |
| AILL baseline | Active | Main baseline preserved |
| GLIA | Isolated research candidate | Non-Transformer memory, routing, and sequence handling experiment |
| SenzaAdam | Validated at 1M | Adam-free persistent brain experiment |
| AILL <-> SenzaAdam bridge | Isolated validation passed | Read-only bridge path, not full integration |

## What AILL Is

AILL stands for Artificial Intelligence with Lifelong Learning. It is a research language model built from scratch in PyTorch to study lifelong learning, inference-time plasticity, bounded active compute, and benchmark-driven validation. The main AILL baseline remains preserved and separate from the isolated GLIA and SenzaAdam research tracks.

## Why GLIA Exists

GLIA exists because the project is testing an isolated non-Transformer route for memory, routing, and sequence handling without replacing the active AILL baseline. The point of GLIA is to validate whether a different memory structure can improve retrieval and stability under controlled benchmark conditions. GLIA is a research candidate, not a public claim that it replaces AILL today.

### GLIA Results

| Metric | Value |
| --- | --- |
| GLIA Core v2 mini-corpus recall | 0.94 |
| Entity recall | 0.96 |
| Factual recall | 0.93 |
| Event recall | 0.86 |
| Timeline recall | 0.86 |
| Location recall | 1.00 |
| QA | 0.96 |
| Interference recall | 0.92 |
| Repetition | 0.04 |
| Hallucination | 0.12 |
| Wrong entity | 0.12 |
| Collapse | false |
| AILL+GLIA probe seeds 0/1/2 | passed |

The current takeaway is narrow and deliberate: GLIA passed isolated validation, but it is still a separate research candidate and not a replacement for the preserved AILL baseline.

## Why SenzaAdam Exists

SenzaAdam exists to test a different persistent-memory path with bounded active compute:

- no Adam optimizer state
- no global backward pass
- local updates
- active-cell-only compute
- persistent dormant cells stored in a unified brain file
- lower active VRAM pressure than dense full-model training loops

The research claim is narrow: a persistent memory benchmark can remain efficient when only a small active fraction of the stored brain participates at each step. This is not a claim of infinite memory, trillion-scale dense weights in 16GB VRAM, or production readiness.

## Correct External Claim

This public repository reports isolated research prototypes showing bounded active compute, a persistent unified brain state, local learning without Adam, and controlled retrieval behavior on a real 1M-pair SenzaAdam brain. The main AILL baseline remains preserved and separate.

## What Must Not Be Claimed

- AGI
- human brain simulation
- infinite memory
- production ready
- dense trillion-scale weights in 16GB VRAM
- GLIA replacing AILL today
- SenzaAdam replacing AILL today
- full AILL integration completed

## Public vs Private

| Area | Public? | Reason |
|---|---|---|
| README | Yes | Public summary |
| Benchmark PNGs | Yes | Public visual summaries |
| Live website | Yes | Public presentation |
| AILL core code | No | Private research implementation |
| Training scripts | No | Private engineering |
| Checkpoints / .pt files | No | Model artifacts |
| Datasets | No | Large/private training data |
| Raw logs | No | Internal/debug data |

## Benchmark Gallery

All figures below are public benchmark PNGs stored in `assets/benchmarks/`.

### Architecture Overview

<p align="center">
  <img src="./assets/benchmarks/architecture_overview.png" alt="Architecture Overview" width="1100">
</p>

Overview of the preserved AILL baseline with isolated GLIA and SenzaAdam benchmark tracks.

Source: generated from validated logs/results.

### Benchmark Atlas

<p align="center">
  <img src="./assets/benchmarks/benchmark_wall_summary.png" alt="Benchmark Atlas" width="1100">
</p>

Compact wall view of the public benchmark set used as a broad summary of validated outputs.

Source: generated from validated logs/results.

### AILL Biological Benchmark Summary

<p align="center">
  <img src="./assets/benchmarks/aill_biological_benchmark_summary.png" alt="AILL Biological Benchmark Summary" width="1100">
</p>

Public biological benchmark summary for the active AILL PyTorch baseline.

Source: generated from validated logs/results.

### GLIA Core v2 Metrics

<p align="center">
  <img src="./assets/benchmarks/glia_core_v2_metrics.png" alt="GLIA Core v2 Metrics" width="1100">
</p>

Isolated GLIA validation metrics covering the non-Transformer memory and routing track.

Source: generated from validated logs/results.

### AILL + GLIA 3-Seed Probe

<p align="center">
  <img src="./assets/benchmarks/aill_glia_probe_3seed.png" alt="AILL + GLIA 3-Seed Probe" width="1100">
</p>

Three-seed stability view for the isolated AILL + GLIA probe.

Source: generated from validated logs/results.

### SenzaAdam Core Validation

<p align="center">
  <img src="./assets/benchmarks/senza_adam_core_validation.png" alt="SenzaAdam Core Validation" width="1100">
</p>

Core validation summary for the Adam-free persistent memory research track.

Source: generated from validated logs/results.

### SenzaAdam 1M Summary

<p align="center">
  <img src="./assets/benchmarks/senza_adam_1m_summary.png" alt="SenzaAdam 1M Summary" width="1100">
</p>

SenzaAdam 1M real-data milestone: 1,000,000 concept/fact pairs, recall 0.9767, anti-forgetting 1.0000, active_cells_avg 1.00.

Source: generated from validated logs/results.

### Brain File Growth 1M

<p align="center">
  <img src="./assets/benchmarks/brain_file_growth_1m.png" alt="Brain File Growth 1M" width="1100">
</p>

Brain file growth across the validated 1M SenzaAdam run.

Source: generated from validated logs/results.

### Total Cells Growth 1M

<p align="center">
  <img src="./assets/benchmarks/total_cells_growth_1m.png" alt="Total Cells Growth 1M" width="1100">
</p>

Total cell growth over the 1M persistent memory benchmark.

Source: generated from validated logs/results.

### Created vs Reused Cells 1M

<p align="center">
  <img src="./assets/benchmarks/created_vs_reused_cells_1m.png" alt="Created vs Reused Cells 1M" width="1100">
</p>

Comparison of created and reused cells during the 1M benchmark.

Source: generated from validated logs/results.

### Recall Over Time 1M

<p align="center">
  <img src="./assets/benchmarks/recall_over_time_1m.png" alt="Recall Over Time 1M" width="1100">
</p>

Recall progression during the validated 1M SenzaAdam run.

Source: generated from validated logs/results.

### Anti-Forgetting Over Time 1M

<p align="center">
  <img src="./assets/benchmarks/anti_forgetting_over_time_1m.png" alt="Anti-Forgetting Over Time 1M" width="1100">
</p>

Anti-forgetting score progression during the 1M benchmark.

Source: generated from validated logs/results.

### Active VRAM Over Time 1M

<p align="center">
  <img src="./assets/benchmarks/active_vram_over_time_1m.png" alt="Active VRAM Over Time 1M" width="1100">
</p>

Active VRAM estimate during the persistent active-cell memory run.

Source: generated from validated logs/results.

### Throughput Over Time 1M

<p align="center">
  <img src="./assets/benchmarks/throughput_over_time_1m.png" alt="Throughput Over Time 1M" width="1100">
</p>

Observed throughput during the validated 1M benchmark.

Source: generated from validated logs/results.

### Active Cells Average Over Time 1M

<p align="center">
  <img src="./assets/benchmarks/active_cells_avg_over_time_1m.png" alt="Active Cells Average Over Time 1M" width="1100">
</p>

Average active cells across the 1M active-cell-only compute benchmark.

Source: generated from validated logs/results.

### Cell Reuse Ratio 1M

<p align="center">
  <img src="./assets/benchmarks/cell_reuse_ratio_1m.png" alt="Cell Reuse Ratio 1M" width="1100">
</p>

Cell reuse ratio during the validated persistent memory run.

Source: generated from validated logs/results.

### Storage Scaling Projection

<p align="center">
  <img src="./assets/benchmarks/storage_scaling_projection.png" alt="Storage Scaling Projection" width="1100">
</p>

Projection chart for future persistent memory storage scaling steps.

Source: generated from validated logs/results.

### Retrieval Query Metrics

<p align="center">
  <img src="./assets/benchmarks/retrieval_query_metrics.png" alt="Retrieval Query Metrics" width="1100">
</p>

Validated retrieval benchmark metrics for known and controlled query behavior.

Source: generated from validated logs/results.

### Natural QA Metrics

<p align="center">
  <img src="./assets/benchmarks/natural_qa_metrics.png" alt="Natural QA Metrics" width="1100">
</p>

Natural QA benchmark metrics from the read-only evaluation flow.

Source: generated from validated logs/results.

### Known Query Examples

<p align="center">
  <img src="./assets/benchmarks/known_query_examples.png" alt="Known Query Examples" width="900">
</p>

Known episodic retrieval examples from the validated benchmark set.

Source: generated from validated logs/results.

### Unknown Query Fast Rejection Fix

<p align="center">
  <img src="./assets/benchmarks/unknown_query_fix.png" alt="Unknown Query Fast Rejection Fix" width="1100">
</p>

Corrected fast rejection behavior for unknown queries in read-only benchmark mode.

Source: generated from validated logs/results.

### Active Cell Snapshot A

<p align="center">
  <img src="./assets/benchmarks/active_cell.png" alt="Active Cell Snapshot A" width="900">
</p>

Cell-level visualization from the public active-memory benchmark export.

Source: generated from validated logs/results.

### Active Cell Snapshot B

<p align="center">
  <img src="./assets/benchmarks/active_cell-1.png" alt="Active Cell Snapshot B" width="900">
</p>

Additional cell-level visualization from the validated export set.

Source: generated from validated logs/results.

### Active Cell Snapshot C

<p align="center">
  <img src="./assets/benchmarks/active_cell-2.png" alt="Active Cell Snapshot C" width="900">
</p>

Additional active-cell visualization from the public benchmark export.

Source: generated from validated logs/results.

## Live Site

https://research.elenaxvora.com

## Update Policy

Public README and website will be updated when validated monthly results are available.