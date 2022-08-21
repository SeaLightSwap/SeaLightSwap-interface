# Sea-Light-Swap-V2
Decentralized Exchange On Polygon Network

SeaLightSwap Interface 

An open source interface for SeaLightSwap -- a protocol for decentralized exchange of Ethereum tokens.

Website: https://SealightSwap.org

Accessing the SealightSwap Interface

To access the SeaLightSwap Interface,visit sealightswap.org.

Development

Install Dependencies

yarn
Run

yarn start
Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

Make a copy of .env named .env.local
Change REACT_APP_NETWORK_ID to "{YOUR_NETWORK_ID}"
Change REACT_APP_NETWORK_URL to e.g. "https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}"
Note that the interface only works on testnets where both Uniswap V2 and multicall are deployed. The interface will not work on other networks.

Contributions

Please open all pull requests against the master branch. CI checks will run against all PRs.
