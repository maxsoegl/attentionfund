# attentionfund

#Code Description
This repository contains the full codebase used in the research project “Public Attention Signals and Short-Horizon Market Dynamics.” The purpose of this code is to support empirical analysis of whether publicly observable attention measures—such as Google search trends and Wikipedia pageview activity—provide incremental predictive information about short-horizon stock market volatility and downside risk beyond historical price-based features.
The project emphasizes methodological transparency and reproducibility rather than the development of a deployable trading system. All models are evaluated out-of-sample using time-series–aware validation procedures to mitigate lookahead bias. The code implements feature engineering pipelines for price-based and attention-based signals, constructs clearly defined prediction targets, and compares baseline models against attention-augmented alternatives using standard performance metrics.
Key components include:
Data ingestion and preprocessing for market prices, volatility indices, and public attention sources
Normalization and feature engineering of attention signals relative to historical baselines
Gradient-boosted model training with rolling time-series splits
Out-of-sample evaluation focused on short-horizon volatility increases and downside risk
Utilities for performance comparison and feature importance analysis
This repository is intended as a research artifact, not as financial advice or an automated trading framework. The results derived from this code are discussed in the accompanying paper, which highlights both the informational value and the structural limitations of public attention data in financial markets.
All data sources used are publicly accessible, and the code is organized to facilitate inspection, modification, and replication of the analysis.
