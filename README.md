#Timelock: Fault-Tolerant Trustless Consensus through Time-locked Staking

Existing proof-of-stake cryptocurrency protocols involve participants staking currency for a chance to be the creator of the next block. The blockmaker is selected based on their stake and/or the time their stake has been locked away for. The primary problem with this style of proof-of-stake is that there is nothing at stake as particpants can stake currency on multiple forks of the blockchain. 

In the Timelock protocol, staked currency is locked away when a new block is created rather than before the blocks creations. The locked currency is freed after a certain amount of time has elapsed. The locking of the currency Participants can stake currency on multiple chain forks but their stake is only locked when a block is created. This makes it progressively more difficult for a malicious participant to build further blocks on any of the chain forks they have previously created a block on. 

In order to for a block to be created in the Timelock protocol, 1/3 of the total currency in circulation must be staked and the staked currency is locked away from 10 blocks. Suppose a malicious participant stakes controls 1/3 of the total currency in the network and creates a block. 



