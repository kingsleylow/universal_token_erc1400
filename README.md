**ERC1400** is a hybrid token standard precisely designed for the use case of tokenised financial assets.

It achieves this by being:
- Backward compatible with ERC-20 and easily extended to be compatible with ERC-777.

- Consists of a suite of other standards:
1. ERC-1066
2. ERC-1410
3. ERC-1411
4. ERC-1462
5. ERC-1594
6. ERC-1600
7. ERC-1643
8. ERC-1644

Security token requirements:

- MUST have a standard interface to query if a transfer would be successful and return a reason for failure.
- MUST be able to perform forced transfer for legal action or fund recovery.
- MUST emit standard events for issuance and redemption.
- MUST be able to attach metadata to a subset of a token holder's balance such as special shareholder rights or data for transfer restrictions.
- MUST be able to modify metadata at time of transfer based on off-chain data, on-chain data and the parameters of the transfer.
- MUST support querying and subscribing to updates on any relevant documentation for the security.
- MUST be ERC-20 compatible.
- MAY require signed data to be passed into a transfer transaction in order to validate it on-chain.
- SHOULD not restrict the range of asset classes across jurisdictions which can be represented.
- COULD be ERC-777 compatible.
