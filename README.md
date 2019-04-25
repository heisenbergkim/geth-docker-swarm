# Local Ethereum Network

The testnet consists out of multiple parts :
* 1 Bootnode - registers existing nodes on the network, discovery service.
* 2 Miners - Also called **sealers** with proof-of-authority. They validate the blocks. No RPC is exposed as they are required to be unlocked.
* 1 Node - This serves as **transaction relay** and is a fullnode that does not mine, is locked but has RPC exposed
* 2 Swarm nodes - These nodes make up the **peer-to-peer CDN**
* 1 Blockchain explorer - Lightweight web application to explore the blockchain through web application. 


