## Get Started

Start your Nolaris node by running the following command on a device that is connected to the Internet through Starlink:

```shell
./nolaris-node -b <Your Ethereum Address>
```

The Ethereum address in the argument is the address to receive mining reward. Only one node will get reward per Starlink device at the same time.

Node will also start a web dashboard at `127.0.0.1:8001` by default, which can be changed using `--web-http` argument. You will need to change the listening address (e.g. `0.0.0.0:8001`)if you want to access the web dashboard from a different device.

When your node is up and running, it will receive cryptographic proofs from validators periodically, which can be used to claim reward by submitting it to the chain. To submit it to the chain, open the web dashboard, connect to MetaMask, and click the Claim button. Currently, Nolaris is running on Ethereum Sepolia testnet, so you will need to change to Sepolia network in MetaMask before claiming.