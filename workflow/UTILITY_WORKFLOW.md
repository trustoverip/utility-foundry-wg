# Utility Project Lifecycle Management

This document provides introductory concepts for  the ToIP Utility Foundry Working Group ("UFWG").

The objective is to help:

* the UFWG members establish a baseline framework for the purpose and scope of the WG.
* interested public identity utilities ("Utility Projects") begin create and operate a Utility.

Specifically, this document provides a catalyst for the discussion of foundational utility concepts to help the working group develop an initial scope for the establishment and lifecycle management of utilities.

This document addresses four topics:

1. What is a Utility?
0. What is a Utility Project”?
0. How would we describe the lifecycle management of a Utility Project?
0. Provide exemplar stories to help visual the lifecycle management workflow concepts.

## Concepts
The UFWG needs to establish some foundational
Ecosystem terms for submission to the ToIP Glossary (See Concepts and Terminology WG). This section provides initial working drafts for several key terms.

### What is a Utility?
In the context of ToIP, a *Public Identity Utility* ("Utility") refers to an organization that maintains the infrastructure for a public identity verification service. While a Utility will generally be publicly accessible for read access, write access may be restricted by the governance model of the Utility. Utilities may be operated by a consortium of private sector entities, government monopolies or a combination of both.

A ToIP Layer 1 Utility is unique because it requires a community of stakeholders to collaborate on the operation and maintenance of the necessary decentralized infrastructure necessary to provide a public identity verification service. A key aspect of the Utilities infrastructure is interoperable with a  ToIP Layer 2 protocol.

[See proposed Glossary Term](https://github.com/trustoverip/concepts-and-terminology-wg/issues/20.)

### What is a Utility Project
A formalized collaborative activity, managed by members of a Utility, that leverages ToIP guidance to establish and maintain a public identity verification service.  [See proposed Glossary Term](https://github.com/trustoverip/concepts-and-terminology-wg/issues/21.)

### Additional Terms for Utility Newbies
* **Decentralized identifiers (DID)**: A W3C Specification for unique identifiers.
* **Schema**: A set of attribute data types and formats that can be part of a credential claim. Eg., the fields within a passport/license document.
* **Credential Definition**: A public statement by the issuer that they will publish credentials agains a specific schema(s).
* **Credential**: An issuer-specific data fields that can come from one/more schemas and defines the proofs sent by the holder. Eg., proof of education, age, nationality, etc.
* **Verifiable Credential (vCred)**: A W3C Specification for Verifiable Credentials.
Revocation List: A registry that helps identify the revocation of a private DID of a holder
* **DID v. Verifiable Credential**:  DIDs create the cryptographic trust between two entities whereas the verifiable credential creates the business trust across the same.



## Utility Foundry Workflow
The UFWG needs to publish guidance for the lifecycle management of Utility Projects. This guidance must consider:

* Utility Project Requirements
* Lifecycle Management of a Utility Project
* Decision Tree Guidance for each lifecycle swim-lane

The following workflow diagram depicts the conceptual swim-lanes of a lifecycle management process for the establishment and maintenance of a Utility Project.

The objective of the UFWG is to expanded each swim-lane into a decision-tree for a variety of process questions/answers.

![swimlanes](./img/workflow-swimlanes.png)

### Learn
Before prospective stakeholders embark on the creation of a Utility Project, they must first gather some fundamental knowledge about concepts, processes and challenges.

Such education based activity will be an ongoing activity since stakeholders within the Utility Project will come and go.

Initially, key decision topics will include:

1. Why is a *Public Identity Utility* needed by the stakeholders?
2. Why a legal entity structure is required for a public utility?
3. What are the differences between legal entity creation approaches (i.e.: Linux Foundation Non-Profit, NGO)
4. What regulatory compliance, legal, risk mitigation decisions will beed to be considered?
5. What are the key progress factors that will trigger a decision to convene?

### Convene
One or more prospective stakeholders will typically emerge as the early convener(s) of a Utility Project. The Convener will help organize an initial set of prospective stakeholders. This group will gather to address some important topics:

1. Why do we need a Utility?
2. What is unique about the desired Utility?
3. Who will participate?
4. What are the common stakeholder motivators?
5. What are the common stakeholder requirements?

### Define
Once the prospective stakeholders agree to proceed, the next phase of the process will focus on critical elements such as:

* Articulating the scope of management and how the Utility Project will be governed.
* Making decisions about DID Methods and ledger technology
* Documenting sustainability requirements
* Outlining criteria for the selection of a Utility Service Provider

### Create
Now the hard work begins! The legal entity that will be the public identity utility needs to be created. This can be done under the umbrella of the Linux Foundation or under the non-profit or  non-government organization (NGO) requirements of a country or region. This new entity will require a governance framework along with any additional legal instruments (contracts) for participating members. Templates and guidance from the ToIP GFWG will be used to aid this activity. The templates will also be used to formalize policies for Utility write-access and budgetary considerations.

### Implement
A Utility is a key component to ToIP infrastructure. As such, an implementation plan will be established and executed to stand up the Utility. This plan will include:

1. Publishing a governance framework
2. Onboarding members
3. Selecting a USP
4. Aiding members with the selection of node hosting providers
5. Establishing technical project

### Maintain
As a public service, the Utility must be monitored for performance and reliability. The stakeholders will need to:

* Accommodate the operation of a number of ledger environments (dev, test, production)
* Run membership campaigns
* Monitor USP performance

## Examples
Our **Utility Foundry Workflow** is a *work-in-progress*. Each workflow step will eventually be expanded into decision tree guidelines. Before we tackle this activity,  further modeling by example should be undertaken by UFWG members. Specifically, we need to:

* Request that volunteers submit example utility  project stories to the ```./stories``` folder using the ```./stories/_stories_template.md```.
* Solicit feedback on proposed workflow swim-lanes and definitions
* Expand on the decision points for swim-lane?

### Stories
As the UFWG refines the * Utility Foundry Workflow Model*, sample descriptive experiences or hypothetical cases will be leveraged by the UFWG to validate our workflow model.

1. [Bedrock Business Utility](./stories/bbu.md)

### Utility Projects
Refer to the list of [Utility Projects](../UTILITY_LIST.md).
