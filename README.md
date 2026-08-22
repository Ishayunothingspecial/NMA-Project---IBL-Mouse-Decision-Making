# Mouse Decision Strategy Stability

## About?

Mice performing perceptual decision-making tasks do not simply respond to a stimulus, they have to continuously decide how to use the information available to them.

In the task used here, a mouse views a visual stimulus presented on either side of a screen. The stimulus varies in **contrast**, making some trials easier to detect than others. The mouse indicates which side it perceives the stimulus on and receives a reward for making the correct choice.

The question is whether a mouse uses the **same decision strategy throughout an entire behavioral session**, or whether the way it makes decisions changes as the session progresses.

## The Dataset

This project uses behavioral data from the **International Brain Laboratory (IBL)** dataset.

The dataset contains trial-by-trial behavior from mice performing the visual decision-making task. For each trial, information about the stimulus and the mouse's response is available, allowing us to examine how sensory evidence relates to the animal's choices.

Rather than treating the entire session as one continuous block, we examine how behavior changes **within the session itself**.

## Research Question

**Do mice maintain a stable decision strategy from the beginning to the end of a behavioral session?**

We focus on **stimulus sensitivity (β)**, which represents how strongly the mouse's choice is influenced by the visual stimulus.

A higher β indicates that the mouse's decisions are more strongly driven by the visual stimulus, while a lower β indicates weaker dependence on the current stimulus.

## What was done?

Sessions were divided into three temporal sections:

* **Early**
* **Middle**
* **Late**

Stimulus sensitivity was estimated separately for each section for mice with sufficient valid trials. This allowed us to compare each mouse with itself across different points in the same session.

The analysis then examined both the **population-level trend** and **individual differences between mice**.

## Main Finding

Most mice showed relatively small changes in stimulus sensitivity across the session, indicating that their decision strategies were **largely stable**.

However, at the population level, stimulus sensitivity showed a modest but statistically significant decline from the Early to Late portion of the session.

**Early vs Late: paired t-test, p = 0.0053**

Thus, the data suggest that mice generally maintain a stable decision strategy while still exhibiting subtle within-session changes in how strongly they rely on sensory information.

## Interpretation

The observed decline in stimulus sensitivity does not by itself establish why the change occurs. One possible interpretation, consistent with previous work on state-dependent decision-making, is that mice may gradually rely more on internal behavioral state or previous choices rather than exclusively on the current sensory stimulus.

This remains an interpretation rather than a directly tested mechanism in this analysis.

## Context

This analysis is part of a broader investigation into **internal state and behavioral variability in mouse decision-making**. Other analyses in the larger project examine measures such as engagement, pupil-linked arousal, lapses, and trial history to understand what may account for changes in behavior across a session.

## Reference

International Brain Laboratory (IBL) behavioral dataset.

Ashwood et al. (2022), *Mice alternate between discrete strategies during perceptual decision-making*.

