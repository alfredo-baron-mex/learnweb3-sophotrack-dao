# LearnWeb3 - Sophomore Track

## Level 9 Building a DAO (Decentralized Autonomous Organization) Lab

### Introduction
---
The scenario is launch a DAO for holders of the CryptoDevs NFTs (created in NFT Collection Lab). From the ETH that was gained through the ICO and has built up a DAO Treasury. The DAO now has a lot of ETH, but currently does nothing with it.

Now, it want to allow the NFT holders to create and vote on proposals to use that ETH for purchasing other NFTs from an NFT marketplace, and speculate on price. Maybe in the future when sell the NFT back,  split the profits among all members of the DAO.

### Requirements
---
- Anyone with a CryptoDevs NFT can create a proposal to purchase a different NFT from an NFT marketplace.
- Everyone with a CryptoDevs NFT can vote for or against the active proposals.
- Each NFT counts as one vote for each proposal.
- Voter cannot vote multiple times on the same proposal with the same NFT.
- If majority of the voters vote for the proposal by the deadline, the NFT purchase is automatically executed.

### Prerequisites
---
- [**NFT Collection Lab**](https://github.com/alfredo-baron-mex/learnweb3-sophotrack-nftcollection)

### Important
- To be able to purchase NFTs automatically when a proposal is passed, need an on-chain NFT marketplace that you can call a purchase() function on. There exist a lot of NFT marketplaces out there, but to avoid overcomplicating things, will create a simplified fake NFT marketplace for this Lab as the focus is on the DAO.


### Lab Content
---
- Smart Contract ([***hardhat***](hardhat))
- React-Next App ([***my-app***](my-app))

