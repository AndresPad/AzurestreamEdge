# Azure Percept Deployment Manifests

This folder contains three JSON Deplyment configuration files.

* The one labeled `azure-percept-default-deployment.json` can be used
  to restore your Azure Percept DK's IoT Edge environment to its default state for any OS version you have on your
  Percept DK. This configuration is pinned to a specific version of each module, and will not change. These
  modules will be old and need updating therefore.
* The one labeled `azure-percept-default-deployment-2112.json` can be used to restore your Azure Percept DK's IoT Edge environment
  to its default state for any OS version **starting with November Service Release 2111** ([see here](https://docs.microsoft.com/en-us/azure/azure-percept/software-releases-usb-cable-updates#full-list-of-releases)). This configuration will be updated anytime there are
  updates to the IoT modules on the device.
* The one labeled `azure-percept-sql-edge-deployment.json` can be used to restore your Azure Percept DK's IoT Edge environment
  to a state where you have SQL Edge running on the Azure Percept Device.
