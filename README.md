# awesome-solana v2
Awesome list of Solana links, updated recently and with more info than some other similar lists.

------------------------

* [Solana Developer Reference](https://github.com/csjcode/awesome-solana#solana-developer-reference)
* [Solana Architecture](https://github.com/csjcode/awesome-solana#solana-architecture)
* [Solana Developer Opportunities & Jobs](https://github.com/csjcode/awesome-solana#developer-opportunities--jobs)

------------------------

### Solana Developer Reference

#### [Solana Official Docs](https://docs.solana.com/)

* Learn Solana Development
  https://docs.solana.com/developers
    * [Programs](https://docs.solana.com/developing/intro/programs)
    * [Transactions](https://docs.solana.com/developing/programming-model/transactions)
    * [Accounts](https://docs.solana.com/developing/programming-model/accounts)
    * [Building Programs](https://docs.solana.com/developing/on-chain-programs/overview)
    * [Hello World](https://docs.solana.com/developing/on-chain-programs/examples#helloworld)
* Running a Validator
  https://docs.solana.com/running-validator
* Programming Model
  https://docs.solana.com/developing/programming-model/overview
* Create an SPL Token
  https://spl.solana.com/token
* Architecture
  https://docs.solana.com/cluster/overview
* Add Solana to Your Exchange
  https://docs.solana.com/integrations/exchange
* Solana Terminology
  https://docs.solana.com/terminology


#### [Solana Cookbook](https://solanacookbook.com/)
* Installation (Web3/Solana)
  https://solanacookbook.com/getting-started/installation.html
* Local Development
  https://solanacookbook.com/references/local-development.html
* How to generate a new Keypair
  https://solanacookbook.com/references/keypairs-and-wallets.html
* Accounts
  https://solanacookbook.com/core-concepts/accounts.html#facts
* Programs
  https://solanacookbook.com/core-concepts/programs.html#facts
* Transactions
  https://solanacookbook.com/core-concepts/transactions.html#facts
* Program Derived Addresses (PDAs)
  https://solanacookbook.com/core-concepts/pdas.html#facts
* Get Program Accounts
  https://solanacookbook.com/guides/get-program-accounts.html#facts
* Serializing Data
  https://solanacookbook.com/guides/serialization.html
* Debugging Solana Programs 
  https://solanacookbook.com/guides/debugging-solana-programs.html#facts

#### [Solana Playground]( https://beta.solpg.io/)
* Develop, deploy and test Solana programs in the browser. https://beta.solpg.io/


#### [Anchor: Smart Contract Framework](https://www.anchor-lang.com/)
* Intro to Programming on Solana
  https://www.anchor-lang.com/docs/intro-to-solana
* Install Anchor, Rust and Solana 
  https://www.anchor-lang.com/docs/installation
* Getting Started: Hello World
  https://www.anchor-lang.com/docs/hello-world
* High-level Overview
  https://www.anchor-lang.com/docs/high-level-overview
* The Accounts Struct
  https://www.anchor-lang.com/docs/the-accounts-struct
* The Program Module
  https://www.anchor-lang.com/docs/the-program-module
* Starter project: Tic-Tac-Toe
  https://www.anchor-lang.com/docs/tic-tac-toe
* Anchor CLI
  https://www.anchor-lang.com/docs/cli
* Anchor github repo - coral-xyz/anchor 
  https://github.com/coral-xyz/anchor


#### [Metaplex NFT documentation](https://docs.metaplex.com/)
* Understanding Programs
https://docs.metaplex.com/programs/understanding-programs
* Token Metadata
https://docs.metaplex.com/programs/token-metadata/
* Candy Machine
https://docs.metaplex.com/programs/candy-machine/
* Auction House
https://docs.metaplex.com/programs/auction-house/
* Gumdrop
https://docs.metaplex.com/programs/gumdrop/
* RPC Providers
https://docs.metaplex.com/resources/rpc-providers
* A Front End Minting Experience
https://docs.metaplex.com/guides/candy-machine-ui
* Community: Setting up a Solana Metaplex NFT Storefront in the Cloud
https://artifact-staking.medium.com/setting-up-a-solana-metaplex-nft-storefront-in-the-cloud-a10ea2490ed9
* Community: Solana and Metaplex FAQ
https://hackmd.io/@archaeopteryx/By4bpbA4F#Solana-and-Metaplex-FAQ
* Community: Candy Machine fee calculator
https://feecalc.live/

#### Solana Program Library
* https://github.com/solana-labs/solana-program-library

#### Solana Stack Exchange
* https://solana.stackexchange.com/?utm_source=solana.com

#### Create Solana App
* https://github.com/solana-developers/create-solana-app

#### [Solscan](https://solscan.io/)
  * Docs
    https://docs.solscan.io/
  * Account details 
    https://docs.solscan.io/browsing-the-site/transaction-details
  * Transaction details 
    https://docs.solscan.io/browsing-the-site/transaction-details
  * Fee Tracker 
    https://beta-analysis.solscan.io/public/dashboard/06d689e1-dcd7-4175-a16a-efc074ad5ce2


#### solana-web3.js
* https://solana-labs.github.io/solana-web3.js/
* https://github.com/solana-labs/solana-web3.js


#### Solana Deploy cheatsheet
* https://hackmd.io/@raza/deploy15

#### Solana Developer Changelog weekly podcast 
* https://www.youtube.com/watch?v=jIZXTkVaTps&list=PLilwLeBwGuK5-Qri7Pg9zd-Vvhz9kX2-R


-----------------


### Solana Architecture

Explaining Solana and its Innovations without technical jargon
https://learn.figment.io/tutorials/explaining-solanas-innovations-without-technical-jargon


8 Innovations that Make Solana the First Web-Scale Blockchain
https://medium.com/solana-labs/7-innovations-that-make-solana-the-first-web-scale-blockchain-ddc50b1defda

Solana’s Network Architecture
https://medium.com/solana-labs/solanas-network-architecture-8e913e1d5a40

* [Proof of History (POH) ](https://medium.com/solana-labs/proof-of-history-a-clock-for-blockchain-cf47a61a9274)— a clock before consensus;


* [Tower BFT ](https://medium.com/solana-labs/tower-bft-solanas-high-performance-implementation-of-pbft-464725911e79)— a PoH-optimized version of PBFT;
* [Turbine](https://medium.com/solana-labs/turbine-solanas-block-propagation-protocol-solves-the-scalability-trilemma-2ddba46a51db) — a block propagation protocol;
* [Gulf Stream](https://medium.com/solana-labs/gulf-stream-solanas-mempool-less-transaction-forwarding-protocol-d342e72186ad) — Mempool-less transaction forwarding protocol;
* [Sealevel](https://medium.com/solana-labs/sealevel-parallel-processing-thousands-of-smart-contracts-d814b378192) — Parallel smart contracts run-time;
* [Pipelining](https://solana.com/pipelining-in-solana-the-transaction-processing-unit/) — a Transaction Processing Unit for validation optimization
* [Cloudbreak](https://medium.com/solana-labs/cloudbreak-solanas-horizontally-scaled-state-architecture-9a86679dcbb1) — Horizontally-Scaled Accounts Database; and
* [Archivers](https://solana.com/archivers/) — Distributed ledger store

Solana Labs Architectural Security Review and Report
https://solana.com/solana-security-audit-2019.pdf

Solana Proof of Stake + Proof of History Primer
https://www.shinobi-systems.com/primer.html

RPC Infrastructure
https://solana.com/rpc

ok so what the $%#@ is the deal with solana anyway
https://2501babe.github.io/posts/solana101.html

Solana Validator 101: Transaction Processing
https://jito-labs.medium.com/solana-validator-101-transaction-processing-90bcdc271143

Solana-as-a-Service (SaaS)
https://twitter.com/kevin_lim9/status/1574598748881264640?s=20&t=V55xxZqnTggScJEQtbh2qw

What is Solana? SOL Explained with Animations
https://www.youtube.com/watch?v=1jzROE6EhxM&ab_channel=WhiteboardCrypto

How Staking SOL REALLY Works
https://www.youtube.com/watch?v=Tl5Xx8BiHSM&t=1s&ab_channel=KnoxTrades

High performance memory management for smart contracts
https://medium.com/solana-labs/high-performance-memory-management-for-smart-contracts-aa9b3bc950fb

Is Solana Decentralized? Understand How Solana Staking Works!
https://www.youtube.com/watch?v=xPCr7T3IUo4&ab_channel=KnoxTrades

Understanding Solana Consensus Protocol Better
https://www.reddit.com/r/solana/comments/rd3rp8/understanding_solana_consensus_protocol_better/


Proof-of-Stake (vs proof-of-work)
https://www.youtube.com/watch?v=M3EFi_POhps&ab_channel=SimplyExplained

Where does SOL inflation go exactly?
https://www.reddit.com/r/solana/comments/s1hhq4/where_does_sol_inflation_go_exactly/

Inside Solana’s Internal Scalability Test
https://medium.com/solana-labs/inside-solanas-internal-scalability-test-cce13aa8c859

How Solana Works and How it Works EVEN BETTER with Genesys Go
https://www.youtube.com/watch?v=4TSQrhc0xNE&ab_channel=KnoxTrades

Boot your Solana endpoint in seconds, not days.
https://www.quicknode.com/chains/sol

Solana Block Production & 1 Oct Outage Review
https://www.youtube.com/watch?v=7tGYT8j7AbE&ab_channel=Laine

Is Proof of History (PoH) pointless?
https://www.reddit.com/r/solana/comments/xqq9b2/is_proof_of_history_poh_pointless/
https://www.reddit.com/r/solana/comments/xqq9b2/comment/iqbsffl/?utm_source=share&utm_medium=web2x&context=3
https://www.reddit.com/r/solana/comments/xqq9b2/comment/iqb16kq/?utm_source=share&utm_medium=web2x&context=3







-----------------


### Developer Opportunities & Jobs

Solana Labs repo: Good first issues 
https://github.com/solana-labs/solana/labels/good%20first%20issue)

Solana Labs Github Projects newest issues
https://github.com/solana-labs/solana/issues

Solana Labs Github Projects 
https://github.com/solana-labs/solana/projects?type=classic
 
Superteam - Solana ecosystem opportunities
https://earn.superteam.fun/

Superteam - Solana Ecosystem Jobs
https://earn.superteam.fun/opportunities/category/jobs

Web3 Bounties
https://earn.superteam.fun/opportunities/category/bounties

Solana-related Frontend Dev Grants
https://earn.superteam.fun/opportunities/skill/front-end-dev?category=Grants

Solana Ecosystem - Backend Grants
https://earn.superteam.fun/opportunities/skill/back-end-dev


-----------------


