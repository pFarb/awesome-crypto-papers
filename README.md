# Awesome crypto papers

A curated list of cryptography papers, articles, tutorials and howtos.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

### Notes 

The goal of this list is to provide educational reading material for different levels of cryptographic knowledge. I started it because my day job onboarding engineers at [Cossack Labs](https://www.cossacklabs.com) includes educating them in cryptographic matters and giving advise what to read on specific topics, and that involves finding the same materials repeatedly. Hopefully, it will be useful for someone else as well.

This list intends to capture most of the classic papers necessary to get into certain topics in it's historic context, not bleeding edge (because it moves as you read this). Due to nature of my work, many subjects or important papers are not covered here, it is not intentional and everyone is welcome to contribute/correct anything.

### Contributing



## Contents

* Introducing people to data security and cryptography
  * Cryptography
  
* Books

## The list

### Introducing people to data security and cryptography

#### Simple: cryptography for non-engineers

* [Nuts and Bolts of Encryption: A Primer for Policymakers](https://www.cs.princeton.edu/~felten/encryption_primer.pdf)
* [Keys under Doormats](https://dspace.mit.edu/bitstream/handle/1721.1/97690/MIT-CSAIL-TR-2015-026.pdf) or why cryptography shouldn't be backdoored, by a all-star committee of crypto researches from around the world. 

#### Brief engineer-oriented introductions

* [An Overview of Cryptography](http://www.garykessler.net/library/crypto.html) - by Gary C. Kessler.
* [Using Encryption for Authentication in Large Networks](http://inst.eecs.berkeley.edu/~cs268/sp02/cached_papers/needham.pdf) - by Needham, Schroeder: this is were crypto-based auth starts.

### Specific topics

#### Hashing

* [FIPS 198-1: HMACs](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.198-1.pdf) - The Keyed-Hash Message Authentication Code FIPS document
* [FIPS 202: SHA3](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.202.pdf) - SHA-3 Standard: Permutation-Based Hash and Extendable-Output Functions
* [Birthday problem](https://en.wikipedia.org/wiki/Birthday_problem) - The best simple explanation of math behind [birthday attack](https://en.wikipedia.org/wiki/Birthday_attack).

#### Secret key cryptography

* [FIPS 197](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf) - AES FIPS document.
* [List of proposed operation modes of AES](http://csrc.nist.gov/groups/ST/toolkit/BCM/modes_development.html), maintained by NIST.
* [Recomendation for Block Cipher modes of operation: Methods and Techniques](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-38a.pdf).
* [Stick figure guide to AES](http://www.moserware.com/2009/09/stick-figure-guide-to-advanced.html) - if stuff above was a bit hard or you're looking for a good laugh.

#### Public key cryptography: General and DLP

* [New Directions in Cryptography](https://www-ee.stanford.edu/~hellman/publications/24.pdf) - seminal paper by Diffie and Hellman, introducing public key cryptography and key exchange/agreement protocol.
* [RFC 2631: Diffie-Hellman Key Agreement](https://tools.ietf.org/html/rfc2631) - an explanation of the Diffie-Hellman methon in more engineering terms.
* [A Method for Obtaining Digital Signatures and Public-Key Cryptosystems](https://people.csail.mit.edu/rivest/Rsapaper.pdf) -  original paper introducing RSA algorithm. 
* [RSA Algorithm](http://www.di-mgt.com.au/rsa_alg.html) - rather education explanation of every bit behind RSA.
* [Secure Communications Over Insecure Channels ](http://www.merkle.com/1974/PuzzlesAsPublished.pdf) - paper by R. Merkle,   predated "New directions in cryptography" though it was published after it. The Diffie-Hellman key exchange is an implementation of such a Merkle system.
* [On the Security of Public Key Protocols ](http://www.cs.huji.ac.il/~dolev/pubs/dolev-yao-ieee-01056650.pdf) - Dolev-Yao model is a formal model, used to prove properties of interactive cryptographic protocols.
* [How to Share a Secret](https://cs.jhu.edu/~sdoshi/crypto/papers/shamirturing.pdf) - A safe method for sharing secrets.
* [Twenty Years of Attacks on the RSA Cryptosystem](http://crypto.stanford.edu/~dabo/pubs/papers/RSA-survey.pdf) - great inquiry into attacking RSA and it's internals, by Dan Boneh. 

#### Public key cryptography: Elliptic-curve crypto

* [Elliptic Curve cryptography: A gentle introduction](http://andrea.corbellini.name/2015/05/17/elliptic-curve-cryptography-a-gentle-introduction/)
* [Explain me like I'm 5: How digital signatures actually work](http://blog.oleganza.com/post/162861219668/eli5-how-digital-signatures-actually-work) - EdDSA explained with ease and elegance.
* [Elliptic Curve Cryptography: finite fields and discrete logarithms](http://andrea.corbellini.name/2015/05/23/elliptic-curve-cryptography-finite-fields-and-discrete-logarithms/)
* [Detailed Elliptic Curve cryptography tutorial](https://www.johannes-bauer.com/compsci/ecc/)
* [Elliptic Curve Cryptography: ECDH and ECDSA](http://andrea.corbellini.name/2015/05/30/elliptic-curve-cryptography-ecdh-and-ecdsa/)
* [Elliptic Curve Cryptography: breaking security and a comparison with RSA](http://andrea.corbellini.name/2015/06/08/elliptic-curve-cryptography-breaking-security-and-a-comparison-with-rsa/)
* [Elliptic Curve Cryptography: the serpentine course of a paradigm shift](http://eprint.iacr.org/2008/390.pdf) - historic inquiry into development of ECC and it's adoption.
* [Let's construct an elliptic curve: Introducing Crackpot2065](http://blog.bjrn.se/2015/07/lets-construct-elliptic-curve.html)
* [Explicit-Formulas Database](http://www.hyperelliptic.org/EFD/) - for many elliptic curve representation forms.

#### Zero Knowledge Proofs

* [How to construct zero-knowledge proof systems for NP](http://www.wisdom.weizmann.ac.il/~oded/gmw1.html) - classic paper by Goldreich,  Micali and Wigderson.
* [Proofs that yield nothing but their validity and a Methodology of Cryptographic protocol design] (http://www.math.ias.edu/~avi/PUBLICATIONS/MYPAPERS/GMW86/GMW86.pdf) - by Goldreich,  Micali and Wigderson, a relative to the above. 
* [A Survey of Noninteractive Zero Knowledge Proof System and Its Applications](https://www.hindawi.com/journals/tswj/2014/560484/)
* [How to Prove a Theorem So No One Else Can Claim It](http://www.mathunion.org/ICM/ICM1986.2/Main/icm1986.2.1444.1451.ocr.pdf) - by Manuel Blum
* [Information Theoretic Reductions among Disclosure Problems](http://crypto.cs.mcgill.ca/~crepeau/BCR86.pdf) - Brassau et al.
* [Knowledge complexity of interactive proof systems](http://groups.csail.mit.edu/cis/pubs/shafi/1989-siamjc.pdf) - by GoldWasser, Micali and Rackoff. Defining computational complexity of "knowledge" within zero knowledge proofs. 
* [A Survey of Zero-Knowledge Proofs with Applications to Cryptography](http://www.austinmohr.com/work/files/zkp.pdf) - great intro on original ZKP protocols.

#### Homomorphic encryption

* The Swiss Army Knife of Cryptography [1](https://windowsontheory.org/2012/05/01/the-swiss-army-knife-of-cryptography/) [2](https://windowsontheory.org/2012/05/02/building-the-swiss-army-knife/)

#### Key Management

* [Recommendation for Key Management – Part 1: General](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-57pt1r4.pdf) - methodologically very relevant document on goals and procedures of key management. 

#### Cryptoanalysis

I haven't done anything 

#### Math

* [PRIMES is in P](https://www.cse.iitk.ac.in/users/manindra/algebra/primality_v6.pdf) - unconditional deterministic polynomial-time algorithm that determines whether an input number is prime or composite.

### Books

That seems somewhat out of scope, isn't it? But these are books only fully available online for free. Read them as a sequence of papers if you will.

* [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/) - by Dan Boneh and Victor Shoup. A well-balanced introductory course into cryptography, a bit of cryptoanalysis and cryptography-related security.
* [CrypTool book](https://www.cryptool.org/en/ctp-documentation/ctbook) - predominantly mathematically oriented information on learning, using and experimenting cryptographic procedures.
* [Handbook of Applied Cryptography](http://cacr.uwaterloo.ca/hac/) - by Alfred J. Menezes, Paul C. van Oorschot and Scott A. Vanstone. Good classical introduction into cryptography and ciphers.
* [The joy of Cryptography](http://web.engr.oregonstate.edu/~rosulekm/crypto/) - by Mike Rosulek. A lot of basic stuff covered really well. No ECC.
* [A Computational Introduction to Number Theory and Algebr](http://www.shoup.net/ntb/) - by Victor Shoup, excellent starters book on math universally used in cryptography. 


### Lectures and educational courses

* [Understanding cryptography: A textbook for Students and Practitioners](http://www.crypto-textbook.com/) - Textbook, great lectures and problems to solve.
* [Crypto101](https://www.crypto101.io/) - Crypto 101 is an introductory course on cryptography, freely available for programmers of all ages and skill levels.
* [a Course in Cryptography](https://www.cs.cornell.edu/courses/cs4830/2010fa/lecnotes.pdf) - Lecture notes by Rafael Pass, Abhi Shelat

### Online crypto challenges 

Not exactly papers, but crypto challenges are awesome educational material.

* [Cryptopals crypto challenges](https://cryptopals.com/)

