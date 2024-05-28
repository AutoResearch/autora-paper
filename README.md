# AutoRA: Automated Research Assistant for Closed-Loop Empirical Research

This repository hosts the joint JOSS submission of the [AutoRA](https://github.com/AutoResearch/autora) framework.

**CORE PACKAGES** (required dependency)

The AutoRA framework consists of core packages with minimal dependencies.

- [autora](https://github.com/AutoResearch/autora): Main repository that hosts the documentation of autora across all vetted subpackages and serves as the main package.
- [autora-core](https://github.com/AutoResearch/autora): AutoRA workflow mechanics.
- [autora-synthetic](https://github.com/AutoResearch/autora): Synthetic models for benchmarking in AutoRA.

**OPTIONAL PACKAGES** (optional dependency):

In addition, the AutoRA framework provides vetted optional dependencies for workflow components, including theorists (for automating model discovery), experimentalists (for automating experimental design), and experiment runners (for automating data collection).

Theorist Components:
- [autora[theorist-darts]](https://github.com/AutoResearch/autora-theorist-darts): Automated model discovery with Differentiable Architecture Search. 
- [autora[theorist-bms]](https://github.com/AutoResearch/autora-theorist-bms): Automated model discovery with Bayesian Machine Scientist.
- [autora[theorist-bsr]](https://github.com/AutoResearch/autora-theorist-sr): Automated model discovery with Bayesian Symbolic Regression.

Experimentalist Components:
- [autora[experimentalist-falsification]](https://github.com/AutoResearch/autora-experimentalist-uncertainty): Automated experimental design based on predicted model falsification.
- [autora[experimentalist-inequality]](https://github.com/AutoResearch/autora-experimentalist-inequality): Automated experimental design based on a pairwise distance metric.
- [autora[experimentalist-leverage]](https://github.com/AutoResearch/autora-experimentalist-uncertainty): Automated experimental design based on the leverage of data points on model predictions.
- [autora[experimentalist-mixture]](https://github.com/AutoResearch/autora-experimentalist-uncertainty): Automated experimental design based on mixture of  experimentalists.
- [autora[experimentalist-nearest-value]](https://github.com/AutoResearch/autora-experimentalist-nearest-value): Automated experimental design based on distance to existing pool of experiment conditions.
- [autora[experimentalist-novelty]](https://github.com/AutoResearch/autora-experimentalist-novelty): Automated experimental design based on experiment novelty.
- [autora[experimentalist-model-disagreement]](https://github.com/AutoResearch/autora-experimentalist-model-disagreement): Automated experimental design based on model disagreement.
- [autora[experimentalist-uncertainty]](https://github.com/AutoResearch/autora-experimentalist-uncertainty): Automated experimental design based on model uncertainty.

Experiment Runner Components:
- [autora[experiment-runner-firebase-prolific]](https://github.com/AutoResearch/autora-experiment-runner-firebase-prolific): Automated data collection through serving an experiment on [Firebase](https://firebase.google.com/) and recruiting participants with [Prolific](https://www.prolific.com/).
- [autora[experiment-runner-experimentation-manager-firebase]](https://github.com/AutoResearch/autora-experiment-runner-experimentation-manager-firebase): Automated data collection through serving an experiment on Firebase.
- [autora[experiment-runner-recruitment-manager-prolific]](https://github.com/AutoResearch/autora-experiment-runner-recruitment-manager-prolific): Automated participant recruitment with Prolific.


