# SafeStack Book Library

Private and public SafeStack books, articles, technical papers, and controlled documentation will be catalogued here as the collection grows.

## Current catalogue

| Title | Type | Pages | SHA-256 |
| --- | --- | ---: | --- |
| [Post-Quantum.pdf](Post-Quantum.pdf) | Technical document | 13 | `1231f8f601535e068fe067fc37e74c2032ecfaa3380596d4a93ed48df4bf3844` |
| [API_Naudojimas_Terminale.pdf](API_Naudojimas_Terminale.pdf) | Technical guide | 9 | `2a0efa03917037f4a58e973fbd0c7d00bbddd3ff33de4fc4e171b8213e25de59` |
| [GitHub dokumentacijos pagrindai.pdf](GitHub%20dokumentacijos%20pagrindai.pdf) | Practical documentation | 5 | `7626875afa26db43928093ef4f33442fcd4cc3aa8cb142956cce5aab68f56de5` |
| [Kibernetinio_Saugumo_Pilnas_Gidas.xdoc.pdf](Kibernetinio_Saugumo_Pilnas_Gidas.xdoc.pdf) | Security guide (Part 1) | 5 | `93a5d49bdca504268de4fd24871ea4c041e047fe39ee7d69c77543e3e5522858` |
| [Kibernetinio_Saugumo_Pilnas_Gidas_Dalis_2.xdoc.pdf](Kibernetinio_Saugumo_Pilnas_Gidas_Dalis_2.xdoc.pdf) | Security guide (Part 2) | 4 | `f6aa322b7af969f314251ab85ae5ca877b3f0aaef9dc7a0d93373ff8e551834e` |
| [SHA256_Tikrinimas_Terminale.xdoc.pdf](SHA256_Tikrinimas_Terminale.xdoc.pdf) | Verification guide | 4 | `550293ab6e45eaeaab72eed866b7a5e5102d1aff09ee96441f328e4a133fa8aa` |
| [NIST_FIPS_203_ML-KEM.pdf](NIST_FIPS_203_ML-KEM.pdf) | Official PQC Standard (ML-KEM) | 56 | `fe1f12f32a7e44ec9fdebbf400cda843a40b506dee676725234dc6f7923b6cac` |
| [NIST_FIPS_204_ML-DSA.pdf](NIST_FIPS_204_ML-DSA.pdf) | Official PQC Standard (ML-DSA) | 65 | `57239b9f84c03227eda3ca0991204dc7764c79af9ce2e6824eda774918d46b6b` |
| [NIST_FIPS_205_SLH-DSA.pdf](NIST_FIPS_205_SLH-DSA.pdf) | Official PQC Standard (SLH-DSA) | 61 | `8ef34228276f3386d23cb0da8c14592b8cfb0db3358016bba64df7a004f8d13d` |

The recorded SHA-256 value is the integrity reference for each repository copy.

## Collection cover

```text
             +----------------------------------+
            /   S A F E S T A C K              /|
           /       BOOK LIBRARY               / |
          +----------------------------------+  |
          |                                  |  |
          |          POST-QUANTUM            |  |
          |       TECHNICAL COLLECTION       |  |
          |                                  |  |
          |              [ 01 ]              |  /
          |          13 PAGES / PDF          | /
          +----------------------------------+/

        +------------+ +------------+ +------------+
        |  BOOK 01   | |  PAPERS    | |  DOCS      |
        | POST-      | | NIST PQC   | | GUIDES &   |
        | QUANTUM    | | FIPS 203-5 | | TERMINAL   |
        +------------+ +------------+ +------------+
        =================================================
                    SAFE / READ / VERIFY
```

The cover is an ASCII index for the collection. Each future book, article, or technical document receives its own catalogue entry, checksum, and clearly labelled source or licence.

## Library rules

- Add one document per file with a descriptive filename.
- Add every new item to the catalogue with its type, page count, source, and SHA-256 checksum.
- Keep private customer data, credentials, private keys, and confidential operational records outside this repository.
- Publish a document only when its author, owner, licence, and redistribution rights are known (respect author copyrights and open licensing).
- Preserve the original file when a translated, annotated, or derived version is needed; place the derivative beside it and label the relationship clearly.

## PDF verification

To verify the integrity of all documents in the library:

```bash
shasum -a 256 *.pdf
```

To verify an individual document:

```bash
shasum -a 256 Post-Quantum.pdf
```

The output must match the checksum in the catalogue. A checksum verifies file integrity; it does not prove authorship, safety, or redistribution rights.

## Recommended literature & official sources

In alignment with the SafeStack philosophy (**SAFE / READ / VERIFY**, Zero Trust, and cryptographic integrity), the following literature is recommended. We respect authors' intellectual property and direct readers to authorized publishers and open educational repositories.

### Open-access & free authorized resources
* **[Security Engineering: A Guide to Building Dependable Distributed Systems](https://www.cl.cam.ac.uk/archive/rja14/book.html)** (3rd Edition) – *Ross Anderson*  
  *Freely provided online by the author at the University of Cambridge archive.*
* **[Building Secure and Reliable Systems](https://sre.google/books/building-secure-and-reliable-systems/)** – *Heather Adkins, Betsy Beyer, Paul Blankinship, Piotr Lewandowski, Ana Oprea, Adam Stubblefield (Google)*  
  *Officially provided free to read by Google SRE.*
* **[NIST Post-Quantum Cryptography Standardization](https://csrc.nist.gov/projects/post-quantum-cryptography)** – *National Institute of Standards and Technology*  
  *Public domain technical specifications establishing global quantum-resistant algorithms.*

### Essential core literature
* **Serious Cryptography: A Practical Introduction to Modern Encryption** – *Jean-Philippe Aumasson* (No Starch Press)
* **Applied Cryptography: Protocols, Algorithms, and Source Code in C** – *Bruce Schneier* (John Wiley & Sons)
* **Extreme Privacy: What It Takes to Disappear** – *Michael Bazzell* (IntelTechniques)
* **Threat Modeling: Designing for Security** – *Adam Shostack* (John Wiley & Sons)
* **The Art of Invisibility** – *Kevin Mitnick* (Little, Brown and Company)
* **Data and Goliath: The Hidden Battles to Collect Your Data and Control Your World** – *Bruce Schneier* (W. W. Norton & Company)
