# Riemann-Model

> **Open Source Side (OSS)**  
> This is the open source implementation of the Riemann Model, designed to mirror the functionality of the proprietary version while providing greater customization and transparency. This OSS version allows users to modify, extend, and adapt the model according to their specific needs.

## Overview

The Riemann Model harnesses the power of specialized Large Language Models to implement probabilistic trading strategies based on analyst recommendation analysis. This sophisticated system evaluates analyst calls, historical accuracy rates, and market responses to identify which analysts consistently provide valuable insights for specific sectors. By ranking analyst recommendations and assigning confidence scores, the Riemann Model cuts through the noise of conflicting opinions, offering a 12% improvement in selection accuracy compared to treating all analyst opinions equally.

## Key Features

- **Analyst Rating Ranking**: Evaluates and ranks analyst recommendations using LLM analysis
- **Web Scraping**: Collects analyst recommendations from free forums, Benzinga, and other financial websites
- **Ensemble Learning**: Weights analysts based on historical performance and portfolio analysis
- **Confidence Scoring**: Assigns confidence scores to recommendations

## Purpose

The goal of the Riemann Model is to move beyond traditional approaches:
- Instead of using one or two analyst opinions
- Instead of following paid research services (which are often expensive and limited)
- Instead of relying on single analyst recommendations

The model leverages the collective intelligence of multiple analysts, continuously evaluating and ranking their performance to optimize trading decisions based on analyst insights. Higher-ranked analysts with better historical accuracy receive higher coefficients, meaning they have more influence in the Riemann Model's final decision-making process.

