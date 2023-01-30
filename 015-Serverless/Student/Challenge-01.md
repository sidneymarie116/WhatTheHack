# Challenge 01 - Setup

**[Home](../README.md)** - [Next Challenge >](./Challenge-02.md)

## Pre-requisites

- Your laptop: A GME device.
- Access to the shared Azure subscription [APPS_CloudTouch_DEV](https://portal.azure.com/#@EMCloudAD.onmicrosoft.com/resource/subscriptions/d5ee6e04-0498-4b40-963e-8bcf6bcaf680/overview). You and your team should be given **contributor** RBAC access to a single resource group within this subscription, the name/link of which be shared by your coach. Your resource group name should look something like _serverless-sessionX-rg_.

## Introduction

The first challenge is to setup an environment that will help you build the Tollbooth application and deploy it locally. We need to make sure everything is working before bringing it into Azure.

## Description

Set up your *local* environment:

- Visual Studio or Visual Studio Code
    - Azure development workload for Visual Studio 2022 or 2019
    - Azure Functions and Azure Functions Core Tools
    - [Node.js 8+](https://nodejs.org/en/download/): Install latest long-term support (LTS) runtime environment for local workstation development. A package manager is also required. Node.js installs NPM in the 8.x version. The Azure SDK generally requires a minimum version of Node.js of 8.x. Azure hosting services, such as Azure App service, provides runtimes with more recent versions of Node.js. If you target a minimum of 8.x for local and remove development, your code should run successfully.
    - .NET 6 SDK
    - [VS Code Todo Tree Extension](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
    - Any extentions required by your language of choice

*To setup Azure Functions on Visual Studio Code, [follow this guide.](https://docs.microsoft.com/en-us/azure/azure-functions/functions-develop-vs-code?tabs=csharp)*
 
Your coach will provide you with a `Resources.zip` file containing the source code and supporting files for this hack.  Uncompress the file on your local workstation.

To support this event, we are making the [`Resources.zip`](https://aka.ms/serverless-september/wth/resources) file available for download [here](https://aka.ms/serverless-september/wth/resources).

## Success Criteria

1. Verify your Visual Studio or Visual Studio Code installation has all of the necessary developer tools installed and available.
1. Verify you have the following folders locally wherever you unpacked the `Resources.zip` file:
    - `/Tollbooth`
    - `/license plates`
