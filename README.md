# aml-dask-interactive

This sample shows you how to provision interactive Dask cluster in Azure Machine Learning Workspace. 

## Prerequisite 
[ v ] Azure Subscription

[ v ] An account with contributor role of a Resource Group or Azure Machine Learning Service

[ v ] Azure Machine Learning Service

[ v ] (Optional) Azure Virtual Network

[ v ] Puttygen 

## Architecture Diagram

![architecture](https://raw.githubusercontent.com/hyssh/aml-dask-interactive/main/img/architecture.png)

## Steps

Make sure you have access to Azure Machine Learning Workspace with contributor role.

### 1. Create CI (Compute Instance) in AML

Create CI or you can use your local machine. Make sure you have Azure Machine Learning SDK for Python install.

### 2. Clone this git repo from AML Notebook

![architecture](https://raw.githubusercontent.com/hyssh/aml-dask-interactive/main/img/git_clone.png)

### 3. Run notebook 'GetStartDask'

![architecture](https://raw.githubusercontent.com/hyssh/aml-dask-interactive/main/img/getStartDask.png)

### 4. Stop 'GetStartDask' run 

Stop the Run to terminate the Compute Cluster
