-   1 minute

You download Terraform for use in Azure via Azure Marketplace, Terraform Marketplace, or Azure VMs.

## Azure Marketplace

Azure Marketplace offers a fully configured Linux image containing Terraform with the following characteristics:

-   The deployment template will install Terraform on a Linux (Ubuntu 16.04 LTS) VM and tools configured to work with Azure. Items downloaded include:
    
    -   Terraform (latest)
    -   Azure CLI 2.0
    -   Managed Service Identity (MSI) VM extension
    -   Unzip
    -   Jq
    -   apt-transport-https
-   This image also configures a remote back-end to enable remote state management using Terraform.
    

## Terraform Marketplace

The Terraform Marketplace image makes it easy to get started using Terraform on Azure without installing and configuring Terraform manually. There are no software charges for this Terraform VM image. You pay only the Azure hardware usage fees that are assessed based on the size of the VM that's provisioned.

## Azure VMs

You can also deploy a Linux or Windows VM in Azure VM's IaaS service, install Terraform and the relevant components, and then use that image.

Need help? See our [troubleshooting guide](https://docs.microsoft.com/en-us/learn/support/troubleshooting?uid=learn.wwl.implement-terraform.explore-terraform-azure&documentId=71f39d73-c31b-4be0-0500-0243a58bb480&versionIndependentDocumentId=e55e4ce7-57e3-ca39-7810-a4405a8c98a4&contentPath=%2FMicrosoftDocs%2Flearn-pr%2Fblob%2Flive%2Flearn-pr%2Fwwl-azure%2Fimplement-terraform%2F4-explore-terraform-azure.yml&url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Flearn%2Fmodules%2Fimplement-terraform%2F4-explore-terraform-azure&author=lumac) or provide specific feedback by [reporting an issue](https://docs.microsoft.com/en-us/learn/support/troubleshooting?uid=learn.wwl.implement-terraform.explore-terraform-azure&documentId=71f39d73-c31b-4be0-0500-0243a58bb480&versionIndependentDocumentId=e55e4ce7-57e3-ca39-7810-a4405a8c98a4&contentPath=%2FMicrosoftDocs%2Flearn-pr%2Fblob%2Flive%2Flearn-pr%2Fwwl-azure%2Fimplement-terraform%2F4-explore-terraform-azure.yml&url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Flearn%2Fmodules%2Fimplement-terraform%2F4-explore-terraform-azure&author=lumac#report-feedback).