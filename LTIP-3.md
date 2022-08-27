| id | Title | Status | Author | Description | Discussions to | Created |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| LTIP-3 | OPIncubator Project #1 | Draft | Weston (westonnelson) Exosphere (@exosphereL2), Train (@layer2train) | DAO Vote to Partner with Thales Protocol and Support L2 Adoption | https://discord.gg/layer2dao | 2022-08-26
 
# Summary
 
This LTIP proposes to enable a vote by the Layer2DAO, conducted via Snapshot, to select the first project for the OPIncubator. Thales Protocol has been identified as the project that has demonstrated leadership in the L2 space and is what the DAO believes a high impact L2 project. The Proposal would entail supporting Thales with 27,500 $OP tokens and a token swap between the two DAOs, Layer2DAO, and Thales DAO, to align both protocols interests over the long-term. 

 
# Abstract

The L2DAO is about leadership in the Layer2 space.

# Background: 

L2DAO is the Layer2DAO governance token which was recently [launched](https://docs.layer2dao.org/airdrop) ~6 months ago. The DAO has launched several products that are starting to produce ongoing revenues, such as .L2 domain sales and resale commissions of the L2 early adopter NFT series, with other revenue generating projects, such as the OPIncubator, in the pipeline. .L2 domains in particular have tremendous growth potential as a direct competitor to ENS.

The Layer2DAO team is proposing that we reward long-term holders of L2DAO tokens by paying out a part of DAO revenues (up to 50%) to token holders on a regular basis. Token holders will need to stake and lock up their tokens in order to participate in revenue sharing. Tokenomics are a critical missing piece for bootstrapping the protocol, TVL, and volume. There must be enough L2DAO liquidity to mitigate undesirable price action and negative feedback loops.

The specific tokenomics model being proposed lets users lock their L2DAO governance tokens for different lengths of time (between 3 months and 2 years) to receive xL2DAO tokens, which provide voting power and access to revenue sharing from the protocol. Users receive more voting power and revenue proportional to their lock duration. 

xL2DAO holders will vote on which revenue sources to include in revenue sharing, starting with .L2 domain sales. 50% of the included protocol’s revenue will be distributed to xL2DAO holders weekly as L2DAO/ETH LP tokens, which will provide continuous buy pressure for the L2DAO/ETH Pool. The remaining 50% of revenue will go to the community treasury to continue building protocol controlled value/investments in other protocols/high impact layer 2 plays.

Layer2DAO’s tokenomics implementation (xL2DAO) will be largely based on [Ribbon Finance](https://www.ribbon.finance/)’s Ribbonomics [(source code)](https://github.com/ribbon-finance/ribbonomics). The major changes from Curve’s/Ribbon’s implementation include:

* Optionality to unlock all locked xL2DAO ahead of the max 2 year lock if governance wants to use an alternate tokenomics model.
* A withdrawal penalty that allows users to unlock their xL2DAO early by paying a penalty that is distributed to remaining lockers pro-rata.

Layer2DAO will also distribute 1% of the token supply (10,000,000 L2DAO) from the community treasury over 3 months as incentives to accelerate the new tokenomic model.

Many thanks to the [Saddle Finance](https://saddle.finance), [Curve](https://curve.fi) and [Ribbon](https://www.ribbon.finance/) teams for their opensource contributions to the space!

# Implementation:

If LTIP-3 is approved, the process for enabling the DAO to deploy the xL2DAO contracts would begin as well as the UI for token holders to manage their interactions with the protocol. 

A new Snapshot voting strategy will be deployed to replace L2DAO voting with xL2DAO voting as governance voting will be eligible only to those holding xL2DAO. 
Future Plan: Although not a part of this proposal, in the future we hope the community will investigate the following new initiatives:

* Migrate to on-chain governance using [Compound’s](https://compound.finance/) [Governor Bravo](https://medium.com/tally-blog/understanding-governor-bravo-69b06f1875da) or [SafeSnap](https://docs.snapshot.org/plugins/safesnap), or one of the new developments soon to be released from Snapshot.
* Issue bonds via [Olympus Pro](https://www.olympusdao.finance/pro) to buy and deploy more protocol owned value.
* Launch borrowing against LP tokens
* Collect airdrops and admin fees from select Layer2DAO Partner Protocols
* Explore creative use cases of dynamically integrating NFT ownership to provide direct economic incentives to xL2DAO holders.
* The ability for xL2DAO lockers to delegate their boosts to other users.

# Copyright:

Copyright and related rights waived via CC0.