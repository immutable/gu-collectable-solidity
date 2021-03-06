
# gu-collectable-solidity

A thin wrapper of the Open Zeppelin ERC721 contracts to allow for some custom logic for each token type. Collectables 'delegate' their token-specific logic to another contract (their Delegate) - when it can be minted, when it can be transferred etc. The 'type' of an item is denoted by its delegate id, and the delegate itself can store additional properties if necessary/desired.

Currently deployed on mainnet at: [0xa5e5be69c923c701ae6ac8f1f5936af3ae610c68](https://etherscan.io/address/0xa5e5be69c923c701ae6ac8f1f5936af3ae610c68)

| ID | Name | Delegate |
|:---|:----|:-----|
| 0 | imToken Card Back | [0xe9813b3ac3fd938d21e47d10987f58914e6ff1fd](https://etherscan.io/address/0xe9813b3ac3fd938d21e47d10987f58914e6ff1fd) |
| 1 | - | [0xfaf68b886d48a882134e7a75e083a563ed3af593](https://etherscan.io/address/0xfaf68b886d48a882134e7a75e083a563ed3af593) |
| 2 | CK Statue | [0xc41dce1b128378d5262890800bf4dfae6e84793a](https://etherscan.io/address/0xc41dce1b128378d5262890800bf4dfae6e84793a) |

Metadata will be here: https://api.godsunchained.com/collectable/{id}.

