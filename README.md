# Cryptography Course

Jupyter notebooks with laboratory exercises and solutions for a university cryptography course. Each lab focuses on a different topic, from classical symmetric ciphers to modern public-key and homomorphic schemes.

## Requirements

- Python 3.10 or newer
- Jupyter Notebook or JupyterLab
- Common libraries used across the labs: `numpy`, `matplotlib`, `secrets`, `math`

Install dependencies as needed before running a notebook:

```bash
pip install jupyter numpy matplotlib
```

## Labs

| Lab | Topic | Notebook |
|-----|-------|----------|
| Lab 2 | Primality tests, prime generation, extended Euclidean algorithm | `Lab2/Solution.ipynb` |
| Lab 3 | DES block cipher (key schedule, Feistel network, encryption) | `Lab3/Solution.ipynb` |
| Lab 4 | Diffie-Hellman key exchange, discrete logarithm (BSGS), RSA | `Lab4/Diffie-Hellman(2025)-ver2.ipynb`, `Lab4/Kryptosystem RSA(2025).ipynb` |
| Lab 5 | SHA-256 hash function (manual bit-level implementation) | `Lab5/SHA-2(256)-version-2025.ipynb` |
| Lab 6 | Lattice-based cryptography and the GGH scheme (Babai, LLL) | `Lab6/Lattice-based-cryptography-GGH-laboratory.ipynb` |
| Lab 7 | Homomorphic encryption (RSA, Paillier, trivial FHE, array operations) | `Lab7/Laboratorium_6_4students.ipynb` |

## Usage

Open the repository in Jupyter and run the cells in order from top to bottom. Some labs depend on earlier work (for example, RSA uses primality testing ideas from Lab 2).

```bash
jupyter notebook
```

## Repository structure

```
Lab2/   Primality and number theory
Lab3/   Symmetric cryptography (DES)
Lab4/   Asymmetric cryptography (DH, RSA)
Lab5/   Cryptographic hash functions (SHA-256)
Lab6/   Lattice cryptography (GGH)
Lab7/   Homomorphic encryption
```

## License

See [LICENSE](LICENSE) for details.
