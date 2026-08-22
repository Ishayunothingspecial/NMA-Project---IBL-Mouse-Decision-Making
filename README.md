# Mouse Decision Strategy Stability

## Overview

This project investigates whether mice maintain a stable decision-making strategy throughout a behavioral session, or whether their strategy changes over time.

The analysis uses behavioral data from the **International Brain Laboratory (IBL)** dataset, in which mice perform a visual contrast discrimination task. The project focuses on how strongly mice rely on the visual stimulus when making choices and how this changes across a session.

## Research Question

**Do mice maintain a stable decision strategy from the beginning to the end of a behavioral session?**

More specifically, we examine whether **stimulus sensitivity (β)** changes across the session. β reflects how strongly a mouse's choices are driven by the visual stimulus.

## Dataset

The analysis focuses on trained mice with sufficient valid trials for reliable within-session comparisons.

Each behavioral session is divided into:

* **Early**
* **Middle**
* **Late**

This allows changes in decision-making to be examined within the same mouse over the course of a session.

## Main Finding

Most mice show relatively small changes in stimulus sensitivity across the session, suggesting that their decision strategies are largely stable.

At the population level, however, stimulus sensitivity shows a modest but statistically significant decline from the Early to Late phase.

**Early vs Late: paired t-test, p = 0.0053**

This suggests that decision strategies are generally stable while still showing subtle within-session modulation.

## Interpretation

The late-session reduction in stimulus sensitivity may be consistent with changes in internal behavioral state or increased reliance on factors other than the immediate sensory stimulus. This interpretation is supported by previous work on state-dependent decision-making, but the present analysis does not directly establish the underlying mechanism.

## Project Context

This analysis forms part of a broader investigation into how **internal state, behavioral history, engagement, arousal, and lapses** influence decision-making in mice.

The central motivation is to understand whether behavioral variability reflects rapid trial-to-trial fluctuations, stable individual strategies, or slower changes occurring across a behavioral session.

## Reference

International Brain Laboratory (IBL) behavioral dataset.

Ashwood et al. (2022), *Mice alternate between discrete strategies during perceptual decision-making*.
