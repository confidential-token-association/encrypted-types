# 🔐 Encrypted Type Aliases

This repository defines encrypted type aliases.

## 📘 Overview

These Solidity `bytes32` aliases represent encrypted values, used for privacy-preserving smart contracts:

### Core Encrypted Types (e\*)

```solidity
type euint8 is bytes32;
type euint16 is bytes32;
type euint24 is bytes32;
...
type euint256 is bytes32;

type ebool is bytes32;

type eaddress is bytes32;

type ebytes1 is bytes32;
// ...
type ebytes32 is bytes32;

type ebytes64 is bytes32;
type ebytes128 is bytes32;
type ebytes256 is bytes32;
```

### External Encrypted Types (externalE\*)

```solidity
type externalEuint8 is bytes32;
type externalEuint16 is bytes32;
type externalEuint24 is bytes32;
...
type externalEuint256 is bytes32;

type externalExternalEbool is bytes32;
type externalEbytes1 is bytes32;
// ...
type externalEbytes32 is bytes32;

type externalEbytes64 is bytes32;
type externalEbytes128 is bytes32;
type externalEbytes256 is bytes32;
```

These types enable type-safe handling of encrypted data in contracts, support validation via proofs, and integrate with decryption oracles for confidential workflows.

## 📜 License

MIT
