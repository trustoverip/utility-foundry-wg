## Utility Case Study

| Story Name | Case Study Type |
| --- | --- |
| Sovrin Network | Actual|

### Background Context
Evernym Inc. was created to fill a need in the SSI community with a goal to provide a network upon which SSI could be provided to the world. They created a new Hyperledger project named INDY and proceeded to build the code and gathered community support to help them. They soon realized that as a "for-profit" company, that would be unable to provide a fully decentralized network on which to run their solution, so the Sovrin Foundation was born.
The Sovrin Foundation's main goal is "Identity For All" and thus many of the concepts and other ideas presented here use that concept as their guiding force.

### Pertinent Concepts
* Identity for All: As a non-profit organization, the Sovrin Foundation was built with the idea that those who could afford to pay for Identity would be charged a small fee, while those who could not would be able to have SSI available to them via grants and other means.
* Governance: As a decentralized public service provider, the Utility must be governed with a transparent governing model.
* Sustainability: The new concept of a Public Utility Ledger was not expected to be an overnight success, so donations would be needed to keep it running for the first 5+ years. After that, ledger payments (via tokens) were planned and designed as the means for supporting the Sovrin Foundation including the staff and the Sovrin Networks. An economic advisement board was created to manage the donations and the tokens.
 
### Stakeholders / Persona
The following subjects are participants in the story:

* Nathan George - Sovrin CTO
* Mike Bailey - Evernym Network Operations
* Drummond Reed - Evernym Governance Expert
* >enter content here

### User Stories
1. >enter content here
2. 

### Utility Foundry Workflow

![swimlanes](../img/workflow-swimlanes.png)

### Learn
* >enter content here

### Convene
>enter content here

### Define
To begin with, volunteers were recruited to discuss and forrmulate the early versions of the [Sovrin Governance Framework](https://sovrin.org/library/sovrin-governance-framework/). The framework has undergone many many hours of review and enhancement to get where it is today. Some of the core items defining the Sovrin Networks are: 
* Will use Linux Foundation open source project models.
* Will develop and use Hyperledger Indy as the ledger technology.
* Will comply with GDPA and other similar governing mandates so that Sovrin can be a globally acceptable SSI Network.
* >enter content here

### Create
* >enter content here

### Implement
What follows is a high level list of steps that Sovrin used to implement their MainNet and other networks. 
* Held many meetings and discussions to determine desired Governance.
* Wrote Governance documents.
* Governance documents reviewed and ratified by community member committee.
* Recruited Trustees. Created the Sovrin Board of Trustees.
* Trustees created their DID's using instructions given by Mike Bailey during a Trustee Training meeting.
* Recruited Stewards.
* Genesis Stewards installed their nodes using instructions sent by Mike Bailey.
* Sovrin packaged builds of Indy were used to install the nodes.
* A MainNet instantiation meeting was held and the mainnet was started up.
* The DemoNet was later added as a place to try things out before moving to production.
* The BuilderNet was later added as an initial place to try out builds, and for developers to work on pre-demo apps. The DemoNet was renamed to StagingNet.
* After the Auth_Rules feature was finalized, added customized Auth_Rules to the ledgers using the instructions in the Auth_Rules Walkthrough and other files found in the [Auth_Rules](https://drive.google.com/drive/folders/1xtZxSHhZ584B6NtASdfQEcoai9w6CyhN?usp=sharing) directory. The Auth_Rules were added to BuilderNet and StagingNet for testing before being added to the MainNet.
* Added a Transaction Author Agreement in a similar manner as the Auth_Rules were added. Instructions for adding this are in the "TAA for CLI walkthrough" in the [TAA folder](https://drive.google.com/drive/folders/1rPxNgn12_Pv2U7EzV1FYqzbpI867NYE1?usp=sharing).
* Added test-token functionality to the BuilderNet and StagingNet using the libsovtoken plugin. Token functionality was tested and shown to be functional on those networks, but has not yet been approved for the MainNet.

### Maintain
Maintaining an Indy network includes the following types of actions:
* Adding new nodes (onboarding new Stewards)
* Network software upgrades
* Monitoring
* Debugging and resolving issues

Here is what Sovrin has done so far for each of those items:

*New Nodes*
After a new Steward has signed all of the appropriate documents (Steward Agreements), they are asked to follow the instructions in the Validator Preparation Guide to prep their node, then a zoom call with the administrator completed the onboarding. The preparation guide also has instructions in it for moving a node between networks when that is needed.
 
*Upgrades*
Determined an upgrade schedule and used as a guide the upgrade procedures and documents found in the [Network Upgrades](https://drive.google.com/drive/folders/1vsOuN_kkcdwDjsDMuEIEedz7fGDh0aTE?usp=sharing) folder.

*Monitoring*
Initially a manual monitoring [script](https://github.com/sovrin-foundation/community-tools/blob/master/monitornodes.py) was used, then later a pull request was submitted to the Indy Node Monitor [github repo](https://github.com/hyperledger/indy-node-monitor) containing a graphical monitoring tool derived from "validator-info" information. A public demo of that contribution can be found [here](https://indymonitor.indiciotech.io). The community is in the process of improving that PR along with the Indy Node Monitoring tool for ease of use by any Indy project.
indyscan.io was built and a public release of that project is available to assist with monitoring and maintenance of the Sovrin Networks.

*Repair*
The [Tips and Tricks](https://docs.google.com/document/d/1YRoviyrF1FXmnHbZlfoqxRohiuXzzZGtJNEK6FtdWTA) document has been created and used to diagnose and resolve common issues that occur during onboarding and day-to-day operation. Jira tickets can be created on the [SN Board](https://sovrin.atlassian.net/secure/RapidBoard.jspa?rapidView=9&useStoredSettings=true) when defects are found. Volunteers are monitoring Jira and fixing the major issues.
