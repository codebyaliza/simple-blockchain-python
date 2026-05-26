# 🔗 Simple Blockchain in Python

A **mini blockchain** built from scratch in Python to demonstrate how cryptocurrencies like Bitcoin work under the hood.

## 🎯 What it does
- Creates blocks with transactions, timestamps, and hashes
- Uses **SHA-256** for cryptographic hashing
- Implements **Proof-of-Work** mining (find leading zeros)
- Validates chain integrity automatically
- Detects tampering — changing any transaction breaks the chain

## 📚 Key Concepts Covered
| Concept | How it works |
|---------|---------------|
| Hashing | SHA-256 generates unique block fingerprints |
| Mining | Nonce incremented until hash has `difficulty` leading zeros |
| Immutability | Changing any data invalidates all subsequent hashes |
| Consensus | `is_valid()` checks every block's hash & PoW |

## 🔬 Real-World Connection
- **Pending transactions** → Bitcoin's mempool
- **Mining** → Bitcoin's Proof-of-Work puzzle
- **Chain validation** → Bitcoin node consensus

## ▶️ Sample Output
