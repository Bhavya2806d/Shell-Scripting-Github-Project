In list-users-github.sh
We will able to list the people who access to any repository in an organization.
You need to pass two parameters- organization name followed repository name.


In azcli-checkresources-github.sh

This Bash script lists Azure resources using the Azure CLI. It provides:
- A list of all Virtual Machines (VMs)
- A list of all VMs in a specific resource group
- A list of all storage accounts
- A list of all blob containers in a specific storage account
The script helps Azure administrators and DevOps engineers quickly get an overview of resources in their subscription.

Prerequisites
- Azure CLI installed: [Install Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
- Logged into Azure: Run `az login` before executing the script.
- Bash shell: The script is written for Bash.
- Sufficient permissions: You need `Reader` or higher access to list resources.

Usage
-Make the script executable:
chmod +x azcli-checkresources.sh

Run
./azcli-checkresources.sh




