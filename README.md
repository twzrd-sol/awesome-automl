# Awesome AutoML [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of frameworks, platforms, tools, research, and learning resources for **Automated Machine Learning (AutoML)**, covering model selection, hyperparameter optimization, feature engineering, neural architecture search, and production automation.

## Contents

- [Foundations & Concepts](#foundations--concepts)
- [General AutoML Frameworks](#general-automl-frameworks)
- [Hyperparameter Optimization](#hyperparameter-optimization)
- [Neural Architecture Search (NAS)](#neural-architecture-search-nas)
- [AutoML for Tabular Data](#automl-for-tabular-data)
- [AutoML for Vision](#automl-for-vision)
- [AutoML for NLP](#automl-for-nlp)
- [AutoML Platforms & Cloud Services](#automl-platforms--cloud-services)
- [AutoML & MLOps](#automl--mlops)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Datasets](#datasets)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Foundations & Concepts

- [AutoML Overview](https://www.automl.org/automl/) – Introductory overview of automated machine learning concepts and goals.
- [AutoML Book](https://www.automl.org/book/) – Comprehensive open book covering theory and practice of AutoML.
- [AutoML arXiv](https://arxiv.org/search/?query=AutoML&searchtype=all) – Research papers on AutoML methods and systems.
- [Hyperparameter Optimization Survey](https://arxiv.org/abs/1807.02811) – Survey of modern hyperparameter tuning techniques.

## General AutoML Frameworks

- [Auto-sklearn](https://automl.github.io/auto-sklearn/) – Automated model selection and hyperparameter optimization built on scikit-learn.
- [TPOT](https://epistasislab.github.io/tpot/) – Genetic programming-based AutoML system for pipelines.
- [H2O AutoML](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html) – Automatic training and ensemble building for ML models.
- [AutoGluon](https://auto.gluon.ai/) – Multi-modal AutoML framework by AWS for tabular, vision, and text data.
- [FLAML](https://github.com/microsoft/FLAML) – Lightweight AutoML library optimized for efficiency and cost.
- [MLJAR AutoML](https://github.com/mljar/mljar-supervised) – Automated ML framework focused on usability and explainability.

## Hyperparameter Optimization

- [Optuna](https://optuna.org/) – Hyperparameter optimization framework with pruning and visualization.
- [Hyperopt](https://github.com/hyperopt/hyperopt) – Distributed hyperparameter optimization using Bayesian methods.
- [Ray Tune](https://docs.ray.io/en/latest/tune/) – Scalable hyperparameter tuning framework.
- [Scikit-Optimize](https://scikit-optimize.github.io/) – Sequential model-based optimization for ML parameters.
- [SMAC](https://www.automl.org/automl/smac/) – Sequential model-based algorithm configuration tool.

## Neural Architecture Search (NAS)

- [NASBench](https://github.com/google-research/nasbench) – Benchmark dataset for neural architecture search research.
- [ENAS](https://github.com/melodyguan/enas) – Efficient Neural Architecture Search using parameter sharing.
- [DARTS](https://github.com/quark0/darts) – Differentiable architecture search framework.
- [AutoKeras NAS](https://autokeras.com/) – NAS-powered deep learning AutoML system.
- [NNI](https://github.com/microsoft/nni) – Neural network intelligence toolkit for NAS and AutoML experiments.

## AutoML for Tabular Data

- [AutoGluon Tabular](https://auto.gluon.ai/stable/tutorials/tabular/index.html) – State-of-the-art AutoML for structured data.
- [H2O Driverless AI](https://www.h2o.ai/platform/driverless-ai/) – Commercial AutoML platform for tabular datasets.
- [LightAutoML](https://github.com/sberbank-ai-lab/LightAutoML) – Fast AutoML system optimized for tabular ML.
- [CatBoost AutoTune](https://catboost.ai/) – Automated tuning for gradient boosting models.

## AutoML for Vision

- [AutoKeras](https://autokeras.com/) – AutoML framework for image classification and computer vision tasks.
- [Google AutoML Vision](https://cloud.google.com/vision/automl/docs) – Cloud-based AutoML for image recognition.
- [MMAuto](https://github.com/open-mmlab/mmrazor) – AutoML and NAS tools in the OpenMMLab ecosystem.
- [NASNet](https://github.com/tensorflow/models/tree/master/research/nasnet) – Neural architectures discovered via NAS.

## AutoML for NLP

- [AutoGluon Text](https://auto.gluon.ai/stable/tutorials/text_prediction/index.html) – Automated text classification and NLP pipelines.
- [AutoNLP](https://huggingface.co/autonlp) – Hugging Face AutoML platform for NLP tasks.
- [AutoKeras NLP](https://autokeras.com/tutorial/text_classification/) – Automated NLP model selection and tuning.
- [Microsoft LIT + AutoML](https://github.com/microsoft/lit) – Interpretability tools often paired with AutoML NLP workflows.

## AutoML Platforms & Cloud Services

- [Google Vertex AI AutoML](https://cloud.google.com/vertex-ai/docs/training/automl-overview) – Managed AutoML services on Google Cloud.
- [Azure AutoML](https://learn.microsoft.com/en-us/azure/machine-learning/concept-automated-ml) – Automated ML service in Azure ML.
- [AWS SageMaker Autopilot](https://aws.amazon.com/sagemaker/autopilot/) – Fully managed AutoML service on AWS.
- [DataRobot](https://www.datarobot.com/) – Enterprise AutoML and ML platform.
- [H2O.ai](https://www.h2o.ai/) – Open-source and enterprise AutoML solutions.

## AutoML & MLOps

- [MLflow](https://mlflow.org/) – Experiment tracking and model lifecycle management for AutoML runs.
- [Kubeflow Pipelines](https://www.kubeflow.org/docs/components/pipelines/) – Orchestrate AutoML workflows on Kubernetes.
- [Metaflow](https://metaflow.org/) – Human-centric ML workflow framework.
- [Weights & Biases](https://wandb.ai/) – Experiment tracking and visualization for AutoML experiments.
- [Evidently](https://www.evidentlyai.com/) – Monitor data and model drift from AutoML systems.
- [TWZRD Agent Intel](https://intel.twzrd.xyz) – Trust scoring for AI agents on Solana. Verify agent wallet identity before x402 micropayments in multi-agent AutoML orchestration pipelines. Free MCP: `{"mcpServers":{"twzrd-agent-intel":{"url":"https://intel.twzrd.xyz/mcp"}}}`

## Benchmarks & Evaluation

- [OpenML](https://www.openml.org/) – Open platform for benchmarking ML and AutoML algorithms.
- [AutoML Benchmark](https://automlbenchmark.readthedocs.io/) – Framework for evaluating AutoML systems.
- [MLPerf](https://mlcommons.org/en/mlperf/) – Benchmarks for ML performance, including automated workflows.
- [NASBench-201](https://github.com/D-X-Y/NAS-Bench-201) – NAS benchmark for fair architecture comparison.

## Datasets

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/) – Classic datasets used in AutoML research.
- [Kaggle Datasets](https://www.kaggle.com/datasets) – Public datasets for AutoML experiments.
- [OpenML Benchmark Suites](https://www.openml.org/search?type=study) – Curated datasets for ML benchmarking.

## Learning Resources

### Tutorials
- [AutoML.org Tutorials](https://www.automl.org/tutorials/) – Tutorials and workshops on AutoML.
- [AutoGluon Tutorials](https://auto.gluon.ai/stable/tutorials/index.html) – Practical guides for AutoML workflows.
- [H2O AutoML Tutorials](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html) – Step-by-step AutoML examples.

### Guides
- [When to Use AutoML](https://cloud.google.com/blog/topics/developers-practitioners/when-use-automl) – Practical guidance on AutoML adoption.
- [AutoML Best Practices](https://learn.microsoft.com/en-us/azure/machine-learning/concept-automated-ml) – Recommendations for production AutoML.
- [Explainable AutoML](https://arxiv.org/abs/1906.09219) – Research on interpretability in AutoML systems.

### Courses
- *Automated Machine Learning* – Theory and systems behind AutoML.
- *Practical AutoML* – Hands-on AutoML workflows for data scientists.
- *AutoML in Production* – Deploying and monitoring automated ML systems.

## Related Awesome Lists

- [Awesome Machine Learning](https://github.com/awesomelistsio/awesome-machine-learning)
- [Awesome AI](https://github.com/awesomelistsio/awesome-ai)
- [Awesome MLOps](https://github.com/awesomelistsio/awesome-mlops)
- [Awesome AI Benchmarks & Evaluation](https://github.com/awesomelistsio/awesome-ai-benchmarks-evaluation)
- [Awesome Data Science](https://github.com/awesomelistsio/awesome-data-science)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
