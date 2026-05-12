# Epilepsy & Brain Atrophy: Predictive Modeling

This project applies simple and multiple linear regression to three 
neuroscience and behavioral datasets to identify patterns, generate 
predictions, and evaluate competing theoretical explanations.

## Analyses

**1. Temporal Lobe Epilepsy & Hippocampal Atrophy**
Models hippocampal volume loss over time in 90 epilepsy patients, 
comparing atrophy trajectories between the ipsilateral hemisphere 
(seizure-origin side) and contralateral hemisphere. An interaction 
regression model enables hemisphere-specific volume predictions at 
any point in a patient's diagnosis timeline.

**2. Temporal Rate Perception**
Tests whether prior exposure to fast or slow rhythms affects 
subsequent rate perception. Linear regression is used to evaluate 
two competing hypotheses — priming vs. adaptation — across 150 
experimental trials.

**3. Cognitive Load & Postural Balance**
Examines whether solving math problems while balancing increases 
postural instability. A parallel slopes multiple regression model 
isolates the effect of cognitive task beyond what body weight alone 
would predict.

## Tools & Skills
R · ggplot2 · tidyverse · dplyr · moderndive · linear regression · 
multiple regression · interaction models · data visualization

## Files
- `epilepsy_predictive_modeling.Rmd` — full annotated source code
- `epilepsy_predictive_modeling.html` — rendered report
