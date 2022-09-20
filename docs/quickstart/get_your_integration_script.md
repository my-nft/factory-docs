After you create your NFT Kit in the <a href="https://factory.my-nft.io" target="_blank"> factory</a> page you can access your integration script <a href="https://my-nft.io/integration" target="_blank"> here</a>.

In this page you will find the following information:

1. A listing of all the NFT Kits you created, on testnets and mainnet
2. The integration information for every NFT Kit you have generated

The integration information are structured as follows:

### Example NFT collection website

This is an example minting website to allow you test the NFT Kit you created.

The URL of the example minting website is structured as follows:

1. `8496248`: the NFT Kit unique ID
2. `0x72ddbdc341bbfc00fe`: the first 20 characters of your wallet address
3. `4`: the `chainID` of the blockchain you are using

Example link: www.8496248.0x72ddbdc341bbfc00fe.4.my-nft.io

Every blockchain has a unique ID, ex `Ethereum`: `1`, `Rinkeby` testnet: `4`, ...

### NFT Kit integration script

This the script you will integrate in your website to be able to use NFT features.

The script URL looks like that:

https://www.8496248.0x72ddbdc341bbfc00fe.4.my-nft.io/static/nft-integration.js


Check the next section for instruction how to integrate it in your website.

You will also get access to an admin page to be able to control the smart contract you just deployed. A detailed description of the admin page is available in the section **Interact with the smart contract**.
