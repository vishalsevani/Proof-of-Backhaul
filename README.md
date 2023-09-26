# Proof-of-Backhaul

Proof of Backhaul is a blockchain  based decentralised speed-test which can be 
used by a “payer” to determine the backhaul capacity of a “prover” with the help 
of a pool of “challengers“ who send the challenge traffic to the prover. 

For more details about Proof of Backhaul service and the different
terms mentioned above, please read: [GitBook link](https://witness-chain.gitbook.io/witness-chain/proof-of-backhaul/introduction)

## Demo

The DEMO of Proof of Backhaul in action is at:
[DEMO](https://witness-chain.gitbook.io/witness-chain/proof-of-backhaul/demo-videos)

## Running a Speed-test

We host our Proof of Backhaul service at 
[site](https://pob.witnesschain.com/static/home.html). You can run speed-test for your
device via the above site. For this you need to first install Phantom wallet for your
chrome browser and then run a "prover" program on your device.

### Install Phantom wallet

We have integrated our Proof of Backhaul with [Solana](https://solana.com/) blockchain.
To run a speed test using our sevice, first you need to install a Solana wallet,
[Phantom](https://chrome.google.com/webstore/detail/phantom/bfnaelmomeimhlpmgjnjophhpkkoljpa), for
your chrome browser. Phantom will create a Solana account for you with Solana wallet address. 

### Airdrop Solana SOL for Testnet

You need to airdrop Solana tokens, SOL for Testnet to you Phantom Solana wallet address. For
this add the Solana testnet wallet address in Phantom at the following site, 
[Solana faucet](https://solfaucet.com/). More details about airdropping Test SOLs is [at](https://www.quicknode.com/guides/solana-development/getting-started/a-complete-guide-to-airdropping-test-sol-on-solana).

### Run a prover

After you have added SOL for Testnet to your Solana wallet, you can need to run a prover on your device.
To set-up and run a prover follow the link below, [Prover Set-up](https://witness-chain.gitbook.io/witness-chain/proof-of-backhaul/getting-set-up/as-a-prover). 
After you have set-up the prover, register it with our service following the instructions in the link above.

### Initiate a challenge

After you have registered your prover, you can run speed-test for it. For this, login to Proof of Backhaul 
[dashboard](https://pob.witnesschain.com/static/home.html#) via your Phantom wallet. After you login, open
the [Prover explorer](https://pob.witnesschain.com/static/prover-map.html). You will see a map of provers.
Your prover will be shown in the map at the location where it is running. Right click on your prover and then
click "Start challenge". The challenge will ask you to confirm the initiation via your Phantom wallet. The speed test
will then run after executing the transaction on Solana Testnet. After the Solana transaction is over, you can see 
the results of the speedtest by right clicking your prover.
