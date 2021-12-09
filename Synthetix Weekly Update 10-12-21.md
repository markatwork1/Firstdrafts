
<p align="center">
  <a href="http://app.boardroom.info/BanklessDAO">
    <img src="https://miro.medium.com/max/1400/1*V3K-Uu2va_r9p7O2p_FzMw.png" alt="Synthetix" width="400" />
  </a>
  <h1 align="center">Synthetix Weekly Update</h1>
  <p align="center">
    December 10th, 2021
  <br />
  <a href="http://app.boardroom.info/BanklessDAO"><strong>View in the Portal »</strong></a>
  <br />
  </p>
</p>

### <p align="center"> *New Weekly Update for Synthetix from Mark Priddy December 6th 2021 - December 10th 2021*

## Discord Announcements
	
[December 10th Recap Blog](https://snxweave.medium.com/snxweave-weekly-recap-53f3d05f5830)

[On Spotify](https://open.spotify.com/episode/6Om5sRth9AzVW7RmIb7glh)

- Blog Post for the next [Synthetix Community Call](https://blog.synthetix.io/come-join-us-on-dec-15-dec-16-for-the-next-synthetix-community-governance-call/)

- Rewards are now claimable [here](https://synthetixembassy.io/gpp) by all addresses who delegated $UNI for the Governance Participation Program
	
- All Synthetix Improvement Proposals [here](https://sips.synthetix.io/all-sip/)
	
## Governance

### Spartan Council and Core Contributor Committee

- New Spartan Council Election is active
	
  - "If you plan to run for Spartan Council this epoch and would like to participate in the panel, please have your nomination in BEFORE tomorrow at 22:00 UTC, and tag ProofOfCake in the spartan-council-nominations channel in the Synthetix Discord."[^1]
	
[^1]: SNXWeave, "SNXweave Weekly Recap", *https://snxweave.medium.com/snxweave-weekly-recap-53f3d05f5830*, Medium, December 7th, 2021. December 9th, 2021
	
-  LUSD/sUSD wrappr has been added to L1 with [SIP-190](https://sips.synthetix.io/sips/sip-190/) with parameter changes in [SIP-151](https://sips.synthetix.io/sccp/sccp-151/)
	
  - This introduced an LUSD Wrappr that mints sUSD for each LUSD deposited, with no fee
	
  - Burn fee on ETH has also been lowered to zero and the cap decreased
  
- [SCCP-153](https://sips.synthetix.io/sccp/sccp-153/) was implemented raising the cap on atomic swaps per block to 1 million sUSD
	
  - In the near future, this will be raised again to accomodate large trades without a fee reclamation delay.
	
- [SIP-192](https://sips.synthetix.io/sips/sip-192/) implemented with the [Atria Release](https://blog.synthetix.io/the-atria-release/) to fix the error where fees from the Wrappr Factory are double-counted 
	
  - $257,000 repaid to Synthetix fee address after an error where stakers claimed a higher amount than they should have been able to, resulting in a loss of funds in the fee payment address
	
- [SIP-188](https://sips.synthetix.io/sips/sip-188/) and [SIP-180](https://sips.synthetix.io/sips/sip-180) were presented recently
	
  - SIP-188 will list a synth that tracks and mirrors the ETH:BTC price ratio on L1.
  - The only difference in functionality of this synth will be that it trades at the ratio of prices from multiple Chainlink feeds — ETH:USD and BTC:USD, or inverse of BTC:ETH
	
  - SIP-180 proposes the creation of Aelin Protocol
  - Aelin is an open and permissionless set of factory contracts that enables anyone to instantiate a pool of capital that can be used to source deals within the Ethereum ecosystem
  - [Recording available here](https://anchor.fm/synthetix/episodes/SD036---Spartan-City-Hall-3---Aelin-e1af7f3) with Aelin in a Spartan City Hall recap.
  - This SIP was also voted on and approved, with 6 Council members voting in favor and none against
	
  - "Aelin is a new decentralized deal coordination protocol that will leverage the established decentralized governance framework of Synthetix to launch this new protocol in a fair and transparent manner. 30% of the initial supply of AELIN tokens will be released initially. Of this 30%, half (so, 15%) will be airdropped to SNX stakers on L1 and L2 as a sign of appreciation for the effort that has gone into Synthetix governance enabling Aelin to launch via this SIP."[^2]
	
[^2]: SNXWeave, "SNXweave Weekly Recap", *https://snxweave.medium.com/snxweave-weekly-recap-53f3d05f5830*, Medium, December 7th, 2021. December 9th, 2021
		
	
### GrantsDAO

- [Twitter Announcement](https://twitter.com/snxgrants/status/1465949107386781698) of the Retroactive Public Goods Grants (RPGG) initiative going live last week
	
- Twitter Space event with Grants Council and Gitcoin took place Wednesday November 8th, 2021
	
- Grants Council partnered with Gitcoin to put forth a private Grants funding round that will go towards public good projects that have benefitted the larger DeFi community
	
  - [Eligibility Criteria Here](https://medium.com/@SynthetixGrants)
	
- Another AMA event announcement will be posted soon with members from the Synthetix Ambassadors DAO, Optimism, and the Universe.xyz
	
- New gDAO website still being worked on but should be available by the end of the year 
	
- Reminder that the recent Flashloan tool used lets you sell off some of your SNX for sUSD so you can pay off some of your debt and eventually get unstaked. If all of your SNX is staked and zero SNX is transferable, then there is zero SNX that can be sold. You can ONLY take a flashloan out against transferable SNX
	
	
### AmbassadorsDAO

- Millie submitted an [SCCP](https://sips.synthetix.io/sccp/sccp-155/) to modify the Ambassador Council mandate for the upcoming election. 
	
  - The most notable change will raise the Council seats to 4, while allowing for a 3/4 Gnosis Safe Multi-Sig. 
  - The SSCP also reinstates the need for a technical role on the Ambassador Council as opposed to a clause in [SIP-157](https://sips.synthetix.io/sips/sip-157/) excluding the expectation for a technical role.
	
- Co-founders of Optimism Kevin and Ben [answer several of the community’s questions as well as discuss](https://anchor.fm/synthetix/episodes/SD039---Spartan-City-Hall-4---Optimism-e1b60p2) the recent regenesis and the future of Optimism ina recent Spartan City Hall
	
- The nomination period for all DAO positions is open for another week
  
  - To be on the ballot for the Spartan, Treasury, Grants, or Ambassador Council you must have your nomination in before the end of the day UTC time Tuesday December 14th. Voting will begin immediately following the end of the nomination period and will go through the end of the day UTC time Tuesday December 21st


## Summary	

- [SIP-190](https://sips.synthetix.io/sips/sip-190/) implemented and added LUSD/sUSD to L1

- [SIP-151](https://sips.synthetix.io/sccp/sccp-151/) added alongside SIP-190 which included Wrappr Parameter Changes (L1)

- [SIP-153](https://sips.synthetix.io/sccp/sccp-153/) implemented which increased Volume Cap on Atomic Exchanges
  
- [SIP-192](https://sips.synthetix.io/sips/sip-192/) implented with the Atria release which added a Fee Pool Accounting Error Fix and Reimbursement
  
- [SIP-188](https://sips.synthetix.io/sips/sip-188) was presented to Add sETH/BTC synth still in feasibility
  
- [SIP-180](https://sips.synthetix.io/sips/sip-180) was also presented The initial [Aelin](https://anchor.fm/synthetix/episodes/SD036---Spartan-City-Hall-3---Aelin-e1af7f3) Council will have 5 members voted in by SNX holders 
  
- [SCCP-155](https://sips.synthetix.io/sccp/sccp-155/) Ambassador Council Modification

- [SIP-157](https://sips.synthetix.io/sips/sip-157/) ambassadorDAO Mandate
  - There was a clause in this SIP that excluded any expectation of technical skills related to smart contracts. However, since Ambassador Council has matured with initiatives such as the Governance Participation Program, a technical role within the Council is necessary.

## Additional Research

-  [Bloomberg Atricle](https://www.bloomberg.com/news/articles/2021-12-06/crypto-crash-weights-on-defi-tokens-already-on-downward-spiral) mentioning Synthetix among other top cryptocurrencies
  - Mainstream FUD around the recent dips

<p align="center">
  <a href="http://app.boardroom.info/">
    <img src="https://i.ibb.co/PFcchnQ/boardroom.png" alt="Boardroom Logo" width="450" />
  </a>
</p>

<p align="center">
	This report was prepared by the Governance Scribes Guild
  <br />
  <a href="http://boardroom.info/">Portal</a>
  ·
  <a href="https://discord.com/invite/tgrTFg9">Discord</a>
  ·
  <a href="https://boardroom.mirror.xyz/JHrN8nVy_J4C7Xzj37zoyPANg0ZnNszhWy9YOZHC0lM">Join the Scribes Program</a>
</p>

<p align="center">
  <a href="https://discord.gg/CEZ8WfuK8s">
    <img src="https://img.shields.io/badge/Discord-Join-7289da?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
  <a href="https://twitter.com/boardroom_info">
    <img src="https://img.shields.io/badge/Twitter-Follow-1da1f2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
  </a>
</p>


