## Utility Case Study

| Story Name | Case Study Type |
| --- | --- |
| KOB Public Identity Utility | Actual |



### Background Context

The KochiOrgBook Public Identity Utility(KOBPIU) is a community first initiative driven by Wipro whose primary focus is to provide a cryptographically verifiable digital identity for the citizens and organisations/associations residing in the city of Kochi, where these organisations/associations/citizens can present these digital identities in place of paper credentials whenever required.In the current scenario, it requires a lot of effort, time and documents to prove one's identity or eligibility. The utility aims to cut down this red tape by providing these digital identities in the most efficient and easiestt way possible.

The desired characteristics of the utility are,
- Consent management
- Zero-Knoweldge-Proofs(ZKP)
- Privacy
- Security

This initiative is driven with the help of -

- Managed Service Providers - help in conceptualizing and implementing the use cases for this utility.
- Community of developers - design and build use cases for the utility through crowd sourcing initiatives
- Associations - define and validate implementation of use case

The KOBPIU is intended to serve organizations that desire to participate in digital trust ecosystems and require an enterprise grade governance framework. The framework will:

- Enforce permissioned-writes with contractual instruments that will conform to privacy regulations such as GDPR
- Maintain financial sustainability of the consortium members without the use of cryptographic tokens
- Establish a governing board so that no single organization owns the Identity Utility Network
- Require adherence to specified open standards and protocols

Our mission is "Internet scale digital trust with close to 1 million digital credentials on the network".


### Pertinent Concepts

* Jurisdiction: The public identity utility will be focused in a particular jurisdiction, the city of Kochi.
* Low cost: The utility aims to bring down the cost to be incurred by the stake holders for hosting a node to the possible minimum
* Community cloud: The utility will also have a community cloud where service providers can host their services and other participants can avail them. 
* Service Providers - The service providers will define and validate implementation of digital identity services as well as host their services in the community cloud.


### Stakeholders / Persona

The following subjects are participants in the story:

- Association of Medical practitioners: Indian Medical Association (Kochi Chapter)
- Association of Lawyers: Bar Council (Kochi Chapter)
- Association of Real Estate Developers: CREDAI (Kochi Chapter)
- Association of Technical Universities
- Association of Retailers: Retailers Association of India (Kochi Chapter)
- Association of CBSE schools: Kerala CBSE School Management Association (Kochi Chapter)
- Association of Driving Schools
- Residential Associations

### User Stories

Some of the possible use cases are given below,

1. **Verification services**

    Some of the verification services are,

    - Email verification
    - Phone number verification
    - Address verification

    Phone number or Email-id are the most commonly shared credential in the digital world. Even these are misused by individuals for various illegal activities. The purpose of these service is to verify one's ownership upon their credentials.

    This use case is focused on offering basic verification services like email verification, phone verification services etc. which could then be bundled along with other services for offering customized digital identity services on KOB network.

2. **Engaging and availing services from Doctors based on their specializations and qualifications**
   
   In the current scenario, it will be difficult for a citizen of Kochi to find a suitable doctor for his/her needs. Usually they will have to go to reputed hospitals or will have to ask a third person. 
   This use case aims to provide a citizen of Kochi the basic technology where in which he/she can find a suitable doctor they need.

3. **Engaging lawyers who are qualified to handle specific cases**
   
   It is quite difficult to identify the best lawyer suitable for a particular case as only their name and qualification are given to the public. A citizen, without any proper contacts, will have to consult a series of lawyers to find the suitable one. This makes it hard and time consuming.

   This use case is focused on enabling a citizen of the city of Kochi to verify that the Lawyer is qualified to handle or offer legal consultation on specific types of cases in a most efficient and trustworthy manner.
    
4. **Availing Driving License test by sharing proofs for eligibility**
   
   To prove that one is eligible for the driver's license test, he/she will have to submit a set of documents to prove all the required proofs. Then the RTO needs to validate it manually and inform the person whether they are eligible or not. It takes a huge amount of time and effort for this.

   This use case is focused on enabling a citizen to present digital proofs to take up driving license test leveraging capabilities of verifiable credentials and increase efficiency of the process.


