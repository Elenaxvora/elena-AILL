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

The full AILL project remains private. This public README publishes validated benchmark results, architecture history, and real PNG artifacts only. Private source code, training pipelines, checkpoints, datasets, and heavyweight runtime artifacts are not included.

The public package does not advertise a public chat product, upload access, or SaaS access. The interactive demo remains private until the Stage 7 speaking writer is ready.

## Current Public Status

- Elena AILL remains the umbrella research project.
- Earlier dense AILL history is preserved as research lineage.
- GLIA remains a documented research track, not the current public runtime.
- SenzaAdam Brain + SPEAK-NEW is the active validated public path.
- verified_10m_result = PASS.
- 100M stress run was deferred, not failed.
- Stage 2 through Stage 6 public benchmark evidence is PASS.
- Public evidence uses real PNG charts only.

## Monthly Research Updates

- Live site: https://research.elenaxvora.com
- Latest update: May 2026 -- verified 10M SenzaAdam milestone
- Current public gate: Stage 7 speaking writer for a future demo release

### April 2026 -- historical 1M SenzaAdam milestone

- AILL baseline preserved
- GLIA isolated validation completed
- SenzaAdam 1M real-data brain passed
- recall_score = 0.9767
- anti_forgetting_score = 1.0000
- active_cells_avg = 1.00
- brain_file_size_mb = 487.44
- no Adam
- no global backward

### May 2026 -- verified 10M internal benchmark result

- verified_10m_result = PASS
- learned_facts = 10,833,323
- created_cells = 394,856
- reused_cells = 10,438,467
- recall_score = 0.9883
- anti_forgetting_score = 1.0000
- active_cells_avg = 1.0000
- brain_file_size_mb = 2358.2526
- no Adam optimizer state
- no global backward pass in the active memory path

### Why 100M was deferred

The 100M stress run was deferred, not failed. The 10M run had already produced strong enough evidence to shift engineering effort toward system integration, public benchmark packaging, SenzaAdam Brain + SPEAK-NEW runtime validation, and Stage 7 -- the speaking writer designed to make Elena AILL produce more natural, controlled, memory-grounded responses.

## Research Lineage And Active Runtime

| Area | Status | Scope |
| --- | --- | --- |
| AILL baseline | Preserved | Main dense research history remains documented |
| GLIA | Preserved research track | Memory, routing, QA-from-memory, interference resistance |
| SenzaAdam Brain | Active validated module | Persistent memory without Adam and without global backward |
| SPEAK-NEW | Active validated runtime path | Stage 2 to Stage 6 validated benchmark path |
| Stage 7 speaking writer | Private next gate | Natural, controlled, memory-grounded responses before public demo |

## What AILL Is

AILL stands for Artificial Intelligence with Lifelong Learning. It is a research language model built from scratch in PyTorch to study lifelong learning, inference-time plasticity, bounded active compute, and benchmark-driven validation.

The public storyline is narrow and deliberate:

- Elena AILL is the umbrella project
- GLIA remains important research history
- SenzaAdam Brain is the active persistent-memory module
- SPEAK-NEW is the active validated runtime path
- the public package publishes evidence, not product claims

## Why GLIA Still Appears Publicly

GLIA is a preserved Elena AILL research track for memory and routing validation. It explored entity recall, memory retrieval, routing, QA from memory, and interference-resistant retrieval. GLIA is not the current public runtime, but it remains part of the public narrative because it validated ideas that informed the current SenzaAdam Brain + SPEAK-NEW direction.

### GLIA results

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
| AILL + GLIA probe seeds 0/1/2 | passed |

## Why SenzaAdam Brain Exists

SenzaAdam Brain exists to test a persistent-memory path with bounded active compute:

- no Adam optimizer state
- no global backward pass
- local updates
- active-cell-only compute
- persistent dormant cells stored in a unified brain artifact
- lower active VRAM pressure than dense full-model training loops

This is not a claim of AGI, infinite memory, trillion-scale dense weights in 16GB VRAM, or production readiness.

## Stage 2 To Stage 6 Benchmark Summary

