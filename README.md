# Solutions to Guard Against MEV Theft

This report addresses the significant concern of Maximum Extractable Value (MEV) theft within Ethereum's liquid staking pools, particularly those composed of permissionless node operators (NOs). It highlights the risk posed by NOs who might redirect MEV rewards to their own addresses, thereby depriving liquid staking token (LST) holders of their rightful shares. This concern is exacerbated in the context of permissionless staking pools, where entry and participation are minimally regulated.

Key concepts such as Staking Rewards, MEV, Proposer-Builder Separation (PBS), and various Ethereum Improvement Proposals (EIPs) like EIP-4788 and EIP-7044 are reviewed to provide a foundational understanding. The report delves into MEV theft strategies, including the "lottery block attack" and "long-con attack," illustrating the potential avenues through which NOs can exploit the system for personal gain.

To combat these issues, the report explores both existing and novel MEV theft mitigation strategies, focusing on the potential of "forced exits" as a deterrent. Forced exits would enable a decentralized staking pool to initiate an exit for a validator from the network without the NO's direct involvement, contrasting with the conventional voluntary exit process. This concept is further elaborated with technical insights into implementing forced exits, including the use of voluntarily signed exit messages and proposals for new Ethereum Improvement Proposals (EIPs) like EIP-7002, which would facilitate execution layer triggerable exits.

It is currently issues as a Draft and we welcome commetns form the community.

[Download a pdf of the report]([https://github.com/htimsk/ForcedExits/raw/Forced%20Exits.pdf](https://github.com/htimsk/ForcedExits/blob/main/Forced%20Exits.pdf))

[Google docs version for direct commenting](https://docs.google.com/document/d/1waYXhC7QvqegpkQ3nAXcx9_D3Riev39S2W-NpUgAHKI/edit?usp=sharing)

This analytical report and any associated code in this repository are available under the BB CY license. 