5. **Creating student credentials for applying admission to external Universities**
   
   Often a student will have to share multiple credential information for applying admission to external universities. The student would need to apply and secure many of these credentials from different source independently. Not every student may be well versed with the formalities involved this and this results in students incurring delays and cost for securing all the required credentials for applying to external Universities. Lack of transparency in the process also causes some students to miss out on the requesting credentials in specific format which forces them to miss out on apply for admissions.

   This use case is focused on enabling a student to collect all required digital credentials /proofs and submit them in a timely manner leveraging a workflow which offers transparency, enhance efficiency, and reduces cost to apply for admissions.


### Utility Foundry Workflow

![swimlanes](./img/workflow-swimlanes.png)

### Learn

- The necessity for a decentralised network which provides privacy as well as security was found out.
- Wipro took the initiative in developing a project which focuses on developing a decentralised identity network which provide both security and privacy.
- The target audience of this project were various associations residing in the city of Kochi, who is interested in participating in a decentralised network.
- Few stakeholders were identified for the project.

### Convene

#### 1. Who are the Conveners and/or Sponsors?

The conveners are going to be,

- Wipro.
- CUSAT
- KBA (Kerala Blockchain Academy)
- Various associations/organizations who wish to have a digital identity.
- Educational institutions in the city of Kochi.
  

#### 2. Why do we need a Utility?

- To give a cryptographically verifiable digital credential for various associations/organizations.
- To give the control of the identity to its owners in its every sense.
- To cut down the red tape in identity verification.
- To give a digital identity that is free of forgery or any such malpractice.
  

#### 3. What is unique about the desired Utility?

- The utiltiy is restricted to a particular jurisdiction, the city of Kochi.
- The utility aims to cut down the cost of hosting a node, incurred by the associations, to the possible minimum.
  

#### 4. Who will participate?

- Association of Medical practitioners: Indian Medical Association (Kochi Chapter)
- Association of Lawyers: Bar Council (Kochi Chapter)
- Association of Real Estate Developers: CREDAI (Kochi Chapter)
- Association of Technical Universities
- Association of Retailers: Retailers Association of India (Kochi Chapter)
- Association of CBSE schools: Kerala CBSE School Management Association (Kochi Chapter)
- Association of Driving Schools
- Residential Associations
  
#### 5. What are the common stakeholder motivators?

- Ownership of one's digital identity.
- Privacy.
- Trusted digital services offering. 
- Low expense in hosting a node.
- Enhance confidency and trust on digital service providers.
- Dedicated community cloud for availing shared infra.
- Verified digital identity.
- ZKP

#### 6. What are the common stakeholder requirements?

- Ability to host their own infrastructure (In this absense , they can avail the community cloud service.).

### Define
   
Using the [Sovrin Governance Framework](https://sovrin.org/library/sovrin-governance-framework/) as a model, a simplified governance framework was built. The KOBPIU networks are run with a very similar governance and structure as what the Sovrin Networks were based on, except that the network will be built for the city of Kochi. All documents are open source, and it will be operated as a public decentralized network. As "Network of Networks" becomes a reality, we hope to be available and at the forefront of collaboration and testing.

* Will use Linux Foundation open source project models.
* Will use Hyperledger Indy as the ledger technology
* Will begin by building a TestNet, then will build a production network and finally a demonstration network as more and more Node Operators come onboard.

### Create

1. Created a CLI manager for the ease of installing various environments.
2. Conducted sessions for various stakeholders.
3. Brought up a verification service.
4. Conducted sessions with Hyperledgerkochi.
5. Built up a website for the project.
6. Recruited a steward.
   
   
   
### Implement

- Drafted Governance documents with Sovrin's Governance Framework as a reference.
- Drafted Steward Agreement.
  

### Maintain
>enter content here
