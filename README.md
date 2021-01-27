---
page_type: sample
languages:
  - python
products:
  - azure
  - azure-redis-cache
description: "This sample creates a multi-container application in an Azure Kubernetes Service (AKS) cluster."
---

# Azure Voting App

This sample creates a multi-container application in an Azure Kubernetes Service (AKS) cluster. The application interface has been built using Python / Flask. The data component is using Redis.

To walk through a quick deployment of this application, see the AKS [quick start](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough?WT.mc_id=none-github-nepeters).

To walk through a complete experience where this code is packaged into container images, uploaded to Azure Container Registry, and then run in and AKS cluster, see the [AKS tutorials](https://docs.microsoft.com/en-us/azure/aks/tutorial-kubernetes-prepare-app?WT.mc_id=none-github-nepeters).

## Guidelines for a newly joined Developer

  ## Our Workflow and Branching Strategy
    
    This section represents our current branching and release strategy.

    Forking Workflow is what we follow here. We have one main branch which is the Master.

    Steps to follow:
    * Fork this official server-side repository.
    * Clone the forked repository to your local system.
    * Add a git remote path of the official repository to your local clone.
    * Each feature will have its own branch. 
    * You should be making changes and committing them to the respective branch.
    * When you finish building and testing the feature, you should push to your own branch on the server.
    * Open a Pull request from your branch to the official repository.
    * Your Pull request will be reviewed and merged after receiving the approval.


  ## Commiting Guidelines

     Pre-Commit Check

        We have a pre-commit check where you need to ensure the following:
        * Added only the relevant files to commit
        * Have updated the documentation pertaining to the commit
        * Know the relevant Jira Issue ID 

     Commit Message Check
        
        We have a commit-msg check which ensures that you have mentioned the relevant Jira ID in the commit message.

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
