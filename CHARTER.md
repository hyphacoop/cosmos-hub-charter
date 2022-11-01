# Cosmos Hub Charter

# Preamble

This Working Charter of the Cosmos Hub is a transitory document. It is jointly established by members of the Cosmos Hub community, and adopted by us on `DD-MM-YYYY` through an on-chain vote. The Working Charter will remain in effect no more than four years from the date of its adoption. After that, authority over governance will be ceded to a future Constitution (that incorporates the lessons of the Hub’s prior governance experiments).

The Cosmos Network is an association of economically connected sovereign communities. It is a voluntary association of blockchains that subscribe to a philosophy of sovereign interoperability, localism, and pluralism – a network of networks that uphold the right for communities to maintain technological sovereignty and interoperability.

The Charter enables the philosophy of sovereign interoperability by upholding three freedoms: the freedom to disobey, the freedom to move, and the freedom to create and transform social relationships.

# Section I. Freedoms

## Chapter 1. Freedom to Disobey (to Resist Censorship)

### Article 1
It is our collective duty to co-create and reinforce a culture of censorship-resistance. Censorship resistance is far more a property of the community than it is of the protocol. As such, it starts and ends with every one of us. Sovereignty requires freedom to publish freely.

### Article 2
Individual ATOM stakers should have a strong expectation of property rights on the fork that is canonical to them: apart from the ethical implications of trying to impose future values on past actions, ATOM cannot realize its potential as a credibly neutral reserve currency for the wider interchain if there is a perception that it can be arbitrarily confiscated by the whims of the majority.

### Article 3
Slashing should be reserved exclusively for in-protocol, deterministic removal of token holdings for actions that are provable in a deterministic way (for example double signing, undue downtime, or malicious governance proposals determined as such with NoWithVeto vote).

### Article 4
Slashing should not be used to confiscate funds retroactively from “malicious actors”.

### Article 5
Removing “malicious actors” from the token distribution should, barring an existential threat to the protocol, always take the form of a fork: in which a new genesis file is created for a distinct chain which rearranges the token distribution on that fork.

## Chapter 2. Freedom to Move (to Fork)

### Article 6
A strength of open source is that you can show, through positive action, what a more beautiful world looks like without the use of force or coercion. The right to fork is key to protecting this fundamental ethos, and should be upheld at all costs.

### Article 7
It’s expected and encouraged that if the governance of the Assembly is captured by malicious actors, ATOM Validators and Delegators will vote to remove the Councils making up the Assembly and reinstate new Councils which better serve the community. In the case where tokenholder governance is also captured, the community is expected to coordinate to fork the system and institute a new Assembly.

### Article 8
All of the core software and tooling required to run the Hub should be made open source, freely available, and easy to use such that a fork is always a viable alternative.

### Article 9
The percentage of centrally controlled assets (including fiat-backed stablecoins) held in the Treasury or Community Pool should be bounded so as to reduce outside influence on fork choice or the sovereign affairs of the Cosmos Hub.

> We should think through how a user-activated fork might look like, as well as the implications for IS consumer chains, IBC channels, etc. There is a lot of nuance here.

## Chapter 3. Freedom to Create and Transform Social Relationships (to be a citizen of the Hub)

### Article 10
Every citizen of the Cosmos Hub has the right to participate, to form relations on the Cosmos Hub, and to experiment and propose changes to the mechanisms and processes that make up the Cosmos Hub.

### Article 11
Every citizen has the right to a clear charter that outlines rules and expectations of governance, providing clear and accessible means to create and transform social relationships. These rules and expectations are described in the rest of this document, the Charter.

### Article 12
Citizens should seek to clarify their intentions by using constructive and collaborative results-oriented language for describing their commitments to each other. This includes dynamic cycles of listening, negotiating, executing and assessing.

> We might also want to have something like the followings sections or chapters
> - Values: what values do we expect to be respected in governance (beyond the basic freedoms)
> - Approach and Operating Goals: what are the goals and how do we go about them?
> - Responsibilities: what are the responsibilities of governance participants, councils, etc.

