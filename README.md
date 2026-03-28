# Modern Cryptography — Mathematical Foundations and Implementation

- Explores the mathematical foundations behind classical and modern cryptography
- Implements Caesar, Vigenère, and Hill ciphers with full cryptanalytic attacks on each
- Builds RSA encryption and digital signatures from scratch using Euler's theorem and Miller-Rabin primality testing
- Demonstrates AES symmetric encryption (CBC & GCM), Diffie-Hellman key exchange, and SHA-256 hashing
- Analyses the quantum computing threat to current cryptographic standards
- All implementations are verified against SymPy's built-in functions

## How to Run

Open `ModernCryptography.ipynb` in JupyterLab and run all cells.

```bash
pip install numpy sympy matplotlib cryptography
jupyter lab ModernCryptography.ipynb
```