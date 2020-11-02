## Utility Case Study

| Story Name | Case Study Type |
| --- | --- |
| Sovrin Network | Actual|

### Background Context
Evernym Inc. was created to fill a need in the SSI community with a goal to provide a network upon which SSI could be provided to the world. They created a new Hyperledger project named INDY and proceeded to build the code and gathered community support to help them. They soon realized that as a "for-profit" company, that would be unable to provide a fully decentralized network on which to run their solution, so the Sovrin Foundation was born.
The Sovrin Foundation's main goal is "Identity For All" and thus many of the concepts and other ideas presented here use that concept as their guiding force.
 
### Stakeholders / Persona
The following subjects are participants in the story:

* Stephen Curran - Board of Trustees
* Drummond Reed - Evernym Governance Expert


### User Stories
1. >enter content here
2. 

## Utility Foundry Workflow

![swimlanes](../img/workflow-swimlanes.png)

### 1. Learn
* >enter content here

### 2. Convene

2.1  Why do we need a Utility?
Identity for All: As a non-profit organization, the Sovrin Foundation was built with the idea that those who could afford to pay for Identity would be charged a small fee, while those who could not would be able to have SSI available to them via grants and other means.

2.2  Who will participate?
As a decentralized public service provider, the Utility must be governed with a transparent governing model by community members.


### 3. Define
To begin with, volunteers were recruited to discuss and formulate the early versions of the Sovrin Governance Framework. The framework has undergone many many hours of review and enhancement to get where it is today. Some of the core items defining the Sovrin Networks are:

* Will use Linux Foundation open source project models.
* Will develop and use Hyperledger Indy as the ledger technology.
* Will run instances of Indy software, will use a non-for-profit to operate the network of nodes.
* Because of the choice of Hyperledger Indy and the respective network consensus model (Plenum BFT), up to 25 partners will be required to run nodes and validate transactions. 25 is the approximate number of nodes that optimize performance, decentralization and robustness.
* Will comply with GDPR and other similar governing mandates so that Sovrin can be a globally acceptable SSI Network.
* Sustainability: The new concept of a Public Utility Ledger was not expected to be an overnight success, so donations would be needed to keep it running for the first 5+ years. After that, ledger payments (via tokens) were planned and designed as the means for supporting the Sovrin Foundation including the staff and the Sovrin Networks. An economic advisory board was created to manage the donations and the tokens.


### 4. Create

* Sovrin is set up as a Utah non-for-profit.
* Originally Sovrin had a dozen partners in the community, over time they added more Stewards as required.


### 5. Implement
What follows is a high level list of steps that Sovrin used to implement their MainNet and other networks.

* Held many meetings and discussions to determine desired Governance.
* Wrote Governance documents.
* Governance documents reviewed and ratified by the community member committee.
* Recruited Trustees. Created the Sovrin Board of Trustees.
* Trustees created their DID's using instructions given by Mike Bailey during a Trustee Training meeting.
* Recruited Stewards.
* Genesis Stewards installed their nodes using instructions sent by Mike Bailey.
* Sovrin packaged builds of Indy were used to install the nodes.
* A MainNet instantiation meeting was held and the mainnet was started up.
* The DemoNet was later added as a place to try things out before moving to production.
* The BuilderNet was later added as an initial place to try out builds, and for developers to work on pre-demo apps. The DemoNet was renamed to StagingNet.
* After the Auth_Rules feature was finalized, added customized Auth_Rules to the ledgers using the instructions in the Auth_Rules Walkthrough and other files found in the Auth_Rules directory. The Auth_Rules were added to BuilderNet and StagingNet for testing before being added to the MainNet.
* Added a Transaction Author Agreement in a similar manner as the Auth_Rules were added. Instructions for adding this are in the "TAA for CLI walkthrough" in the TAA folder.
* Added test-token functionality to the BuilderNet and StagingNet using the libsovtoken plugin. Token functionality was tested and shown to be functional on those networks, but has not yet been approved for the MainNet.


### 6. Maintain
Maintaining an Indy network includes the following types of actions:

1. Adding new nodes (onboarding new Stewards)
2. Network software upgrades
3. Monitoring
4. Debugging and resolving issues

Here is what Sovrin has done so far for each of those items:

#### 6.1  Adding New Nodes 
After a new Steward has signed all of the appropriate documents (Steward Agreements), they are asked to follow the instructions in the Validator Preparation Guide to prep their node, then a zoom call with the administrator completes the onboarding. The preparation guide also has instructions in it for moving a node between networks when that is needed.

#### 6.2  Network Software Upgrades 
Determined an upgrade schedule and used as a guide the upgrade procedures and documents found in the Network Upgrades folder.
As of October 2020, the network has gone through two upgrades, both going smoothly. The MainNet requires the signatures of three trustees for any upgrade to occur.

#### 6.3  Monitoring 
Initially a manual monitoring script was used, then later a pull request was submitted to the Indy Node Monitor github repo containing a graphical monitoring tool derived from "validator-info" information. A public demo of that contribution can be found here. The community is in the process of improving that PR along with the Indy Node Monitoring tool for ease of use by any Indy project. indyscan.io was built and a public release of that project is available to assist with monitoring and maintenance of the Sovrin Networks.
As of October 2020, The Sovrin Foundation is improving the monitoring of the network and strengthening operational processes by redefining performance metrics and network support strategy. Although some nodes do go offline from time to time, the network has yet to have an outage. The Foundation is also looking to better track and identify the root cause of node failures.

#### 6.4  Debugging and Resolving Issues 

The Tips and Tricks document has been created and used to diagnose and resolve common issues that occur during onboarding and day-to-day operation. Jira tickets can be created on the SN Board when defects are found. Volunteers are monitoring Jira and fixing the major issues.

### 7. Additional Considerations

#### 7.1  Influencing Standards and Technology Roadmaps
Because the Sovrin Foundation relies on community defined standards (W3C, DIF, ToIP) and open source software (Indy, Aries, Ursa), they need to ensure they are aligned with the contributions and the roadmaps of those respective areas. 

#### 7.2  Sustainability / Business Viability
The Foundation brings together multiple working groups and governance frameworks on things such as Guardianship, Fintech, IoT Devices and more.

As of October 2020, the only current cost the Foundation incurs is to pay network operators. All other paid staff were let go in March 2020. The Board of Directors of the Foundation is dealing with debt previously incurred and putting the pieces in place to ensure the network remains stable and the business model evolves for long term sustainability.