# Section II. The Cosmos Hub

## Chapter 1. The Hub

> The Cosmos Hub’s inaugural role has been to originate the Cosmos Network (aka the internet of blockchains or the interchain). It has achieved this by resourcing the development of the Cosmos SDK, IBC, and Tendermint, the core open-source primitives for the blockchain applications that now populate the interchain.
> 
> The Cosmos Hub’s primary role has now transitioned from conceiving the Cosmos Network to growing a resilient interchain economy: a secure platform for others to build the next generation of interchain-native infrastructure and applications.

### Article 13
Cosmos Hub’s mission is to autonomously secure and capitalize ecosystem-critical applications, while serving as the port of entry for new Cosmos participants, and a coordinating center for the infrastructure and administrative concerns of the Interchain. Accomplishing this aim will require the Cosmos Hub to become self-governing and self-funding.

### Article 14
Cosmos Hub governance consists of two governing bodies (1) ATOM stakers comprising delegators and validators and (2) the Assembly which is in turn composed of Councils. Importantly, ATOM stakers have the power to remove individual Councils from the Assembly, as well as veto power (ref: Art 27) over any proposal made to the Treasury.

### Article 15
The Cosmos Hub will strive to be a minimal hub that other zones will want to use. All features – including the Allocator and the Scheduler – be implemented as consumer chains wherever possible. In a minimal system, zones should be allowed to choose their own set of regulatory policies, and the Cosmos Hub can help enforce these policies when it comes to IBC transfers across zones, or from hub to zone. From the perspective of the Cosmos Hub, this is still a permissionless, voluntary system. The Cosmos Hub endeavors to engage in peaceful, non-coercive relations with other sovereign parties.

## Chapter 2. The Community Pool

### Article 16
The purpose of the Community Pool is to ensure each community member has the ability to request funds for any initiative that ATOM stakers deem worthy of support.

### Article 17
Formal requests for funds from the Community Pool are made through a Community Spend Proposal.

### Article 18
ATOM stakers determine the outcome of Community Spend Proposals through a token holder vote.

### Article 19
A fraction of revenues from the distribution module are diverted to the Community Pool via the community tax parameter. ATOM stakers have the power to directly change this parameter through an on-chain param-change proposal.

## Chapter 3. The Treasury

> The Assembly and Council structure that manages the Treasury is outlined below in Chapter 4

### Article 20
The purpose of the Treasury is to support the maintenance of R&D excellence in the Cosmos Hub and its related technologies, and to support special initiatives that increase adoption, growth, and capitalization of the ATOM economic zone, including public works and opportunities for expansion, turning ATOM into the preferred interchain reserve asset.

### Article 21
The Treasury is initially capitalized through issuance in ten tranches of 4M ATOM each.

### Article 22
ATOM stakers must approve each tranche (where the issuance of the tranche is implemented as a governance approved software upgrade or through an in-protocol mechanism which requires governance approval). There must be a minimum interval of 8 months between each successful proposal. No more than one tranche may be issued within a calendar year.

### Article 23
An Assembly proposal can request that a portion of the Treasury flow back to the Distribution module. The proposal may not ask for more than 10% of the value of the Treasury, and there must be a minimum interval of 1 year between such successful proposals.

### Article 24
Treasury spending will be restricted to pilots and setup costs until the Assembly’s initial budget is approved. The Assembly budget consists of a roll-up of the individual Council budgets; the Assembly is a voting body & nothing more. Pilots and setup costs include expenses for building components described in the Cosmos Hub paper, including the Allocation module and onboarding Allocation DAO members. Before any funds are released for this tranche, a product specification and funding roadmap will be provided for public review. Additional funds can be released if the initial tranche is not sufficient, but the release of these funds is contingent upon the accounting of previously deployed funds and key milestones being met.

### Article 25
The budget for Treasury fund allocation is to be made through a yearly budgeting process conducted by the Cosmos Assembly. The resulting budget is deemed to be approved when a majority of the Cosmos Assembly votes in favor. ATOM stakers may veto the yearly budget while the Assembly proposal is in voting period.