| Stage | Status | Public evidence |
| --- | --- | --- |
| Stage 2 | PASS | Core deterministic and decoder runs both pass; validated hard set keeps deterministic slightly ahead at 0.953271 versus 0.943925 |
| Stage 3 | PASS | Deterministic pass_rate = 0.97493, memory_retrieval_success = 1.0, unknown_fallback_success = 1.0 |
| Stage 4 | PASS | Deterministic and decoder both reach pass_rate = 1.0 |
| Stage 5 | PASS | Runtime evidence shows SenzaAdam Brain + SPEAK-NEW on RTX 4060 Ti with writer_mode deterministic and brain_file_size_mb = 0.173 |
| Stage 6 | PASS | facts = 433, local sources = 9, mandatory selfdoc questions = 10/10, pass_rate = 0.97561, memory_retrieval_success = 0.972222, source_trace_success = 1.0, cortex_used_ratio = 0.878049 |

## Current Public Figures

These are the key PNG figures shown directly on the public website.

### Architecture Overview

<p align="center">
  <img src="./assets/benchmarks/architecture_overview.png" alt="Architecture Overview" width="1100">
</p>

Overview of the preserved AILL baseline, GLIA research lineage, and the active SenzaAdam Brain + SPEAK-NEW path.

### GLIA Core v2 Metrics

<p align="center">
  <img src="./assets/benchmarks/glia_core_v2_metrics.png" alt="GLIA Core v2 Metrics" width="1100">
</p>

Isolated GLIA validation metrics for the preserved memory and routing track.

### Stage 2-4 Pass Rate Comparison

<p align="center">
  <img src="./assets/benchmarks/stage5_dashboard_stage2_stage3_stage4_pass_rate.png" alt="Stage 2-4 Pass Rate Comparison" width="1100">
</p>

Public comparison figure used on the website to show the validated Stage 2, Stage 3, and Stage 4 benchmark progression.

### Stage 2-4 Gallery Sheet

<p align="center">
  <img src="./assets/benchmarks/gallery_stage2_stage3_stage4.png" alt="Stage 2-4 Gallery" width="1100">
</p>

Gallery sheet assembled from the real Stage 2 through Stage 4 benchmark PNGs.

### Stage 5 Runtime Gallery

<p align="center">
  <img src="./assets/benchmarks/gallery_stage5_private_runtime.png" alt="Stage 5 Runtime Gallery" width="1100">
</p>

Runtime evidence sheet for the active SenzaAdam Brain + SPEAK-NEW path.

### Stage 6 Self-Documentation Scorecard

<p align="center">
  <img src="./assets/benchmarks/stage6_stage6_scorecard.png" alt="Stage 6 Scorecard" width="1100">
</p>

Scorecard showing Stage 6 pass rate, memory retrieval success, and source trace success.

### Stage 6 Facts By Source

<p align="center">
  <img src="./assets/benchmarks/stage6_ingestion_facts_by_source.png" alt="Stage 6 Facts By Source" width="1100">
</p>

Public chart showing local source distribution for the Stage 6 ingestion benchmark.

### Stage 6 Gallery Sheet

<p align="center">
  <img src="./assets/benchmarks/gallery_stage6_selfdoc_ingestion.png" alt="Stage 6 Gallery" width="1100">
</p>

Gallery sheet assembled from the Stage 6 self-documentation and ingestion PNGs.

## Public PNG Package

The public website now exposes a benchmark inventory of 125 real PNG artifacts:

- 24 preserved historical visuals in `assets/benchmarks/`
- 48 branded benchmark charts in `assets/public-package/charts_branded/`
- 48 original benchmark charts in `assets/public-package/charts_original/`
- 5 gallery sheets in `assets/public-package/charts_gallery/`

No fake charts, no invented metrics, and no AI-generated infographic evidence are included.

### Preserved historical visuals

