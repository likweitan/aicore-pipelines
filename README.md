# Quick Start for Your First AI Project Using SAP AI Core

## Prerequisites

- A BTP global account
If you are an SAP Developer or SAP employee, please refer to the following links ( for internal SAP stakeholders only ) -
How to create a BTP Account (internal)
SAP AI Core
If you are an external developer or a customer or a partner kindly refer to this tutorial
- Have Postman, Python (AI Libraries) or SAP AI Launchpad set up. You can set any of these up using [this tutorial](https://developers.sap.com/tutorials/ai-core-setup.html/#)

You will create an AI workflow for your Hello, World! workflow, and connect and execute it in your SAP AI Core instance. You will see that workflows between GitHub and SAP AI Core can be auto synced, and it is possible to use this workflow after subscription, to connect to your actual AI code.

The terms “executable” and “workflow” can be used interchangeably to refer to the YAML files, introduced in this tutorial.

Please find downloadable sample notebooks for the tutorials : . Note that these tutorials are for demonstration purposes only and should not be used in production environments. To execute them properly, you’ll need to set up your own S3 bucket or provision services from BTP, including an AI Core with a standard plan for narrow AI and an extended plan for GenAI HUB. Ensure you input the service keys of these services into the relevant cells of the [notebook](https://github.com/SAP-samples/ai-core-samples/blob/main/02_ai_core/tutorials/01_create_your_first_machine_learning_project_using_sap_ai_core/01_02_quick_start_for_your_first_ai_project_using_ai_core/quick_start_helloworld.ipynb).