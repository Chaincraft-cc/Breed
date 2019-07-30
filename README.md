## Breed (BEE) 🐝 - Coined by Sharing

Breed is an inflationary ERC20 Token on the Ethereum Blockchain. In a nutshell, BEE is created everytime you're sending it to someone who never held BEE before. The goal of this experiment is to find out how long it takes for a Token that is coined by sharing to hit it's actual hard cap, and how distribution evolves.

### Token mechanics
- Hard Cap: 10M BEE
- No Airdrops, no ICO: Every wallet can claim 250 BEE once for free to get breeding, until 2.5M BEE have been claimed (= 25% of max supply)
- Besides that, BEE can only be minted by transferring it - you can _breed_ 10% of the sent value under special circumstances (see _"How to breed"_ below)
- Pre-Mint: 1% of max. supply, for Dev and giveaways

### How to breed
In short, you mint (_breed_) Tokens by sending them to someone who never held BEE before. If the requirements below are satisfied, you get 10% of the _sent_ BEE back:
- the **recipient** has not 'bred' tokens already (every wallet can _breed_ only once).
- the recipient's balance is >= 0.001 ETH (and therefore is considered an 'active wallet').
- the sent amount of Tokens must be at least 2 BEE (well, you need at least 2 of a kind for things like that).
- the recipient is not the sender (don't be a killjoy).
- the hard cap hasn't been reached yet (obviously).

#### Examples:
- Send 100 BEE to an active wallet which never held BEE -> Recipient receives 100 BEE, you get 10 BEE
- Send 1 BEE to an active wallet which never held BEE -> Recipient receives 1 BEE, and can still breed if s/he recieves BEE again
- Send 2 more BEE to the wallet above -> Recipient receives 2 BEE, you get 0.2 BEE, the recipient can't breed new Tokens anymore
- Send 2 BEE to a wallet which doesn't statisfy the criteria above -> Recipient receives 2 BEE, no breeding

### How to get BEE
You cannot buy BEE, and it most likely will never be listed on an exchange, due to the fact that supply could be inflated by bad actors if  financial incentives are involved.
2.5M BEE (10.000 claims à 250 BEE; 25% of max supply) are available to claim for free from the Breed Smart Contract (see the [Breed Homepage](https://breed.chaincraft.cc#start-breeding) for more details). After the "claim cap" has been reached, new Tokens can be created by _breeding_ only, so make sure to grab some!

### FAQ

#### Why Breed?
I just wanted to play around with unusual Token mechanics and claiming possibilities, and I was tired of the cheap BOMB-knockoffs flooding Reddit and Twitter, so I tried to come up with something new. If I get some reception on Breed, I may get working on the NFT-based game I can't get out of my head currently :)

#### This can be gamed!
The restrictions on breeding should act as a disincentive for bad behaviour - having to fund a new wallet, claiming coins, sending them to another wallet and collect the remaining ETH, or similar scenarios, are quite expensive in terms of transaction fees and gas usage (however possible). In fact, it's part of the experiment to see how exactly new BEE will be bred and how people will interact with it.

#### How much Gas is Breed using?
We don't want you to run into "out-of-gas" situations when interacting with Breed, so set the following [gas limits](https://chaincraft.cc/ethereum-gasprice) (not gas price!) when calling the contract. Better DApp-wallets like [MetaMask](https://www.metamask.io) will do this for you automatically.
- `transfer`: <85k Gas when breeding, <45k Gas for a simple transfer (set to 85k to be safe)
- `claim`: <85k Gas


Special thanks to [OpenZeppelin](https://github.com/OpenZeppelin) for their awesome [Solidity contracts framework](https://github.com/OpenZeppelin/openzeppelin-contracts), [Truffle](https://github.com/trufflesuite/truffle) for the toolset and each and every [Ethereum Core](https://github.com/ethereum) Dev.

### Happy Breeding!