- `assets/benchmarks/architecture_overview.png`
- `assets/benchmarks/benchmark_wall_summary.png`
- `assets/benchmarks/aill_biological_benchmark_summary.png`
- `assets/benchmarks/glia_core_v2_metrics.png`
- `assets/benchmarks/aill_glia_probe_3seed.png`
- `assets/benchmarks/senza_adam_core_validation.png`
- `assets/benchmarks/senza_adam_1m_summary.png`
- `assets/benchmarks/brain_file_growth_1m.png`
- `assets/benchmarks/total_cells_growth_1m.png`
- `assets/benchmarks/created_vs_reused_cells_1m.png`
- `assets/benchmarks/recall_over_time_1m.png`
- `assets/benchmarks/anti_forgetting_over_time_1m.png`
- `assets/benchmarks/active_vram_over_time_1m.png`
- `assets/benchmarks/throughput_over_time_1m.png`
- `assets/benchmarks/active_cells_avg_over_time_1m.png`
- `assets/benchmarks/cell_reuse_ratio_1m.png`
- `assets/benchmarks/storage_scaling_projection.png`
- `assets/benchmarks/retrieval_query_metrics.png`
- `assets/benchmarks/natural_qa_metrics.png`
- `assets/benchmarks/known_query_examples.png`
- `assets/benchmarks/unknown_query_fix.png`
- `assets/benchmarks/active_cell.png`
- `assets/benchmarks/active_cell-1.png`
- `assets/benchmarks/active_cell-2.png`

### Branded benchmark charts

Stage 2 Core:

- `assets/public-package/charts_branded/stage2_core_category_pass_rate_comparison.png`
- `assets/public-package/charts_branded/stage2_core_deterministic_vs_decoder_pass_rate.png`
- `assets/public-package/charts_branded/stage2_core_fallback_rate_comparison.png`
- `assets/public-package/charts_branded/stage2_core_memory_retrieval_success_comparison.png`
- `assets/public-package/charts_branded/stage2_core_scorecard_decoder.png`
- `assets/public-package/charts_branded/stage2_core_scorecard_deterministic.png`

Stage 2 Hard:

- `assets/public-package/charts_branded/stage2_hard_category_pass_rate_comparison.png`
- `assets/public-package/charts_branded/stage2_hard_deterministic_vs_decoder_pass_rate.png`
- `assets/public-package/charts_branded/stage2_hard_fallback_rate_comparison.png`
- `assets/public-package/charts_branded/stage2_hard_memory_retrieval_success_comparison.png`
- `assets/public-package/charts_branded/stage2_hard_scorecard_decoder.png`
- `assets/public-package/charts_branded/stage2_hard_scorecard_deterministic.png`

Stage 3:

- `assets/public-package/charts_branded/stage3_context_qa_success.png`
- `assets/public-package/charts_branded/stage3_fallback_rate.png`
- `assets/public-package/charts_branded/stage3_memory_retrieval_success.png`
- `assets/public-package/charts_branded/stage3_pass_rate_by_category.png`
- `assets/public-package/charts_branded/stage3_pipeline_scorecard.png`
- `assets/public-package/charts_branded/stage3_stage2_vs_stage3_comparison.png`
- `assets/public-package/charts_branded/stage3_unknown_fallback_success.png`

Stage 4:

- `assets/public-package/charts_branded/stage4_context_qa_success.png`
- `assets/public-package/charts_branded/stage4_distractor_rejection_success.png`
- `assets/public-package/charts_branded/stage4_fallback_rate.png`
- `assets/public-package/charts_branded/stage4_memory_retrieval_success.png`
- `assets/public-package/charts_branded/stage4_misleading_context_success.png`
- `assets/public-package/charts_branded/stage4_multi_fact_success.png`
- `assets/public-package/charts_branded/stage4_pass_rate_by_category.png`
- `assets/public-package/charts_branded/stage4_pipeline_scorecard.png`
- `assets/public-package/charts_branded/stage4_stage3_vs_stage4_comparison.png`
- `assets/public-package/charts_branded/stage4_unknown_fallback_success.png`

Stage 5 Runtime:

- `assets/public-package/charts_branded/stage5_dashboard_context_qa_success.png`
- `assets/public-package/charts_branded/stage5_dashboard_distractor_rejection_success.png`
- `assets/public-package/charts_branded/stage5_dashboard_fallback_success.png`
- `assets/public-package/charts_branded/stage5_dashboard_memory_retrieval_success.png`
- `assets/public-package/charts_branded/stage5_dashboard_misleading_context_success.png`
- `assets/public-package/charts_branded/stage5_dashboard_multi_fact_success.png`
- `assets/public-package/charts_branded/stage5_dashboard_public_demo_readiness_scorecard.png`
- `assets/public-package/charts_branded/stage5_dashboard_runtime_memory_scorecard.png`
- `assets/public-package/charts_branded/stage5_dashboard_runtime_vram_usage.png`
- `assets/public-package/charts_branded/stage5_dashboard_stage2_stage3_stage4_pass_rate.png`
- `assets/public-package/charts_branded/stage5_dashboard_stage4_metric_scorecard.png`
- `assets/public-package/charts_branded/stage5_dashboard_writer_mode_comparison.png`

