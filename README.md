# Operational Abandonment Reduction & CR Recovery System

## Business Context
CR (Completion Rate) is a critical operational metric, defined as output over input, with a required target of above 99%.

However, CR performance is highly sensitive to task abandonment. Even a small number of abandoned tasks can significantly degrade CR, making traditional performance monitoring insufficient to address the root problem.

---

## Problem Statement
The operation faced persistent CR underperformance driven primarily by task abandonment.

Key challenges included:
- Limited visibility into when and why tasks were abandoned
- Difficulty distinguishing objective constraints (e.g. capacity, latency spikes) from controllable operational issues
- Lack of a structured daily monitoring mechanism to track recovery progress

The core objective was not only to improve CR, but to systematically drive abandoned tasks toward near-zero levels.

---

## Analytical & Monitoring Approach
The solution focused on three layers:

1. **Trend Identification**
   - Daily and hourly abandonment patterns
   - Comparison against historical min/max ranges

2. **Root Cause Classification**
   - Objective causes (capacity, latency constraints)
   - Subjective or controllable causes (process gaps, execution issues)

3. **Continuous Improvement Monitoring**
   - Daily abandonment tracking
   - Queue-level CR and latency performance
   - Progress visibility toward abandonment reduction targets

> Due to confidentiality obligations, data and internal logic are abstracted and presented at a conceptual level.

---

## Key Decisions Supported
- Identification of high-risk hours and queues contributing disproportionately to abandonment
- Prioritization of operational fixes based on root cause type
- Evaluation of daily improvement effectiveness toward CR recovery

---

## Outcome & Impact
The dashboard enabled operations leaders to shift from reactive metric tracking to proactive abandonment prevention.

By focusing on abandonment reduction rather than CR alone, the operation established a clearer, more controllable path toward sustainable CR performance.
![CR Abandonment Dashboard](images/dashboard_overview.jpg)
---

## Core Skills Demonstrated
- Operations Performance Analysis
- Root Cause & Trend Analysis
- Decision-Oriented Dashboard Design
- Stakeholder Support for Operational Recovery

---

