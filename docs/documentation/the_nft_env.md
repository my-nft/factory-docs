# Introduction

## Methods description

---

```
(async) checkIfUserWhitelisted(address) → {bool}
```

#### Description
Check if a string is a valid whitelisted address.

#### Parameters

##### Name: address

- Type: string
- Description: valid Ethereum address of the user

#### Returns
True if the user is whitelisted, false otherwise.

---

```
(async) getChainId() → {int}
```

#### Description

Returns the current chain id.

#### Parameters

None

#### Returns

Returns the current `chainID` as an integer.

---

```
(async) getMaxToMint() → {int}
```

#### Description

Returns the maximum NFTs that can be minted.

#### Returns

The maximum number of NFTs that can be minted as an integer.

---

```
(async) getMintFee() → {int}
```

#### Description

Returns minting fees.

#### Returns

Returns mint fees in `wei`.

The returned value should be divided by `10e18` to get the value in the native currency.

---

```
(async) getTotalSuply() → {int}
```

#### Description

Returns the total number of NFTs in circulation.

#### Returns

The maximum number of circulating NFTs as integer.

---

```
(async) getUserInstances(address) → {bool}
```

#### Description

Returns the list of all the instances that a user has created in `testnet` and `mainnet`.

#### Parameters

##### Name: address

- Type: string
- Description: Valid ethereum address of the user.

#### Returns

Returns a json file of all the URLs of user instances.

---

```
(async) mintNftExtertnal1()
```

#### Description

Mint an integer number of NFTs.

The number of NFTs to be minted should be integrated using an HTML tag with id `#count`.

---

```
(async) mintNftExtertnal2(count) → {int}
```

#### Description

Mint `#count` of NFTs.

#### Parameters

##### Name: count

- Type: int
- Description: number of NFTs to be minted.

#### Returns

Mint fees in `wei`.

The returned value should be divided by `10e18` to get the value in the native currency.
