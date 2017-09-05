# CAHF: A contingency plan against Byzantium HF & POS Change(EIP649)
### Definitions
HF: HF stands for Hardfork.  Developers add a mandatory rule set to change the node software. These changes make previously invalid blocks become valid. Nodes/Miners with the rule set changes will follow this chain if they have a consensus.

CAHF: CAHF Stands for Community Activated Hard Fork. Like HF, developers add a mandatory rule set to change the node software and these changes make previously invalid blocks become valid. The CAHF proposal is a peaceful and voluntary departure of different community members who have different opinions or visions, and it is not intended to make an attack against other blockchain(s), even if the CAHF chain has the higher hash rate or higher value.

Byzantium HF: Byzantium Hardfork is an hard fork from the post-chain(Called Mainnet Homestead chain). It may follow EIP649 and will be the bedrock of POS(Proof-of-Stake) release.

POW: POW stands for Proof-of-work ecosystem. A chain or network using POW may consume a lot of energy but has an effictive, sustainable security system.

POS: POS stands for Proof-of-stake ecosystem. A chain or network using POS may consume less energy than POW but may have security risk and less circulation on tokens.

Difficulty-Bomb: 

EIP649 node: a Bitcoin node that has implemented BIP148 consensus rule changes.

EIP649 chain: a blockchain that is valid according to the BIP148 consensus rule changes. BIP148 is a kind of UASF.

Original chain(Homestead): The blockchain that uses the same consensus rules in use today.

Circulating Supply(Homestead): Circulating Supply(or total amount of released or issued ether by mining & pre-sale) of Ethereum Mainnet. Now Circulating Supply is approx. 94 million ether.

### Background

Like all Ethereum users knows, Ethereum has passed over several forks including mainnet HF. Several HF that have initiated to Ethereum mainnet caused several consensus between ethereum foundation & miners & the community. Despite that changes of mainnet consensus and protocol updates maintained ethereum's roadmap & inherent value, However, All Hard forks wasn't able to pull all user's agreement. For example, Hardfork that contains refund of The DAO hack occured chain split to the one's who did not updated their protocol(Known as Ethereum-Classic chain), and the hard forked chain(Now the main-net of Ethereum) 

After 1 years later of the chain split, Ethereum's main-net has scheduled to change to Metropolis, and if so main-net chain may pass 2 Hardforks called Byzantium and constantinople hard fork. Before byzantium ethereum main-net chain's mean block time has been increased due to an extreme difficulty increase by a code called Difficulty-Bomb code. It's code's purpose was to give an incentive when mainnet hardforks to Byzantium and POS change, eventually abandon original chain with an iceage.

Therefore, In order to delay the difficulty bomb Ethereum Foundation and their dev team have decided to change the codes on Byzantium(EIP649). Meanwhile, they are also changing mining issuance 5 to 3 as they are saying since the mean of the blocktime has decreased issurance of mining will kept the same until ethereum's POS change.

The start of necessity of issuance reduction was started from single anonymous individuals, claming that reduction is needed for reducing the incentives for miners and redicung inflation, eventually cause POS change and would be more "greener" ethereum(see https://github.com/ethereum/EIPs/issues/186).

However, EIP649 including issurance reduction poses a significant risk for the Ethereum ecosystem, so we are preparing a contingency plan to protect the economic activity on the Ethereum blockchain from this threat.

The purpose of this blog post is to announce our CAHF contingency plan for EIP649/Metropolis.

### Why we need a contingency plan against EIP649 and POS change

Later september, The byzantium hard fork including EIP649 will trigger chain split and newer chain including issurance reduction will adopted at higher chances. 

EIP649 is very dangerous for ethereum ecosystem including users and miners. Smaller incentives for mining is equal to smaller payment for security of main chain, and the risk of security caused from decrease of mining hashes may grow up higher. Since miners won't spend their energy or equipments to smaller intensive, they would likely move to another chain before POS change. Therefore, the mining activity behind a Byzantium chain may stop without notice, and investors who buy in the EIP649 propaganda may lose all their investment. Any exchanges that decide to support a Byzantium token after the forking point need to consider the stagnation risk attached to it.

Also decreasing supplyment of ether without POS may cause serious economic problem based on "unplanned" supply such as deflation or other arguements from investors, eventually make investors reconsider their investing activity to ethereum.

Futhermore We, the ethereum holders or miners have a right and 'duty' to 'capture' or 'preserve' our investigation which is the mainnet of ethereum against the risk, we should build a contingency plan for our original chain being attack.

### Protection Plan

This plan is for Community Activated Hard Fork, or CAHF. You can find techinical specs here:

https://github.com/CAHF/Ethereum-CAHF

CAHF will be activated "right before" Byzantium HF. We will update the time when the blockstamp of Byzantium updates.

CAHF chain will follow and fork existing rules of the main-chain of ethereum except issurance reduction and POS. We will maintain our POW chain and will be the Ethereum-POW chain(when Ethereum hardforks to POS).

Despite of maintaining "large" network of cryptocurrency costs so many human resources and costs, we will issue 10% of pre-mine inflation for "Develop and 'storing value'" stake.(and will be 1% inflation of total supply)

Once we mine our stake 'private' and check that there is no further problem on the chain, we will make our repository 'public' and release our CAHF geth node.(Will be updated to our twitter account)

Our CAHF developers are serious for monetary policy of CAHF chain and CAHF's total supply will be 1 billion. When CAHF chain has issued total 5 hundread million than we will halving the issurance to 2.5. This decision is from that "Ethereum is not an asset, is a currency".

We share the same belief with some very early Ethereumers, that decentralization means that more than 1 billion people in 200 countries are using Ethereum as a saving currency and payment network, and that it comprises of hundreds of thousands of Ethereum services, traders, exchanges and software to be decentralized. We do not believe that decentralization means a decrease of issurance so there will be no more inflation before POS change or change to POS so some accounts that has larger volume of ethereum takes most of issurance than who doesn't.

### Software development

Currently, there are at least 4 client development teams working on the code of the spec. All of them want to stay quiet and away from the propaganda and troll army of certain companies. They will announce themselves when they feel ready for it. Users will be able to install the software and decide whether to join the CAHF.

The softwares are expected to be ready before late september, and it will be live on testnet by then. 

### References

For other parties in the ecosystem, we recommend detailed research on effects of the EIP649. All Ethereum businesses must be prepared on that day to mitigate or eliminate the risks that EIP649 carries.

1. https://blog.bitmain.com/en/uahf-contingency-plan-uasf-bip148/
2. https://github.com/digitsu/splitting-bitcoin
3. http://www.uasf.co/
4. https://github.com/ethereum/EIPs/issues/186#issuecomment-269902119
5. https://github.com/ethereum/go-ethereum/pull/15028/commits/b872961ec82ec88a7ac6ef331cfb3eb685ce2c00

### Translations

Translations may be available at transifex