> Currently many teams that work on the Hub follow a yearly budgeting process. It is the goal of the Hub to become a self funded network. The yearly budgeting proposed for the Treasury may help teams transition to become Hub funded.

### Article 26
Budget should leave room for potential formation of new councils during the year that haven't been planned at the outset. This amount should be specified in the Assembly’s budget.

> This can also happen in a bottom up way, where newly proposed councils can request new funding from the Treasury. Something to discuss.

### Article 27
ATOM stakers have veto power on all proposals put forward by the Cosmos Assembly. Quorum will remain 40% and a simple majority is required to veto proposals.

### Article 28
The portfolio of Treasury assets must be managed responsibly including minimizing risks in the event of a prolonged market downturn.

>ATOM holder veto power can be accomplished by adding [Veto functionality](https://github.com/cosmos/cosmos-sdk/issues/12824) to the Gov module. From a technical perspective the assembly could be a group created with the groups module. The members of that group could be other groups (or explicitly designated reps from other groups). The Assembly will need a special “group policy” that allows ATOM stakers to veto their proposals.

## Chapter 4. Assembly and Councils

### Article 29
The Assembly is an on-chain organizational body that consists of councils. Councils may elect to choose a representative to act in the Assembly on the councils’ behalf.

### Article 30
​​The Assembly has to live on the Cosmos Hub in order to properly interact with ATOM governance. Individual Councils however are free to use the governance stack of their choice – whether it be the SDK group module, DAO DAO, or an IBC-connected chain – subject to its ability to interface with the Assembly.

### Article 31
The initial Assembly will be constituted by only two councils: Community Council and the Bootstrap Council. While the Assembly may have more councils in the future, the first two are meant to prove the viability of the changes proposed in the new vision and evolve the on-chain governance process to meet the needs of the Cosmos Hub and its community.

### Article 32
A majority of Assembly members (i.e., councils within the Assembly) are required to pass an Assembly proposal.

### Article 33
For a council to be eligible to receive funding from the Treasury, it has to be added to the Assembly by ATOM stakers (via a standard on-chain tokenholder vote).

### Article 34
Any group of individuals can submit a proposal to ATOM stakers in order to be added to the Assembly as a council. That proposal must include the voting weight that the council will have in the Assembly.

### Article 35
No individual may be in more than one council.

### Article 36 
Councils optimistically propose their yearly roadmaps to the Assembly. A majority vote by the Assembly can veto the roadmap of any individual council.

### Article 37
ATOM stakers may remove individual councils from the Assembly (via a standard on-chain tokenholder vote), thereby restricting their ability to access the Treasury and revoking any on-chain authorizations.

### Article 38
If a council is off-boarded:
* Personnel budget for the council for the following two months remains with the council to ensure a graceful transition period for the individuals
* Funds earmarked as working capital and for the completion incentive are returned to the Treasury

### Article 39
A council can vote to remove any of its council members with a two-thirds majority vote. The Assembly and ATOM stakers cannot remove a council member directly.

### Article 40
A council’s budget will be streamed wherever possible, meaning that the funds are released continuously over a predetermined period of time.

### Article 41
Each council is responsible for coming up with their own disclosure process prior to being ratified by ATOM stakers.

> We will need to think hard about how we can add assurances around one person one council, while remaining as anon friendly as possible. What level of identification is acceptable?

## Chapter 5. Allocator DAOs

### Article 42 
Allocator DAOs that manage Treasury funds must be approved by ATOM stakers.

### Article 43
ATOM stakers may remove individual Allocator DAOs and restrict their ability to access the Treasury.

### Article 44
No more than X% of voting power in the Assembly should be taken up by Allocator DAOs (either via individual councils, or a council of representatives)

### Article 45
Although not every Allocator DAO needs to be a council, there should be a similar degree of accountability (via reporting requirements) between councils and Allocator DAOs.

# Section III. Councils

> This section contains chapters for specific councils that exist. Whenever a new council is added, the charter should be amended to add a Chapter for the new council in this Section.

## Chapter 1. Community Council

### Article 46
The Community Council is the primary representative of ATOM stakers (Hub citizens) within the Assembly.

### Article 47
The Community Council’s role includes holding other councils to account, elaborating on the Charter, providing feedback on decisions from the community’s perspective, and providing a bridge to the wider community by communicating important facets of ongoing workstreams.

### Article 48
The Community Council is expected to act as a balance of power to the Bootstrap Council.

### Article 49
The Community Council is responsible for recommending a veto on Assembly proposals. In case of a veto, it is the responsibility of the Community Council to make recommendations to the Assembly for proposal revisions.

### Article 50
ATOM stakers cannot make proposals to the Assembly directly. The Community Council must do this on their behalf.

### Article 51
The long term vision is for the Community Council to become a fully-fledged Citizens Assembly, which will act as a balance of power between Cosmos citizens and the Assembly of councils. Part of the Community Council’s mandate is to flesh out this longer term vision.

### Article 52
The Community Council should be independently funded from the other Councils, for example, from the Community Pool, to ensure that the Community Council’s funding can not be revoked by the Assembly

### Article 53
The Community Council will initially be composed of…

> The number of members, how they are chosen, and whether or not they should be compensated is something the community needs to decide on.
> 
> Ideas for how Community Council membership is maintained
> 
> * Sortition - random selection from a list of Citizens who have stepped forward
> * ATOM holders vote for each Council member
> * Referral from existing community council members
> 
> There should be term limits for Community Council members and a reflective process to ensure the Community Council is being representative of ATOM holders.

## Chapter 2. The Bootstrap Council

### Article 54
The Bootstrap Council is a temporary Council that will exist until the Assembly’s initial budget proposal.

### Article 55
The Bootstrap Council’s mandate consists of implementing the initial pilots and components described in the Cosmos Hub paper: issuance, governance, Allocator, Scheduler, until a fully-fledged Assembly has been formed.

### Article 56
The Bootstrap Council is expected to act as a balance of power to the Community Council (you can think of the initial Assembly as a 2-of-2 multisig).

> The Bootstrap Council would be made up of core developers and contributors implementing the initial pilots and components described in the paper.

# Section IV. Metagovernance

### Article 57
Once approved, this document will continue to reside within the Cosmos Hub git repository. Amendments and annulments to the Charter are merged in the repository after an on-chain vote.

### Article 58
ATOM stakers have the responsibility of defining and updating this Charter, which includes directives at the highest level (as well as specific details where they are deemed important e.g. reporting requirements for councils and/or Allocator DAOs).

### Article 59
The process of changing Sections I, II, III, and IV of the Charter should require extensive discussion, a quorum of ATOM stakers, and a supermajority in a given vote.

> This will not be explicitly represented in the on-chain quorum until modifications are made to the gov module.

### Article 60
The process of changing a specific param or reporting requirement in the Charter should require extensive discussion, a quorum of ATOM stakers, and a majority in a given vote.

> We will need to decide what the quorum requirement for metagovernance proposals should be (too high and this preliminary Charter will be set in stone until it expires, too low and it loses its meaning/importance). We may need to implement safeguards – e.g vote extensions – to handle the possibility of last-minute vote swings (especially important in a liquid staking world).

# Params and Reporting requirements

As outlined in Section IV Metagovernance, the following parameters and specific requirements can be changed by a lower threshold of voters, while Sections I, II, III, and IV require a supermajority.

## Params

ATOM stakers can vote to change these params through an on-chain parameter change proposal

* Type of Assets held in the Treasury (e.g what is the maximum percentage of real-world assets, stablecoins, etc)
* The fraction of revenues from the distribution module that is diverted to the Community Pool.

> Suggestions for restrictions requested

## Reporting requirements

> For Councils and Allocator DAOs need to be discussed. Since the first two proposed Councils in the Charter are the Community Council and the Bootstrap Council, their reporting requirements should be finalized first.
