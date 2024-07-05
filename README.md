# Digital Real

Dear Community,

This is the repository for the Digital Real Ecosystem. Initially, there will only be one token called "Digital Real" whose features I will explain in the "What is the Digital Real?" subsection of this document. We will later add new contracts to the ecosystem, addressing different areas of the project.

## What is the Digital Real?

The Digital peso is a token programmed using a collection of OpenZeppelin smart contracts under the ERC20 standard. Thus, it inherits the following basic features from these contracts:

* It can be used as a voting mechanism for the DAO, wich is asociated to a Panama Foundation called "Digital Real Foundation".
* It can host meta-transactions.

The base OpenZeppelin ERC20 contract was extensively modified to include the following features:

* **Fully Decentralized Issuance and Redemption**: The smart contract itself acts as an Automated Market Maker (AMM). If a community member decides to buy the Digital Real from the smart contract, they must deposit as much ETH as the tokens they require. This way, the token's price is always 1:1 with ETH.
  
  * This makes it impossible to perform a rug pull with the token. There is no pre-issuance of the token, nor are there extraordinary allocations.
  * The token is fully collateralized in ETH.
    
* **Decentralized Payment Agent**: Each transaction generates a 0.1% fee, which is divided as follows:
  
  * 0.02% goes to the programmer's address.
  * 0.02% goes to the DAO's address.
  * 0.06% is split equally into two distribution pools:
    
    * 0.03% goes to a "Pool A" distribution pool, from which the proportional part is distributed to those holding tokens worth more than 0.01% of the circulating tokens.
    * 0.03% goes to a "Pool B" distribution pool, from which 1% of the balance is distributed linearly among any address that has ever held tokens.

However, to avoid overloading and making the system expensive, each transaction executes 10 "Pool A" distributions and 10 "Pool B" distributions individually, with calculations based on the remaining pool balances in each specific distribution round.

## Why Use the Digital Real?

The Digital Real offers various incentives for using it, which are transparent and easy to understand:

* First, the Digital Real always has a price equivalent to ETH. This is because each Digital Real is collateralized by an ETH in the smart contract. This means that if the price of the Digital Real differs from the price of ETH in secondary markets, it creates an arbitrage opportunity for traders to profit by aligning the prices.
* Second, if you want to hold ETH for its potential future appreciation, it’s better to hold Digital Real because the Digital Real will give you the upside of ETH plus commissions derived from arbitrage operations.
* Third, you generate a basic income in the form of passive earnings just by having had Digital Real in your address at some point.
* Fourth, you can participate in the DAO’s investment decisions to generate more income for the Digital real holders by investing the DAO's capital.

Therefore:

### INCENTIVE #1: Arbitrage between the Digital Real and ETH.
### INCENTIVE #2: Earn the same as ETH plus commissions.
### INCENTIVE #3: Generate Basic Income, even if you don't have BetaCash in your wallet.
### INCENTIVE #4: Vote on important community decisions.

## How Will the Digital Real Ecosystem Improve?

The Ecosystem can improve in two ways:

* By promoting arbitrage operations, which will bring money into the DAO, and thus the DAO, controlled by holders, can make investments (or distribute the money as the majority wishes at any given time) to improve the ecosystem.
* By developing projects that generate income for Digital Real holders.

On this last point, I prefer not to comment further, as the system itself is good, transparent, and simple. There is no need to create hype for the project to work. Projects that integrate in the future or are already integrating are welcome.

## Whitelisting in Digital Real

There are vital smart contracts for the proper development of the Digital Real. These contracts are mainly those that form secondary markets. Many of these AMMs do not support tokens with distributions. Therefore, the token has a whitelist where recipients in transfers generate the fee as a reverse charge. This way, the token is compatible with all AMMs. The whitelist is declared by the DAO, only for addresses associated with smart contracts and up to 50 addresses.

## Who is Behind the Digital Real?

Behind the Digital Real is me, Cypher Arcangel. No one else. There is no need to know more about me. Just read the smart contract.

# DON’T TRUST, VERIFY!
