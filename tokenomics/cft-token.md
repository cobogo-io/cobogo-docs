# CFT Token

The **Cobogo Fan Token** **(CFT)** is an **NFT** (ERC-1155 token) introduced at the cobogo ecosystem to maximize composability, especially as a **mechanism to introduce perks** that Creators can provide for their fan base.

This NFT can only be minted by individuals that stake CBG tokens at a Creator smart contract. **It represents a staking position** and is minted as follows:&#x20;

At the moment a CBG token holder stakes their tokens in a Creator pool smart contract, an NFT is minted and transferred to them, that is, the same individual that called the deposit function.&#x20;

This NFT contains all the metadata regarding that staking position, including how many tokens were deposited, blocktime, and which smart contract (specific to a singular Creator).

CBG tokens can be **withdrawn at any time**, in this case, the owner of the position will call a withdraw function, tokens will be withdrawn and the metadata will be updated in the NFT.&#x20;

In the case where the contract owner decides to withdraw the entire position - that is, 100% of the CBG tokens deposited in the contract (including the accrued yield) - all the tokens are simply withdrawn and the NFT that represents that position is burned.

Fans are free to stake again at any time, in the case another deposit contract is called, another NFT representing the position is minted with all the respective metadata regarding that specific deposit call.&#x20;

The main benefit of introducing the CFT is that **staking positions can be traded on a secondary market**, transferred between wallets, and be easily used as memberships or keys to access gated content and perks.
