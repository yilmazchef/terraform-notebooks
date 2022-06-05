-   2 minutes

Some of Terraform's core components include:

-   Configuration files. Text-based configuration files allow you to define infrastructure and application configuration. These files end in the .tf or .tf.JSON extension. The files can be in either of the following two formats:
    
    -   Terraform. The Terraform format is more accessible for users to review, in that way making it more user-friendly. It supports comments and is the recommended format for most Terraform files. Terraform files end in .tf
    -   JSON. Machines mainly use the JSON format for creating, modifying, and updating configurations. However, it can also be used by Terraform operators if you prefer. JSON files end in .tf.JSON.
    
    The order of items (variables and resources) defined within the configuration file doesn't matter because Terraform configurations are declarative.
    
-   Terraform CLI. It's a command-line interface from which you run configurations. You can command such as **Terraform apply** and **Terraform plan**, along with many others. A CLI configuration file that configures per-user settings for the CLI is also available. However, this is separate from the CLI infrastructure configuration. In Windows operating system environments, the configuration file is named **terraform.rc** and is stored in the relevant user's %APPDATA% directory. On Linux systems, the file is named **.terraformrc** (note the leading period) and is stored in the home directory of the relevant user.
    
-   Modules. **Modules** are self-contained packages of Terraform configurations that are managed as a group. You use modules to create reusable components in Terraform and for basic code organization. A list of available modules for Azure is available on the [Terraform Registry Modules](https://registry.terraform.io/) webpage.
    
-   Provider. The provider is responsible for understanding API interactions and exposing resources.
    
-   Overrides. Overrides are a way to create configuration files that are loaded last and merged into (rather than appended to) your configuration. You can create overrides to modify Terraform behavior without having to edit the Terraform configuration. They can also be used as temporary modifications that you can make to Terraform configurations without changing the configuration itself.
    
-   Resources. **Resources** are sections of a configuration file that define components of your infrastructure, such as VMs, network resources, containers, dependencies, or DNS records. The resource block creates a resource of the given _TYPE_ (first parameter) and _NAME_ (second parameter). However, the combination of the type and name must be unique. The resource's configuration is then defined and contained within braces.
    
-   Execution plan. You can issue a command in the Terraform CLI to generate an execution plan. The _execution plan_ shows what Terraform will do when a configuration is applied. It enables you to verify changes and potential flag issues. The command for the execution plan is **Terraform plan**.
    
-   Resource graph. Using a resource graph, you can build a dependency graph of all resources. You can then create and modify resources in parallel. It helps provision and configures resources more efficiently.
    

___

## Next unit: Explore Terraform on Azure

[Continue](https://docs.microsoft.com/en-us/learn/modules/implement-terraform/4-explore-terraform-azure/)

Need help? See our [troubleshooting guide](https://docs.microsoft.com/en-us/learn/support/troubleshooting?uid=learn.wwl.implement-terraform.examine-terraform-components&documentId=97e2beef-ff34-cd99-9095-c404d8ab9b69&versionIndependentDocumentId=884eed70-3c9e-762b-68ad-b09383c7bef4&contentPath=%2FMicrosoftDocs%2Flearn-pr%2Fblob%2Flive%2Flearn-pr%2Fwwl-azure%2Fimplement-terraform%2F3-examine-terraform-components.yml&url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Flearn%2Fmodules%2Fimplement-terraform%2F3-examine-terraform-components&author=lumac) or provide specific feedback by [reporting an issue](https://docs.microsoft.com/en-us/learn/support/troubleshooting?uid=learn.wwl.implement-terraform.examine-terraform-components&documentId=97e2beef-ff34-cd99-9095-c404d8ab9b69&versionIndependentDocumentId=884eed70-3c9e-762b-68ad-b09383c7bef4&contentPath=%2FMicrosoftDocs%2Flearn-pr%2Fblob%2Flive%2Flearn-pr%2Fwwl-azure%2Fimplement-terraform%2F3-examine-terraform-components.yml&url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Flearn%2Fmodules%2Fimplement-terraform%2F3-examine-terraform-components&author=lumac#report-feedback).