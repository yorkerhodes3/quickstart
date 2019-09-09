# Quickstarts for Azure Blockchain

This repository holds information and links to resources for how to get started with the services and tooling that Microsoft has created to assist in blockchain development and deployment.

# Solution components

When building blockchain solutions, various components and technologies can be used to compose the entire solution, some of which will be creating software components, while others involve provisioning and configuring services.  These components and use are detailed below.

## Azure Blockchain Service

This is a managed ledger service that can be used to create a network, currently using Quorum, in a few minutes with no on-premises infrastructure.  Additionally, this private blockchain network can be scaled up (adding nodes) as well as extended to other blockchain participants, in other organizations/businesses.

[Documentation and Getting Started](https://docs.microsoft.com/en-us/azure/blockchain/service/)

## Azure Blockchain Workbench

This is a group of Azure services and software that will assist in creating Proof of Concepts using blockchain technology, including the entire stack needed for a fully functioning application.  The target audience are those that would like to prototype an application, including not only the blockchain ledger, but also components such as delegated transaction signing, event listening, common api for web/mobile apps, and offchain storage.  This is entirely cloud based and requires no on-premises infrastructure.

[Documentation and Getting Started](https://docs.microsoft.com/en-us/azure/blockchain/workbench/)

## Blockchain Development Kit

This is a collection of software, which showcase 4 primary areas when building applications.

-   [Connect](https://github.com/Azure-Samples/blockchain-devkit/tree/master/connect) - Connect various data producers and consumers to or from the blockchain
-   [Integrate](https://github.com/Azure-Samples/blockchain-devkit/tree/master/integrate) - Integrate legacy tools, systems and protocols
-   [Accelerators](https://github.com/Azure-Samples/blockchain-devkit/tree/master/accelerators) - Deep dive into End-to-End examples, or solutions to common patterns.
-   [DevOps for smart contracts](https://github.com/Azure-Samples/blockchain-devkit/tree/master/devops) - Bring traditional DevOps practices into a distributed application environment

[Full repository and examples](https://aka.ms/bcdevkit)

## VS Code Development  (Azure Blockchain Development Kit for Ethereum)

This is an extension for VS Code that is targetted at developers that looking to:

- Author Ethereum based smart contracts (Solidity), with text highlighting, helpers, etc.
- Deploy Ethereum based smart contracts (Solidity) to both private and public networks.
- Debug Ethereum based smart contracts (Solidity) directly in the IDE.
- Interact with the contracts post deployment.
- Generate Logic App wrappers to surface smart contracts to developers with low to no code.

[Visual Studio Marketplace download](https://marketplace.visualstudio.com/items?itemName=AzBlockchain.azure-blockchain)

## Azure templates for many chains

The Azure marketplace has a full category for blockchain infrastructure and solutions in a single click model.  All cloud based and parameterized for customization.

[Azure Marketplace for Blockchain](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/category/blockchain?page=1)

## Community Samples

Complete solutions driven primary by the community with input from Microsoft Engineering team. These samples have complete instructions for deployment.

[Community Samples](https://github.com/Azure-Samples/bc-community-samples)