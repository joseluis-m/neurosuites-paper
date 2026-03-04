# NeuroSuites: An Online Platform for Running Neuroscience, Statistical and Machine Learning Tools

**Author:** José Luis Moreno-Rodríguez  
**Contact:** joseluis.m.r@outlook.com  
**Platform:** [https://neurosuites.com](https://neurosuites.com)

---

## About

NeuroSuites is an open-access web platform designed for data scientists and neuroscientists. It integrates statistical data analysis, machine learning algorithms, and neuroscience-specific tools into a single browser-based environment — no local installation required.

This repository contains the technical paper describing the platform's architecture, features, and available tools.

## Paper

The full paper is available in this repository:

📄 **[neurosuites-paper.pdf](neurosuites-paper.pdf)**

### Abstract

> Problems with large amounts of data are common in the field of neuroscience. Specific machine learning and statistical tools are then required to transform the data into useful knowledge. In this work we present NeuroSuites, an easy-access web platform with its own architecture that we developed. NeuroSuites has different software tools to integrate statistical data analysis and machine learning algorithms commonly used in neuroscience applications. The list of available software tools will be expanded in future updates, enabled by the scalability of the NeuroSuites architecture.

### Keywords

Neuroscience · Web application · Statistical analysis · Machine learning · Supervised classification · Unsupervised classification · Bayesian networks

## Platform highlights

- **No installation required** — runs entirely in the browser
- **Responsive web design** — accessible from any device
- **Free and open source** — no pricing plans, full code available
- **Scalable architecture** — Docker-based microservices with task queuing (RabbitMQ + Celery)
- **Backend:** Python, Django REST, NumPy, SciPy, Scikit-learn, R (via rpy2)
- **Frontend:** Django CMS, Bootstrap, jQuery, Ajax

## Available tools

| Category | Tools |
|---|---|
| **Neuroscience apps** | L-Measure, NeuroViewer, NeuroSTR, 3DBasalRM, GabaClassifier, 3DspineS, 3DSomaMS, 3DSynapsesSA, Dendritic arborisation simulation, MultiMap |
| **Statistical analysis** | Descriptive and inferential statistics for categorical and continuous data, distribution fitting, correlation analysis, hypothesis testing |
| **Preprocessing** | Missing value handling, normalisation, feature selection (Chi², MI, ANOVA), dimensionality reduction (PCA, ICA, t-SNE, MDS) |
| **Unsupervised learning** | Hierarchical clustering, K-means, DBSCAN, spectral clustering |
| **Supervised learning** | Naive Bayes, TAN, decision trees, k-NN, SVM, RIPPER, LDA, QDA, logistic regression |
| **Bayesian networks** | Structure learning (15+ algorithms), parameter learning, visualisation, inference |
| **Multidimensional classifiers** | Binary relevance, classifier chains, label powerset, RAkEL, multi-label k-NN, multi-label SVM |

## Related repositories

- **Platform source code:** [ComputationalIntelligenceGroup on GitHub](https://github.com/ComputationalIntelligenceGroup)

## License

This paper is distributed under the terms of the [Creative Commons Attribution License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
