# Adaptive Pollination Service Management through Reinforcement Learning-Enhanced Agent-Based Modeling in Quebec’s Agricultural Regions
## Overview

This repository presents a novel Reinforcement Learning–Agent-Based Modeling (RL-ABM) framework designed to simulate and optimize pollination services in agricultural systems.

The framework models the interactions between farmers (pollination service demanders) and beekeepers (pollination service suppliers) across soybean-producing regions of Quebec, Canada. By combining Agent-Based Modeling (ABM), Reinforcement Learning (RL), and Machine Learning (ML), the system captures adaptive decision-making under changing environmental, climatic, and socio-economic conditions.

Unlike conventional ABMs that rely on predefined or random agent behaviors, the proposed RL-ABM allows agents to learn from experience, adapt their strategies over time, and respond dynamically to environmental feedback.

## Research Motivation

Pollination services represent a complex socio-ecological system where multiple stakeholders interact under uncertainty.

Key challenges include:

Climate variability affecting crop productivity.
Environmental factors influencing honeybee survival.
Spatial mismatches between pollination supply and demand.
Dynamic decision-making by farmers and beekeepers.
Trade-offs between agricultural production and pollinator health.

Traditional modeling approaches often fail to capture adaptive behaviors and long-term learning processes. This project addresses these limitations through a reinforcement learning-enhanced agent-based framework.

## Research Objectives

The main objectives of this project are to:

Simulate pollination service dynamics across agricultural landscapes.
Model adaptive decision-making of farmers and beekeepers.
Integrate machine learning predictions into agent decision processes.
Evaluate trade-offs between crop production and pollinator survival.
Assess the benefits of reinforcement learning in agricultural systems.
Support sustainable agricultural and pollinator management strategies.

## Study Area

📍 Soybean-Producing Census Agricultural Regions (CARs), Quebec, Canada

The framework simulates pollination service interactions across multiple agricultural regions over a six-year planning horizon:

2025–2030

The regionalized structure allows agents to adapt to local environmental and climatic conditions.

## Modeling Components
### 🤖 Reinforcement Learning (RL)

The reinforcement learning component enables agents to:

Learn from previous decisions.
Adapt to changing environmental conditions.
Optimize long-term outcomes.
Balance competing objectives.
Improve decision quality over time.

Agents continuously update their strategies based on rewards received from prior interactions.

### 👨‍🌾 Farmer Agents

Farmers represent the demand side of pollination services.

Decision Variables:

Number of beehives requested
Pollination service demand level
Resource allocation strategies

Objectives:
Maximize crop yield
Improve production stability
Adapt to climate variability

### 🐝 Beekeeper Agents

Beekeepers represent the supply side of pollination services.

Decision Variables:
Number of hives supplied
Service allocation among regions
Hive deployment strategies

Objectives: 
Maximize colony survival
Improve pollination service efficiency
Maintain sustainable operations
Machine Learning Models

### 🌾 Crop Yield Prediction
Extreme Gradient Boosting (XGBoost)

An XGBoost model was developed to estimate crop yields using:

Climate variables
Soil characteristics
Honeybee census information
Environmental indicators

### 🐝 Beehive Survival Prediction
Random Survival Forest (RSF)

A Random Survival Forest model was employed to estimate beehive survival probabilities.

Digital Elevation Model (DEM)
Climatic variables
Environmental variables
Synthetic beehive datasets

## Model performance evaluation
To evaluate the effectiveness of reinforcement learning, the RL-ABM was compared against a conventional ABM where agent decisions were randomized under identical environmental conditions.

1. Baseline ABM
No learning capability
Random decision selection
No adaptation over time

3. RL-ABM
Learning-based decision-making
Adaptive behavior
Dynamic response to feedback

### Key Findings
🏆 RL-ABM Outperformed the Baseline ABM

The reinforcement learning framework generated:

More diverse solutions
Improved adaptation
Better long-term decision-making
Enhanced system resilience
Pareto Front Analysis

The RL-ABM produced a broader set of non-dominated solutions.

This indicates superior exploration of trade-offs between:

Crop productivity
Pollinator survival
Long-term sustainability
Pollinator-Centered Strategies

One of the most important findings was that RL agents frequently prioritized:

🐝 Pollinator viability over short-term yield maximization

This behavior aligns with resilience-based and agroecological management principles.

Adaptive Farmer Behavior

Farmer agents learned to:

Adjust hive demand dynamically
Respond to changing climatic conditions
Modify decisions across years and regions

Although moderate hive requests were commonly preferred, decisions varied considerably across space and time.

Adaptive Beekeeper Behavior

Beekeepers exhibited even greater flexibility.

Their decisions were influenced by:

Colony survival prospects
Environmental conditions
Regional opportunities
Future rewards

This adaptive behavior resulted in more efficient pollination service allocation.. 
