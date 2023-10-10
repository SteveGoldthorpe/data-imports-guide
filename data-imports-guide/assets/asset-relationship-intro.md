# Introduction

## Overview

The **Asset Relationship** utility provides Hornbill customers with a safe and secure way to manage relationships between assets within Hornbill linked assets in the Service Manager application on the Hornbill platform, as well as dependencies and imapct record in Configuration Manager.

## Download

The utility can be downloaded from [GitHub](https://github.com/hornbill/asset-rel-import/releases/latest). Please ensure to download the latest version of the ZIP archive that is relevant to the architecture of the computer it will be executed and scheduled to run on.

## Installation

- Once downloaded, the ZIP archive for the utility should be extracted into a new folder within the local user profile of the user who will run the tool - whether that be your user profile to manually run the utility or the profile of a service account that will be used to schedule the running of it. For example: `C:\Users\YourUserOrServiceAccountID\Hornbill\asset_rel_import`
- Open conf.json and add in the necessary configration
- Open a Command Line/Terminal as Administrator
- Change Directory to the folder with the executable and config file `C:\Users\YourUserOrYourServiceAccountID\Hornbill\asset_rel_import`
- Run the command : asset_rel_import.exe

## Updates

The utility will self-update when it detects that a newer minor or patch version has been released on GitHub. All of the import tools use [semantic versioning](https://semver.org/), where:

* Major version updates will contain new feature(s), and include breaking changes to the tool configuration 
* Minor version updates will contain new feature(s) and do not include breaking changes to the tool configuration
* Patch version updates will contain bug fixes only 

When there is a Major version update, the utility will not self-update but instead will output a message to the command line & log(s) stating that there is a newer version available to download from GitHub. In this instance, you should download the [latest release from GitHub](https://github.com/hornbill/asset-rel-import/releases/latest), and review the breaking configuration changes against your existing import configuration before implementation. You can also check the [Hornbill Community Forum](https://community.hornbill.com/forum/135-announcements/) for real-time release updates.

## Requirements 

[[INCLUDE https://raw.githubusercontent.com/Hornbill-Docs/hdoc-library/main/hdoc-library/dataimports/requirements.md]]