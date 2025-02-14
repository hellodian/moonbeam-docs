Some important parameters to understand in relation to the staking system in Moonbeam include:

 - **Collators** — block producers. They collect transactions from users and produce state transition proofs for the relay chain to validate. Have a stake in the network that get slashed if they misbehave
 - **Nominators** — token holders who stake tokens, vouching for specific collators. Any user that holds a minimum amount of tokens as [free balance](https://wiki.polkadot.network/docs/learn-accounts#balance-types) can become a nominator
 - **Minimum nomination stake** — minimum amount of total tokens staked a user must have to be in the set of nominators
 - **Minimum nomination** — minimum amount of tokens to nominate other collators once a user is in the set of nominators
 - **Maximum nominators per collator** — maximum number of nominators a collator can have
 - **Maximum collators per nominator** — maximum number of collators a nominator can nominate
 - **Round** — a specific number of blocks around which staking actions are enforced. For example, new nominations are enacted when the next round starts. When revoking nominations, funds are returned after a certain amount of rounds
