## Plasma

- Vitalik Buterin, Joseph Poon
- aug.2017 project started
- framework of secondary chains 
- communicate as little as possible with main chain
- blockchain tree - numerous smaller chains created on top of main chain
- called Plasma chains
- built with smart contracts, merkle trees
- unlimited smaller chains, copies of the parent chain
- additional chains can be created on any chain
- a plasma chain is a customizable smart contract
- allows flexibility for differet use-case scenarios
- main chain less congested - plasma chains serving different purposes and helping with load on main chain/
- communication between chains - fraud proofs - security
- root chain keeps network secure, punishes bad actors
- a plasma chain can use its own consensus algorithm 
- fraud proof exists so users can report dishonest nodes, protect their funds, and exit the transaction 
- fraud proof = file complaint
- uses MapReduce to verify data within a tree of chains in order to increase efficiency
- mass exit problem: many users exit their plasma chain at the same time and flood the root chain.
- user assets can fall back to root chain in event of a security failure on plasma chain. 
- 
- plasma mvp: transactions occur outside of ethereum
- deposits and withdrawls, entry and exit points handled on smart contract
- plasma applications: except for assets/ data going in/ out of smart contract can be handled off-chain
- state commitment: store compressed version of application cryptographically
- use merkle trees - commitments are save points for application
- 
- exiting: use commitments when leaving a plasma chain
- to withdraw money from application user proves to smart contract they have money to withdraw. This can be done with merkle proof. 
- 
-
- PLASMA MVP:
- simple UTXO-based plasma chain
- enable high-throughput payment transactions
- does not support scripts or smart contracts
- 