Stage 6 Self-Documentation:

- `assets/public-package/charts_branded/stage6_cortex_vs_context_usage.png`
- `assets/public-package/charts_branded/stage6_facts_by_category.png`
- `assets/public-package/charts_branded/stage6_ingestion_facts_by_source.png`
- `assets/public-package/charts_branded/stage6_memory_retrieval_success.png`
- `assets/public-package/charts_branded/stage6_source_trace_success.png`
- `assets/public-package/charts_branded/stage6_stage4_vs_stage6_usage_ratio.png`
- `assets/public-package/charts_branded/stage6_stage6_scorecard.png`

### Original benchmark charts

The original chart pack mirrors the same 48 filenames listed above under `assets/public-package/charts_original/`.

### Gallery sheets

- `assets/public-package/charts_gallery/gallery_all_benchmarks.png`
- `assets/public-package/charts_gallery/gallery_public_website_pack.png`
- `assets/public-package/charts_gallery/gallery_stage2_stage3_stage4.png`
- `assets/public-package/charts_gallery/gallery_stage5_private_runtime.png`
- `assets/public-package/charts_gallery/gallery_stage6_selfdoc_ingestion.png`

## Public vs Private

| Area | Public? | Reason |
| --- | --- | --- |
| README | Yes | Public summary and benchmark narrative |
| Benchmark PNGs | Yes | Public visual summaries and galleries |
| Live website | Yes | Public presentation surface |
| Interactive demo | No | Private until Stage 7 speaking writer |
| AILL core code | No | Private research implementation |
| Training scripts | No | Private engineering |
| Checkpoints / .pt files | No | Model artifacts |
| Datasets | No | Large or private training data |
| Raw logs | No | Internal and debug data |

## What Must Not Be Claimed

- AGI
- human brain simulation
- infinite memory
- production ready
- dense trillion-scale weights in 16GB VRAM
- GLIA replacing AILL today
- SenzaAdam Brain replacing Elena AILL as the umbrella project
- full AILL integration completed
- public chat product availability today

## Live Site

https://research.elenaxvora.com

## Maintainer Note

- Canonical README source: this file
- Generated public copy: `../public/README.md`
- Refresh the public copy with `..\scripts\publish_site.ps1`
- `cartella-pubblica-github-copia-e-incolla/` is legacy and should not be used for updates

## Full Project Structure

The complete AILL project is logically organized as follows:

```text
AILL Project
├── AILL Baseline
│   ├── core model built from scratch in PyTorch
│   ├── tokenizer and dataset pipeline
│   ├── training runs
│   ├── checkpoints
│   └── biological benchmark suite
│
├── GLIA Track
│   ├── GLIA Core v2
│   ├── non-Transformer memory/routing experiments
│   ├── AILL+GLIA isolated probe
│   └── 3-seed stability validation
│
├── SenzaAdam Track
│   ├── Adam-free persistent brain
│   ├── local synaptic updates
│   ├── active-cell-only compute
│   ├── unified portable brain file
│   ├── 100k real-data brain
│   ├── 1M real-data brain
│   └── 10M scale-up run
│
├── AILL <-> SenzaAdam Bridge
│   ├── concept_state -> SenzaAdam router
│   ├── memory recall -> injection vector
│   ├── read-only validation
│   └── future controlled AILL integration
│
├── Benchmark & Reports
│   ├── biological benchmark images
│   ├── GLIA benchmark images
│   ├── SenzaAdam benchmark images
│   ├── query / QA benchmark images
│   └── public visual report
│
└── Public Site
  ├── static HTML/CSS/JS
  ├── benchmark PNGs
  ├── public README
  └── no private model artifacts
```

## Live Site

https://research.elenaxvora.com

## Scope Note

AILL, GLIA, and SenzaAdam are research efforts. The baseline remains active. The isolated tracks remain isolated until a controlled validation step proves otherwise. This repository page is intended to describe validated public benchmark results clearly and conservatively.
