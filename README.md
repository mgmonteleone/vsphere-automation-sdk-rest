# VMware vSphere Automation SDK for REST

## Table of Contents
- [Abstract](#abstract)
- [Intended Audience](#intended-audience)
- [What’s in the SDK?](#whats-in-the-sdk)
- [Quick Start Guide for JavaScript Samples Using NodeJS](#quick-start-guide-for-javascript-samples-using-nodejs)
  - [Requirements](#requirements)
  - [Samples Setup](#samples-setup)
  - [Running JavaScript Samples](#running-javascript-samples)
- [Submitting samples](#submitting-samples)
  - [Required Information](#required-information)
  - [Suggested Information](#suggested-information)
  - [Contribution Process](#contribution-process)
  - [Code Style](#code-style)
- [Resource Maintenance](#resource-maintenance)
  - [Maintenance Ownership](#maintenance-ownership)
  - [Filing Issues](#filing-issues)
  - [Resolving Issues](#resolving-issues)
  - [VMware Sample Exchange](#vmware-sample-exchange)
- [Repository Administrator Resources](#repository-administrator-resources)
  - [Board Members](#board-members)
  - [Approval of Additions](#approval-of-additions)
- [VMware Resources](#vmware-resources)

## Abstract
The VMware vSphere Automation SDK for REST enables programmatic access to vSphere. The SDK includes JavaScript samples to demonstrate how to invoke APIs for Tagging and Virtual Machine Operations as well as [Postman](https://www.getpostman.com/) examples.

## Supported vCenter Releases:

All samples support vCenter 6.5. Tagging samples also support vCenter 6.0.

## Intended Audience

The VMware vSphere Automation SDK for REST is intended for the following audiences:

* Developers who create clients that connect to the vAPI endpoint to use VMware vSphere Automation SDK for REST Services.

## What’s in the SDK?

The VMware vSphere Automation SDK for REST provides a client SDK that contains samples that demonstrate how to use the vSphere Automation REST API and sample code. The following table contains a brief description of the contents of the vSphere Automation SDK for REST.

Directory structure (under VMware-vSphere-Automation-SDK-REST):

|Directory	                      |Contents                                                                            |
|---------------------------------|------------------------------------------------------------------------------------|
|[samples/javascript/tagging](samples/javascript/tagging)|	Javascript samples that demonstrate how to construct REST API requests for Tagging.|
|[samples/javascript/vcenter](samples/javascript/vcenter)|	Javascript samples that demonstrate how to construct REST API requests for Virtual Machine Operations |
|[samples/postman](samples/postman)	          | Postman samples that demonstrate how to construct REST API requests for Virtual Machine Operations. |

## Quick Start Guide for JavaScript Samples Using NodeJS
These steps will walk you through getting the NodeJS-based JavaScript samples running.

### Requirements
* [Node 4+](https://nodejs.org/)
* [NPM 3+](https://www.npmjs.com/)

If you don't already have NodeJS installed you will need to download and install it from [here](https://nodejs.org/en/). Additionally, the samples leverage various Open Source NodeJS which must be installed using the Node Package Manager (npm) which you can install from [here](https://www.npmjs.com/).

### Samples Setup
To run the JavaScript samples you must first install the required node packages referenced in javascript/vcenter/package.json using *npm* file as follows:

    cd samples/javascript/vcenter
    npm install

### Running JavaScript Samples
For a complete list of included samples refer to the "scripts" section of the javascript/vcenter/package.json file. To run a sample use npm as follows:

    npm run <sample_name>

Ex:

    npm run host-connect

For a list of samples run:

    npm run

## Submitting samples
### Required Information
The following information must be included in the README.md or in the sample docstring in case a README already exists in same folder.
* Author Name
  * This can include full name, email address or other identifiable piece of information that would allow interested parties to contact author with questions.
* Date
  * Date the sample was originally written
* Minimal/High Level Description
  * What does the sample do?
* Any KNOWN limitations or dependencies

### Suggested Information
The following information should be included when possible. Inclusion of information provides valuable information to consumers of the resource.
* vSphere version against which the sample was developed/tested
* SDK version against which the sample was developed/tested
* Additional Version information for any dependencies against which the sample was developed/tested

### Contribution Process

* Follow the [GitHub process](https://help.github.com/articles/fork-a-repo)
  * Please use one branch per sample or change-set
  * Please use one commit and pull request per sample
  * Please post the sample output along with the pull request
  * If you include a license with your sample, use the project license

## Resource Maintenance
### Maintenance Ownership
Ownership of any and all submitted samples are maintained by the submitter.

### Filing Issues
Any bugs or other issues should be filed within GitHub by way of the repository’s Issue Tracker.

### Resolving Issues
Any community member can resolve issues within the repository, however only the board member can approve the update. Once approved, assuming the resolution involves a pull request, only a board member will be able to merge and close the request.

### VMware Sample Exchange
It is highly recommended to add any and all submitted samples to the VMware Sample Exchange:  <https://code.vmware.com/samples>

Sample Exchange can be allowed to access your GitHub resources, by way of a linking process, where they can be indexed and searched by the community. There are VMware social media accounts which will advertise resources posted to the site and there's no additional accounts needed, as the VMware Sample Exchange uses MyVMware credentials.     

## Repository Administrator Resources
### Board Members

Board members are volunteers from the SDK community and VMware staff members, board members are not held responsible for any issues which may occur from running of samples from this repository.

Members:
* Steve Trefethen (VMware)
* Alan Renouf (VMware)

### Approval of Additions
Items added to the repository, including items from the Board members, require 2 votes from the board members before being added to the repository. The approving members will have ideally downloaded and tested the item. When two “Approved for Merge” comments are added from board members, the pull can then be committed to the repository.

## VMware Resources

* [Getting Started Blog post](https://blogs.vmware.com/code/2017/02/02/getting-started-vsphere-automation-sdk-rest/)
* [VMware Code](https://code.vmware.com/home)
* [VMware Developer Community](https://communities.vmware.com/community/vmtn/developer)
* VMware vSphere [REST API Reference documentation](https://vdc-repo.vmware.com/vmwb-repository/dcr-public/1cd28284-3b72-4885-9e31-d1c6d9e26686/9a0dbc46-b15f-47cd-af1d-dc64615b03df/doc/index.html).
* [VMware REST forum](https://code.vmware.com/forums/7506/vsphere-automation-sdk-for-rest)