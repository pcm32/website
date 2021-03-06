---
layout: subsite-galaxy
website: https://ml.usegalaxy.eu
subdomain: ml
---

# Welcome to the Galaxy Machine Learning workbench
{:.no_toc}

![ML Galaxy](/assets/media/machine_learning_logo.png){:.rna-intro-right}

The Galaxy Machine Learning workbench is a comprehensive set of data preprocessing, machine learning, deep learning and visualisation tools, consolidated workflows for end-to-end machine learning analysis and training materials to showcase the usage of these tools.
The workbench is available on the [Galaxy framework](https://galaxyproject.org){:target="_blank"}, which guarantees simple access, easy extension, flexible adaption to personal and security needs, and sophisticated machine learning analyses independent of command-line knowledge.

The workbench provides you with a Swiss Army knife of [scikit-learn](https://scikit-learn.org){:target="_blank"},
[Keras](https://keras.io){:target="_blank"} (a deep learning library based on [TensorFlow](https://www.tensorflow.org){:target="_blank"}) and various other tools to transform, learn and predict and plot your data.

The workbench is currently developed by the [Goecks Lab](https://goeckslab.org) and the [European Galaxy project](https://galaxyproject.eu/){:target="_blank"}.
The [German Network for Bioinformatics Infrastructure (de.NBI)](http://www.denbi.de){:target="_blank"},
which runs the German [ELIXIR Node](https://www.elixir-europe.org/){:target="_blank"}, provides the necessary compute clusters with CPUs and GPU resources.

The project is a community effort, please jump in, ask questions, and contribute to the development of new tools, workflows or trainings!

# Content
{:.no_toc}

1. TOC
{:toc}

# Get started

Are you new to Galaxy, or returning after a long time, and looking for help to get started?
Take [a guided tour]({{ page.website }}/tours/core.galaxy_ui){:target="_blank"} through Galaxy's user interface.

# Training

We are passionate about training. So we are working in close collaboration with the
[Galaxy Training Network (GTN)](https://galaxyproject.org/teach/gtn/){:target="_blank"} to develop training materials of data analyses
based on Galaxy {% cite batut2017community %}. These materials hosted on the GTN GitHub
repository are available online at [https://training.galaxyproject.org](https://training.galaxyproject.org){:target="_blank"}.

Want to learn more about machine learning? Take one of our guided tours or check out the following hands-on tutorials, developed together with the [GTN community](https://galaxyproject.org/teach/gtn/).

Lesson | Slides | Hands-on | Input dataset | Workflows | Galaxy tour | Galaxy History
--- | --- | --- | --- | --- | --- | ---
Basics of machine learning |  | [<i class="fa fa-laptop" aria-hidden="true"></i>](https://training.galaxyproject.org/training-material/topics/statistics/tutorials/machinelearning/tutorial.html){:target="_blank"} | [<i class="fa fa-files-o" aria-hidden="true"></i>](https://zenodo.org/record/1468039#.W8zyxBRoSAo){:target="_blank"} | [<i class="fa fa-share-alt" aria-hidden="true"></i>]({{ page.website }}/workflows/run?id=17e99647745eb150){:target="_blank"} | [<i class="fa fa-magic" aria-hidden="true"></i>](https://github.com/galaxyproject/training-material/tree/master/topics/statistics/tutorials/machinelearning/tours/){:target="_blank"} | [<i class="fa fa-list-ul" aria-hidden="true"></i>]({{ page.website }}/u/sbray/h/basics-of-machine-learning){:target="_blank"} |
Classification |  | [<i class="fa fa-laptop" aria-hidden="true"></i>](https://training.galaxyproject.org/training-material/topics/statistics/tutorials/classification_machinelearning/tutorial.html){:target="_blank"} | [<i class="fa fa-files-o" aria-hidden="true"></i>](https://zenodo.org/record/3738729#.XsjpbHUzY5k){:target="_blank"} | [<i class="fa fa-share-alt" aria-hidden="true"></i>]({{ page.website }}/workflows/run?id=1d55d5d20c581b16){:target="_blank"} | | |
Regression |  | [<i class="fa fa-laptop" aria-hidden="true"></i>](https://training.galaxyproject.org/training-material/topics/statistics/tutorials/regression_machinelearning/tutorial.html){:target="_blank"} | [<i class="fa fa-files-o" aria-hidden="true"></i>](https://zenodo.org/record/2579649#.XHep39F7mL4){:target="_blank"} | [<i class="fa fa-share-alt" aria-hidden="true"></i>]({{ page.website }}/workflows/run?id=138d4893a1d6228e){:target="_blank"}  | | |
Age prediction using machine learning |  | [<i class="fa fa-laptop" aria-hidden="true"></i>](https://training.galaxyproject.org/training-material/topics/statistics/tutorials/age-prediction-with-ml/tutorial.html){:target="_blank"} | [<i class="fa fa-files-o" aria-hidden="true"></i>](https://zenodo.org/record/2545213#.XEWTJ9-YVa0){:target="_blank"} | [<i class="fa fa-share-alt" aria-hidden="true"></i>]({{ page.website }}/workflows/run?id=83fe480cdbb70099){:target="_blank"} [<i class="fa fa-share-alt" aria-hidden="true"></i>]({{ page.website }}/workflows/run?id=a669986e1a5cee31){:target="_blank"} |  | [<i class="fa fa-list-ul" aria-hidden="true"></i>]({{ page.website }}/u/sbray/h/age-prediction-using-machine-learning---rnaseq){:target="_blank"} [<i class="fa fa-list-ul" aria-hidden="true"></i>]({{ page.website }}/u/sbray/h/age-prediction-using-machine-learning---dna-methylation){:target="_blank"} |
Clustering |  | [<i class="fa fa-laptop" aria-hidden="true"></i>](https://training.galaxyproject.org/training-material/topics/statistics/tutorials/clustering_machinelearning/tutorial.html){:target="_blank"} | [<i class="fa fa-files-o" aria-hidden="true"></i>](https://zenodo.org/record/3813447#.Xsjsy3UzY5k){:target="_blank"} | [<i class="fa fa-share-alt" aria-hidden="true"></i>]({{ page.website }}/workflows/run?id=848389c45cebe34f){:target="_blank"} | | |
Introduction to deep learning |  | [<i class="fa fa-laptop" aria-hidden="true"></i>](https://training.galaxyproject.org/training-material/topics/statistics/tutorials/intro_deep_learning/tutorial.html){:target="_blank"} | [<i class="fa fa-files-o" aria-hidden="true"></i>](https://zenodo.org/record/3706539#.XsjteHUzY5l){:target="_blank"} | | | |
{:.table.table-striped}


# Available tools

In this section we list the most important tools that have been integrated into the Machine Learning workbench.
There are many more tools available so please have a more detailed look at the tool panel.
For better readability, we have divided them into categories.

## Classification

Identifying which category an object belongs to.

Tool | Description | Reference
--- | --- | ---
{% include tool.html id="sklearn_svm_classifier" %} | Support vector machines (SVMs) for classification| [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_nn_classifier" %} | Nearest Neighbors Classification | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_ensemble" %} | Ensemble methods for classification and regression | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_discriminant_classifier" %} | Linear and Quadratic Discriminant Analysis| [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_generalized_linear" %} | Generalized linear models for classification and regression | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_clf_metrics" %} | Calculate metrics for classification performance  | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{: .table.table-striped .tooltable}

## Regression

Predicting a continuous-valued attribute associated with an object.

Tool | Description | Reference
--- | --- | ---
{% include tool.html id="sklearn_ensemble" %} | Ensemble methods for classification and regression | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_generalized_linear" %} | Generalized linear models for classification and regression | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_regression_metrics" %} | Calculate metrics for regression performance | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{: .table.table-striped .tooltable}

## Clustering

Automatic grouping of similar objects into sets.

Tool | Description | Reference
--- | --- | ---
{% include tool.html id="sklearn_numeric_clustering" %} | Different numerical clustering algorithms | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{: .table.table-striped .tooltable}

## Model building

Building general machine learning models.

Tool | Description | Reference
--- | --- | ---
{% include tool.html id="sklearn_estimator_attributes" %} | Estimator attributes to get all attributes from an estimator or scikit object | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_stacking_ensemble_models" %} | Stacking Ensembles to build stacking, voting ensemble models with numerous base options | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_searchcv" %} | Hyperparameter Search performs hyperparameter optimization using various SearchCVs  | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_build_pipeline" %} | Pipeline Builder as an all-in-one platform to build pipeline, single estimator, preprocessor and custom wrappers | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{: .table.table-striped .tooltable}

## Model evaluation

Evaluation, validating and choosing parameters and models.

Tool | Description | Reference
--- | --- | ---
{% include tool.html id="sklearn_model_validation" %} | Model Validation includes cross_validate, cross_val_predict, learning_curve, and more | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_pairwise_metrics" %} | Evaluate pairwise distances or compute affinity or kernel for sets of samples | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_train_test_eval" %} | Train, Test and Evaluation to fit a model using part of dataset and evaluate using the rest | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="model_prediction" %} | Model Prediction predicts on new data using a preffited model | [Chollet et al. 2011](https://keras.io){:target="_blank"}
{% include tool.html id="sklearn_fitted_model_eval" %} | Evaluate a Fitted Model using a new batch of labeled data | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_model_fit" %} | Fit a Pipeline, Ensemble or other models using a labeled dataset | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{: .table.table-striped .tooltable}


## Preprocessing and feature selection

Feature selection and preprocessing.

Tool | Description | Reference
--- | --- | ---
{% include tool.html id="sklearn_data_preprocess" %} | Preprocess raw feature vectors into standardized datasets  | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_feature_selection" %} | Feature Selection module, including univariate filter selection methods and recursive feature elimination algorithm | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{: .table.table-striped .tooltable}

## Deep learning

Build and use deep neural networks.

Tool | Description | Reference
--- | --- | ---
{% include tool.html id="keras_batch_models" %} | Build Deep learning Batch Training Models with online data generator for Genomic/Protein sequences and images | [Chollet et al. 2011](https://keras.io){:target="_blank"}
{% include tool.html id="keras_model_builder" %} | Create deep learning model with an optimizer, loss function and fit parameters | [Chollet et al. 2011](https://keras.io){:target="_blank"}
{% include tool.html id="keras_model_config" %} | Create a deep learning model architecture using Keras | [Chollet et al. 2011](https://keras.io){:target="_blank"}
{% include tool.html id="keras_train_and_eval" %} | Deep learning training and evaluation either implicitly or explicitly  | [Chollet et al. 2011](https://keras.io){:target="_blank"}
{: .table.table-striped .tooltable}

## Visualization

Plotting and visualization.

Tool | Description | Reference
--- | --- | ---
{% include tool.html id="plotly_regression_performance_plots" %} | Plot actual vs predicted curves and residual plots of tabular data |
{% include tool.html id="plotly_ml_performance_plots" %} | Plot confusion matrix, precision, recall and ROC and AUC curves of tabular data |
{% include tool.html id="ml_visualization_ex" %} | Machine Learning Visualization Extension includes several types of plotting for machine learning | [Chollet et al. 2011](https://keras.io){:target="_blank"}
{: .table.table-striped .tooltable}

## Utilities

General data and table manipulation tools.

Tool | Description | Reference
--- | --- | ---
{% include tool.html id="table_compute" %} | The power of the pandas data library for manipulating and computing expressions upon tabular data and matrices. |
{% include tool.html id="datamash_ops" %} | Datamash operations on tabular data |
{% include tool.html id="datamash_transpose" %} | Transpose rows/columns in a tabular file |
{% include tool.html id="sklearn_sample_generator" %} | Generate random samples with controlled size and complexity | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{% include tool.html id="sklearn_train_test_split" %} | Split Dataset into training and test subsets | [Pedregosa et al. 2011](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html){:target="_blank"}
{: .table.table-striped .tooltable}

## Interactive Environments

You have done the heavy lifting and now want to use your coding skills inside Jupyter or RStudio? Work on data with the following:

Tool | Description | Reference
--- | --- | ---
[Jupyter](https://live.usegalaxy.eu/?tool_id=interactive_tool_jupyter_notebook){:target="_blank"} | Jupyter lab | 
[RStudio](https://live.usegalaxy.eu/?tool_id=interactive_tool_rstudio_notebook){:target="_blank"} | RStudio | 
{: .table.table-striped .tooltable}


# Contributors

- [Qiang Gu](https://github.com/qiagu)
- [Jeremy Goecks](https://github.com/jgoecks)
- [Anup Kumar](https://github.com/anuprulez)
- [Bjoern Gruening](https://github.com/bgruening)
- [Alireza Khanteymoori](https://github.com/khanteymoori)
- [Simon Bray](https://github.com/simonbray)
- [Vahid Jalili](https://github.com/VJalili)
