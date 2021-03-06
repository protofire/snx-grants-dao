## Title of proposal: 
new-grants-dao-frontend

## Description: 
We propose to build a new open-source frontend for the Synthetix GrantsDAO in order to improve the user experience and code quality of [the existing one](https://snxgrants.io).

This proposal sets the following goals:
* Build a new frontend with enhanced user experience, providing different features for each type of user (general visitors, community members and team members) implemented in one cohesive design.
* Provide visitors with a clear summary of what projects the GrantsDAO has recently funded and wants to fund.
* List proposals and requests in a tabbed interface, with one tab for proposals and another for requests.
* Allow users to filter proposals and requests according to their status
  * Proposals sorted in Markdown according to their status, also displaying number, title, and name
  * Proposals sorted by status: Proposed (flagged if still in voting period), Approved, Completed, Rejected
  * Requests sorted by status: Proposed, Completed, Deprecated
* Make the new website serve as a DApp for GrantsDAO team members to interact with the GrantsDAO contract via MetaMask. Users/viewers should be able to load the DApp without connecting to MetaMask.
* Create a subgraph for the GrantsDAO smart contract to speed up and simplify access to on-chain data.
* Follow the same look and feel of the current SIPs site.


## Motivation: 
As a community member, we believe that the current website can be much better organised. Currently proposals and their status are confusing (we had the same experience when going through the process of a grant to build a Gnosis Safe App). We strongly believe that through our expertise, we can collaborate to provide a high-quality user experience by developing an interface that serves data fast, in a clear, and well-structured manner, and invites the community to participate more. 

## Additional information: 

### Value
* Better user experience
* Better graphical user interface
* More features for Community and Team members 
* On-chain data is accesible with higher speed and better organization from the UI though a subgraph
* Hosted on IPFS (no centralized party involved)

### Data to process
* Connection to Metamask
* Get proposal data
* Get community members
* Get team members 
* Get on-chain proposals data (status, voters, votes, etc)
* Get off-chain proposals/requests data (GitHub repository)

### User types
* Visitor (read-only)
* Community member 
* Team member (admin)

### Technologies
* Gatsby (React)
* TypeScript
* Subgraph (GraphQL)
* Styled Components

### Assumptions
* Specifications may change during the project definition and scope discovery.
* The complete UI/UX design (mockups) will be available at the time of starting DApp development

### Development Roadmap
The following roadmap is the result of initial research of the Synthetix GrantsDAO contract and analysis of the existing user interface:

#### Milestone 0 - Project Definition
 - Goals
   - Define project scope and assumptions
   - Fully understand grantsDAO contract domain
   - Estimate project duration
- Deliverables
  - Clear and detailed project specs
  - Wireframes for main workflows
 - Team: Project Manager, UI/UX Developer, Ethereum Developer
 - Estimate, hours: 38

#### Milestone 1 - UI/UX Design
- Goals
  - Create, validate and agree on UI/UX mockups for all pages of GrantsDAO frontend
- Deliverables
  - Mockups and assets for all the pages
- Team: UI/UX Developer
- Estimate, hours: 40

#### Milestone 2 - Community Members (MVP)
- Goals
  - Provide visitors with a clear summary of what the GrantsDAO has currently funded
- Deliverables
  - GrantsDAO DApp MVP
  - Subgraph for Synthetix GrantsDAO contract
- Team: Tech Lead, Full Stack Developer
- Estimate, hours: 48

#### Milestone 3 - Team Members
- Goals
  - Enable team members to perform the following actions: voting, adding new members, creating/removing proposals, updating system parameters
- Deliverables
  - Fully functional GrantsDAO DApp
- Team: Tech Lead, Full Stack Developer
- Estimate, hours: 48

#### Milestone 4 - Deployment & QA
- Goals
  - Deploy the application on IPFS (TBD)
  - Quality assurance and end-user testing of every workflow
  - Bug Fixing
  - Complete project documentation
- Deliverables
  - Full artifacts to deploy/serve DApp as static content
  - System documentation
- Team: Tech Lead, Full Stack Developer, QA Engineer
- Estimate, hours: 36



## Previous work: 
[Protofire](https://protofire.io) is a team of engineers that helps builders and providers of decentralized infrastructure, protocols and applications accelerate growth of their ecosystems. By delivering hands-on coding and contributions, Protofire specializes in bootstrapping developer adoption and network usage.

Relevant projects:
- [Opyn SDK](https://opyn.co/#/buy)
- [Safe Apps SDK](https://www.npmjs.com/package/@gnosis.pm/safe-apps-sdk)
- [Compound Safe App](https://github.com/gnosis/safe-react-apps/tree/master/src/apps/Compound)
- CompoundDAO Governance [Subgraph](https://github.com/protofire/compound-governance-subgraph)
-  KyberDAO ([Truestless Operator pools](https://blog.kyber.network/kyber-partners-with-protofire-to-allow-anyone-to-operate-a-trustless-kyberdao-pool-d5da84d2c4c8) and subgraph)
- MakerDAO governance dashboard (https://mkrgov.science)
 

## Estimated hours: 

| # | Description | Estimate (hours) |
| --- | -- | -- |
|  0  | Project Definition | 38 |
|  1  | UI/UX Design | 40 |
|  2  | Community Members (MVP) | 48 |
|  3  | Team Members | 48 |
|  4  | Deployment, QA, Stabilization & documentation | 36 |

Total: 200 to 240 hours. 
Project delivery: 4 to 5 weeks.

## Price (SNX): 
* Total budget: USD 15000 (worth of SNX)
* Payment terms: 50% upfront / 50% main net


## Ethereum Address: 
0xDEAf1d7775D198Dfa5eD9f1df7FA664cFDA920F6
