## Interact with the smart contract using the admin page

Your NFT Kit gives you access to a dedicated admin page to interact with your smart contract.

To access your dedicated admin page go to this url:
```
https://www.[3563188.0x72ddbdc341bbfc00fe.4].my-nft.io/admin
```
Replace the part between [] with your own link.

NB. You should connect the owner wallet address in metamask to be able to access the admin page.

This page gives you the following informations:

### Collection name

The name you choosed for the collection during the generation step

### Collection symbol

The symbol you choosed for the collection during the generation step

### Collection owner

This is the owner of the collection smart contract. The owner of this wallet address can operate several changes on the smart contract state (change mint price, whitelist address, ...)

### Funds wallet

This is the wallet to receive the NFTs sale funds

### NFT price

This the price per NFT during the sale in the native currency of the blockchain (ETH for Ethereum, BNB for Binance Smart Chain, MATIC for Polygon, ...)

### Max per wallet

This is the maximum numner of NFTs a wallet can mint during the sale.

### URI

This is the link to the ipfs folder with the NFTs content.

### Total minted

The number of NFTs already minted.

### Total sales

The total funds collected so far from the NFTs sale.

### Remaining

The number of NFTs remaining for mint.

### Total supply

The number of NFTs to ever be minted 

### Enable minting

When disabled, no body can mint an NFT from the smart contract.

You should enable it to launch the minting. This require sending a transaction to the blockchain and paying small gas fees.

### Freeze metadata

This is to be optionally called after your NFTs are revealed. It will freeze the NFT content and properties for ever.

NB. Don't use it if you are planning to do some modifications on your NFTs later !

### Enable smart contract whitelisting

This will allow only the whitelisted wallets to mint. These addresses will be sent to the smart contract using the specific method Smart Contract Batch Whitelist.

You should not use this whitelisting if you are on Ethereum blockchain and planning to whitelist a big number of addresses, the gas fees may be extremly high. In that cas use the following method.

### Enable gas free whitelisting

Same principale as the former. Just this one work with a different whitelisting concept.

It's a cheaper way to whitelist thousands of addresses on Ethereum Blockchain while paying only a small gas fees.

The principle is based on an aggregation of all the addresses in a merkle tree.

### Set NFT Price

Change the NFT price. Enter the value in native currency, not in wei.
Use the '.' instead of ','.

### Set max per wallet

Change the maximum number of NFTs a wallet can mint.

### Set metadata URI

This can help you change the NFTs content and properties after the collection smart contract is deployed.

You can use it to implement your NFT reveal strategy.

### Set collection owner

Transfer the collection ownership to a new wallet address.

### Mint too

This method can be used to airdrop free NFTs to a set of addresses separated by ','.

### Smart contract Batch Whitelist

Whitelist a batch of addresses on smart contract level.

### Gas free Batch whitelist

Whitelist a batch of addresses using the gas free approach.

### Check Gas Free whitelisting

Verify if a group of addresses is gas free whitelisted
