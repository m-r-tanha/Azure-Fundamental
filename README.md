# Azure-Fundamental
### Azure Machine Learning Studio

Azure Machine Learning Studio is built considering the cloud-first mobile-first world.

- This tool is fully managed and we don’t have a need to install any external software, or manage any hardware, as there is one portal to view and update everything.

It’s very simple to use. Simple drag, drop and connect interfaces are there to use for data science features. We don’t need any programming for common tasks.

- 33+ classic and mostly used data analysis algorithms are already implemented on this tool. We don’t need to implement new algorithm for basic use. But, it supports R and Python for extensibility usage.

- We can create service and integrate our data analysis tool with our existing web, mobile, or desktop application very easily. We can monetize our designed data analysis model in machine learning marketplace as well.

- We can collaborate work with anyone, anywhere via Azure workspace.

- There is visual composition with end2end support for data science workflow.

- There are built in immutable libraries of models. So, developers just need to search, discover, and reuse them according to their need.

- As we don’t need to do implement our own code, we can test our dataset with different algorithms and models in few minutes.

## Azure Machine Learning Studio supports different types of data format. It supports,

- ARFF
- CSV
- TSV
- Excel
- ZIP as data format.
## We can use different data sources in Azure ML Studio. Some of the supported data sources are,

- Azure Blob Storage
- Azure SQL DB
- Azure SQL DW
- Azure Table
- Hadoop Hive Query
- OData Feed
- Web URL(HTTP)
- Desktop Direct Upload etc.
## We can use different types of data preprocessing methods to explore and process our collected data. Some of them are,

- Clean Missing Data
- Clip Outliers
- Edit Metadata
- Different Filters
- Feature Selection
- Normalization of Data
- Partition
- Quantization etc.
## We can use different methods of data visualization in Azure Machine Learning Studio. These data visualization models are already implemented. We just need to integrate in our system and use them. Some of them are, 

- Box Plots
- Histograms
- Bar Charts
- Scatterplots
- Python Plotting Libraries
- ROC Graph
- Decision Tree
- Confusion Matrix
- Implemented algorithms

## On 8 major categories, 33+ classic and mostly used machine learning algorithms are already implemented in Azure Machine Learning Studio. Major categories and algorithms are,

- Clustering
- 1 K-Means Clustering
- Anomaly Detection
- One-class support vector machine
- 1 PCA-Based Anomaly Detection
- 2 Time Series Anomaly Detection
1. Regression

  1. Bayesian Linear Regression
  1. Boosted Decision Tree Regression
  Decision Forest Regression
  Fast Forest Quantile Regression
  Linear Regression
  Neural Network Regression
  Ordinal Regression
  Poisson Regression
Two-Class Classification

Two-Class Averaged Perceptron
Two-Class Bayes Point Machine
Two-Class Boosted Decision Tree
Two-Class Decision Forest
Two-Class Decision Jungle
Two-Class Locally-Deep Support Vector Machine
Two-Class Logistic Regression
Two-Class Neural Network
Two-Class Support Vector Machine
Multi-Class Classification

Multiclass Decision Forest
Multiclass Decision Jungle
Multiclass Logistic Regression
Multiclass Neural Network
One-vs-All Multiclass
Computer Vision

OpenCV Library

Text Analytics

Feature Hashing
Named Entity Recognition
Vowpal Wabbit
Statistical Functions

Descriptive Statistics
Hypothesis Testing T-Test
Linear Correlation
Probability Function Evaluation

### Compute Instance
- Use a **compute instance** as your fully configured and managed development environment in the cloud for machine learning. They can also be used as a compute target for training and inferencing for development and testing purposes.
- Azure Machine Learning compute instance enables you to author, train, and deploy models in a fully integrated notebook experience in your workspace.
You can run Jupyter notebooks in VS Code using compute instance as the remote server with no SSH needed. You can also enable VS Code integration through remote SSH extension.
- You can install packages and add kernels to your compute instance.
- https://docs.microsoft.com/en-us/azure/machine-learning/how-to-access-terminal
### Data Science Virtual Machine
DSVMIt is a special kind of virtual machine on Azure. Unlike general virtual machines, the virtual machine has been pre-configured with the following environment when it is created:

- Packages such as TensorFlow, PyTorch, Scikit-learn, XGBoost, and Azure Machine Learning SDK
- Common data science tools such as Spark Standalone and Drill
- Azure tools such as Azure CLI, AzCopy, and Storage Explorer
- Integrated development environments (IDE) such as Visual Studio Code and PyCharm
J- upyter Notebook server
