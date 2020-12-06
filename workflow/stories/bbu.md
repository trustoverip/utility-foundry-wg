## Utility Case Study

| Story Name | Case Study Type |
| --- | --- |
| Bedrock Business Utility | Actual|

>DISCLAIMER: This document represents a hi-level summation of actual activity. A detailed synopsis of activities will be required to understand actual workflow decisions.

### Background Context
The [Bedrock Consortium](https://bedrockconsortium.org/) is a collection of international private sector companies that operate the [Bedrock Business Utility (BBU)](http://bbu.bedrockconsortium.org/), an independent self-governed non-profit legal entity that serves as a public identity utility and operates as a self-sustainable directed fund project under The Linux Foundation.

The BBU is intended to serve organizations that desire to participate in digital trust ecosystems and require an enterprise grade governance framework that will:

* Enforce permissioned-writes with contractual instruments that will conform to privacy regulations such as GDPR
* Maintain financial sustainability of the consortium without the use of cryptographic tokens
* Establish a governing board so that no single organization owns the [public identity utility](https://bedrock-consortium.github.io/bbu-gf/gf_info/glossary/#public-identity-utility).
* Require adherence to specified open standards and protocols

### Pertinent Concepts

* **Self-sustainability**: Leveraging lessons learned from the [Sovrin Foundation](http://sovrin.org), success is dependent on the establishment of a business model that is not rooted in philanthropic supported infrastructure.
* **Self-governed**: As a decentralized public service provider, the public identity utility must be governed as a legal entity with a transparent governing model.

### Stakeholders / Persona
The following subjects are stakeholders to story:

* Dan (Founder/Convener): Digital Identity leader at a large technology company.
* Christine (Steward): Digital Identity leader at a large consulting firm.

### User Stories
1. Dan and Christine share common business needs for a public identity utility and decide to collaboratively explore the viability of a Utility.
2. Dan runs an exploratory campaign with industry competitors and clients to identify prospective stakeholders that are willing to collaborate in a consortium.
3. Dan convenes a working group, represented by sponsoring businesses, to establish a governance framework.
4. The Working Group runs a RFP Process to help validate budgetary requirements and the selection of a [Utility Service Provider](https://bedrock-consortium.github.io/bbu-gf/gf_info/glossary/#utility-service-provider) ("USP").
5. The Working Group collaborates with the Linux Foundation ("LF")  on the establishment of a LF Governance Network Project under the new [LF Governancewnce Network Model](https://www.linuxfoundation.org/blog/2020/10/introducing-the-open-governance-network-model/).
6. The Working Group formalizes the launch of a Utility.

### Utility Foundry Workflow

![swimlanes](../img/workflow-swimlanes.png)

### Learn

* While Dan and Christine had an operational understanding of how a Utility would work, they needed to educate prospective stakeholders.
* Clients of Dan and Christine shared a common need - a trusted and enterprise reliable utility service for identify verification that was easy to maintain and use. They desired a minimum viable utility ("MVU")
* The employers of Dan and Christine did not desire to own and operate the Utility, they desired a non-profit and open solution.
4. Both stakeholder companies were deeply concerned about GDPR/CCPA privacy risks associated with participation in such a Utility from an infrastructure perspective.
5. Dan and Christine agreed the requirements for convening a project would be to get 5-10 companies to provide (a) an executive sponsor willing to be a board member if the Utility materialized; (b) a working group resource willing to work on the creation of a governance framework.

### Convene
The Bedrock Consortium was informally formed with representatives from nine (9) prospective companies. The identification of these prospective nine required numerous emails and educational sessions to establish interest and identify common requirements.

The Bedrock Consortium established a Governance Framework Working Group ("GFWG") with Dan as the Convener.

### Define
Using the [Sovrin Governance Framework](https://sovrin.org/library/sovrin-governance-framework/) as a model, the GFWG collaborated on the:

* Creation of a new governance framework online that can be easily navigated and maintained via GitHub
* Articulation of scope of management and how the Utility Project will be governed using proven Linux Foundation open source project models.
* Establishing a set of foundational project decisions:

    1. Design Principles
    2. Technology Stack
    3. Accepted the contribution of a BBU specific DID Method (```did:bbu```)
        * [Demo Resolver](https://resolver.identity.foundation)
        * [DID Method Driver](TBD): See [bedrock-consortium/TSC Issue #3](https://github.com/bedrock-consortium/TSC/issues/3).

    *Note*: As the GFWG progressed so did the open source community. The maturation of parallel effort aided some  architectural decisions: (i) Saturn-V TIP with emphasis on vendor interop testing; (ii) Trends associated with a [network of Hyperledger Indy public identity utilities](https://github.com/trustoverip/utility-foundry-wg/blob/master/UTILITY_LIST.md#utility-directory) (iii) [Indy DID Method standardization activity](https://wiki.hyperledger.org/display/indy/Indy+DID+Method+Specification)

* Modeling of sustainable budget requirements for a MVU of 25 Stewards growing no larger than 60 Stewards.
* Outlining criteria for the selection of a Utility Service Provider.

### Create
* Ran a RFP Process based on the criteria for the selection of a Utility Service Provider.
* Published the [BBU Governance Framework](http://bbu.bedrockconsortium.org/) (a living document)
* [Formalized the Utility via a LF Soft-Launch](https://bedrockconsortium.org/blog/2020/12/01/this-is-a-blog-post/):
    * Created a *Briefing Package* to be used to solicit Bedrock Consortium members.
    * Ran exploratory briefing sessions
    * Created the Bedrock Technical Project


### Implement
Execution of an implementation plan is dependent on achieving a minimum viable membership of 36 members.

### Maintain
TBD
