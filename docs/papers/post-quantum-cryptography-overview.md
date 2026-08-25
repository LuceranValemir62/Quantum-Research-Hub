# Post-Quantum Cryptography: A Systematic Overview

## 1. The Quantum Threat
- Shor's algorithm breaks RSA, ECC, DSA
- Timeline estimates for cryptographically-relevant quantum computers (CRQC)

## 2. NIST Standardization (2024)
### FIPS 203: ML-KEM (Module Lattice-based Key Encapsulation Mechanism)
- Based on CRYSTALS-Kyber
- Security levels 1, 3, 5

### FIPS 204: ML-DSA (Module Lattice-based Digital Signature Algorithm)
- Based on CRYSTALS-Dilithium

### FIPS 205: SLH-DSA (Stateless Hash-Based Digital Signature Standard)
- Based on SPHINCS+

### FIPS 206 (Planned): FN-DSA (FFT over NTRU-based Digital Signature)
- Based on FALCON

## 3. Migration Strategies
- Cryptographic agility
- Hybrid approaches (classical + PQC)
- Inventory and risk assessment

## References
[1] NIST. (2024). FIPS 203: Module-Lattice-Based Key-Encapsulation Mechanism Standard.
[2] Bernstein, D. J., & Lange, T. (2017). Post-quantum cryptography. Nature, 549(7671), 188-194.
