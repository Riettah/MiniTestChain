# Mini C++ Blockchain

A simple practical Blockchain implemented in C++ using SHA-256 and P-O-F.


## Description

This project includes:

- Blocks containing index, timestamp, data, nonce, and previous hash
- SHA-256 hashing for block integrity
- Proof-of-Work mining with adjustable difficulty
- A simple blockchain that links blocks together


- Each block has a hash computed with SHA-256.
- Mining searches for a nonce so the hash has `N` leading zeros.
- Blocks are chained by storing the previous block’s hash.