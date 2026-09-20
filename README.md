# Awesome-Hyperparameter-Optimization-Platform

Top Hyperparameter Optimization Tools Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Bayesian Optimization, Hyperparameter Tuning, Neural Architecture Search & AutoML
Last updated: September 2026

This repository tracks notable SaaS platforms and open-source projects for Hyperparameter Optimization (HPO). These tools help machine learning engineers and data scientists automate the search for optimal hyperparameters, reducing manual experimentation and improving model performance across training pipelines.

Examples include SigOpt, Weights & Biases Sweeps, Optuna Hub, Katib, Determined AI, ClearML HPO, Comet Optimizer, Amazon SageMaker HPO, Vertex Vizier, and Ray Tune (the category leaders).

Open-source emphasis: This section is heavily expanded with every major active project for self-hosting, custom tuning algorithms, and transparent experimentation — ideal for ML engineers, researchers, and teams building AutoML pipelines without vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

SaaS/Hosted Platforms

SigOpt
Enterprise Bayesian optimization platform for hyperparameter tuning and experiment design. Acquired by Intel in 2020 and integrated into Intel's AI software portfolio.

Weights & Biases Sweeps
Hyperparameter optimization integrated into the W&B experiment tracking platform. Supports grid, random, and Bayesian search with visualization dashboards.

Optuna Hub
Community hub for sharing and discovering Optuna-based optimization algorithms, visualization tools, and integration modules. Built around the open-source Optuna framework.

Katib
Kubernetes-native hyperparameter tuning and neural architecture search system, part of the Kubeflow ecosystem. Manages Experiments, Suggestions, and Trials as Kubernetes Custom Resources -
3
.

Determined AI
All-in-one deep learning platform with built-in hyperparameter tuning, distributed training, and resource management. Now part of Hewlett Packard Enterprise -
5
.

ClearML HPO
Open-source MLOps platform with hyperparameter optimization supporting Optuna, BOHB, RandomSearch, and GridSearch strategies. Provides Web UI for managing optimization tasks -
6
-
20
.

Comet Optimizer
Experiment management platform with hyperparameter optimization capabilities. Tracks, visualizes, and compares tuning experiments alongside model metrics.

Amazon SageMaker HPO
Fully managed hyperparameter tuning service within AWS SageMaker. Supports Bayesian, random, and Hyperband strategies with automatic early stopping.

Vertex Vizier
Google Cloud's hyperparameter tuning service based on the Vizier algorithm. Supports multi-objective optimization and early stopping for Vertex AI training jobs.

Ray Tune
Distributed hyperparameter tuning library from the Ray ecosystem. Supports multiple search algorithms including ASHA, Hyperband, BOHB, and Bayesian optimization -
16
.

Open-Source GitHub Projects

Optuna
A hyperparameter optimization framework designed for machine learning. Features define-by-run API, TPE/CMA-ES samplers, pruning algorithms, and distributed optimization. One of the most widely adopted HPO libraries. License: MIT.

Ray Tune
Distributed hyperparameter tuning at scale. Part of the Ray ecosystem with support for ASHA, Hyperband, BOHB, PBT, and Bayesian optimization. Integrates with PyTorch, TensorFlow, and XGBoost. License: Apache 2.0 -
16
.

NNI (Neural Network Intelligence)
Microsoft's open-source AutoML toolkit for hyperparameter tuning, neural architecture search, and model compression. Built-in tuners include TPE, SMAC, BOHB, and GP. Supports local, remote, Kubernetes, and cloud training platforms -
4
-
11
.

Katib
Kubernetes-native hyperparameter tuning and NAS system. Defines Experiments as CRDs with search spaces, algorithms, and objectives. Supports multiple metrics collection strategies -
3
.

Determined
All-in-one deep learning platform with integrated hyperparameter tuning. Supports adaptive_asha, random, and grid search strategies. Deploys locally or on AWS/GCP with YAML configuration -
5
-
12
.

ClearML
Open-source MLOps platform with HPO module. Supports Optuna, BOHB, RandomSearch, and GridSearch. Provides Web UI for monitoring optimization experiments -
6
-
20
.

Ax (Adaptive Experimentation)
Facebook's platform for adaptive experimentation and Bayesian optimization. Built on BoTorch with support for multi-objective optimization and batch acquisition functions. License: MIT.

BoTorch
Bayesian optimization library built on PyTorch. Provides modular components for building custom acquisition functions and optimization loops. Foundation for Ax and other HPO tools. License: MIT.

SMAC3
Sequential Model-based Algorithm Configuration. A versatile Bayesian optimization package for hyperparameter optimization with support for categorical and continuous parameters -
8
.

Hyperopt
Distributed asynchronous hyperparameter optimization library. Features Tree-structured Parzen Estimator (TPE) and random search algorithms. Widely used in academic and industrial ML pipelines.

GPyOpt
Gaussian process optimization library from the Sheffield ML group. Provides Bayesian optimization with support for batch suggestions and constrained optimization -
8
.

Spearmint
Bayesian optimization codebase from Harvard's HIPS lab. Implements algorithms from "Practical Bayesian Optimization of Machine Learning Algorithms" -
8
.

mlr3mbo
R toolbox for Bayesian optimization and model-based optimization. Provides building blocks for custom algorithms with support for single- and multi-objective optimization and mixed search spaces -
1
-
15
.

HEBO
Heteroscedastic Evolutionary Bayesian Optimization from Huawei Noah's Ark Lab. Designed for high-dimensional and conditional search spaces.

Dragonfly
Scalable Bayesian optimization library with support for multi-fidelity and multi-objective optimization. Includes tree-based ensemble methods -
9
.

Hyperband
Reference implementation of the Hyperband algorithm for hyperparameter optimization. Provides early-stopping bandit-based approach to resource allocation -
8
.

Additional Strong Open-Source Options

Algorithm-Specific Libraries: CMA-ES (Python implementation of Covariance Matrix Adaptation), BayesianOptimization (pure Python BO with scipy.optimize interface), RoBO (Robust Bayesian Optimization framework) -
8
.

Kubernetes-Native: Katib for Kubeflow users, Kubernetes Jobs with custom HPO controllers.

Framework Integrations: Optuna integrations for PyTorch Lightning, scikit-learn, XGBoost, and LightGBM.

Visualization & Tracking: Optuna Dashboard, Weights & Biases (self-hosted), TensorBoard HParams plugin.

Frameworks for building custom systems: Combine Optuna or Ray Tune for the tuning engine, Katib for Kubernetes orchestration, Determined for full experiment management, and PostgreSQL + Redis for persistence. Add MLflow or Weights & Biases for tracking and visualization.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Hyperparameter optimization tools consume significant compute resources; monitor costs and resource utilization carefully.

Self-hosted open-source solutions require proper cluster management, storage, and security configuration.

Made for ML engineers, data scientists, AutoML researchers, and MLOps practitioners.
Let's make hyperparameter optimization more open, reproducible, and scalable.
