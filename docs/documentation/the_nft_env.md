
### Introduction

### Methods description

```
(async) checkIfUserWhitelisted(address) → {bool}
```
#### Description
Check if a string is a valid whitelised address.

#### Parameters
##### Name: address

- Type: string
- Description: valid ethereum address of the user.

#### Returns
true if the user is whitelisted, false otherwise.

```
(async) getChainId() → {int}
```
#### Description
Returns the current chain id.
#### Parameters
None

#### Returns
Return the chain current i as an integer.

```
(async) getMaxToMint() → {int}
```
#### Description
Returns the maximum NFTs that can be minted.

#### Returns
the maximum number of nfts that can be minted as integer.

```
(async) getMintFee() → {int}
```
#### Description
Return minting fees.

#### Returns
mint fees in wei.
You should divide the returned value by 10e18 to get the value in the native currency.

```
(async) getTotalSuply() → {int}
```
#### Description
Returns the total number of NFTs in circulation.

#### Returns
the maximum number of circulating NFTs as integer.

```
(async) getUserInstances(address) → {bool}
```
#### Description
Return the list of all the instances a user created, testnet and mainnet.

#### Parameters
##### Name: address

- Type: string
- Description: valid ethereum address of the user.

#### Returns
return a json file of all the urls of user instances.

```
(async) mintNftExtertnal1()
```
#### Description
Mint an integer number of NFTs The number of NFTs to be minted should be integrated in an html tag with id '#count'.

```
(async) mintNftExtertnal2(count) → {int}
```
#### Description
Mint #count of NFTs.

#### Parameters
##### Name: count

- Type: int
- Description: number of NFTs to be minted.

#### Returns
mint fees in wei.
You should divide the returned value by 10e18 to get the value in the native currency.
