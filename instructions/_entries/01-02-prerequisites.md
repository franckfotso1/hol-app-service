---
sectionid: prereq
sectionclass: h2
title: Prerequisites
parent-id: intro
---

### Prerequisites

This workshop will require the following:

- Access to the [Azure Portal](https://portal.azure.com) subscription
- [Azure CLI](https://github.com/Azure/azure-cli)
- [VS Code](https://code.visualstudio.com/) or equivalent
- [Visual Studio 2022](https://visualstudio.microsoft.com/fr/vs/)
- A [Github](https://github.com/join) account

- ### Install Azure CLI

If the CLI is not installed, just follow [this link](https://docs.microsoft.com/fr-fr/cli/azure/install-azure-cli) to do it and follow the tab corresponding to your operating system.

#### Log in to your Azure subscription using Azure CLI and inside the [Azure Portal](https://portal.azure.com)

{% collapsible %}

```bash
# Login to Azure
az login
# Display your account details
az account show
# Choose a specific subscription 
az account set –s <subscription-id> 
```

{% endcollapsible %}
