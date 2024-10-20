# Cryptographic Exercises and Zero Knowledge Proofs

This repository contains a collection of exercises and implementations related to cryptography, zero-knowledge proofs, and discrete logarithms. The code is written primarily in Rust and includes detailed tests for each implementation.

## Exercises

### 1. ZKP for Discrete Logarithms (DLOG)

**Location**: `zkp_dlog/`

This project demonstrates a zero-knowledge proof for discrete logarithms using Rust. The proof uses the Fiat-Shamir heuristic to prove knowledge of a secret `x` such that:
`y = g^x (mod p)`

#### How to Run the ZKP DLOG Project:

1. Navigate to the `zkp_dlog` folder:

   ```bash
   cd zkp_dlog
   ```

2. Run the tests:

   ```bash
   cargo test
   ```

## Dependencies

### Rust Projects

Make sure you have Rust installed. You can install Rust via rustup:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

```bash
cargo test
cargo run
```
