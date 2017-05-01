# Crypto-Tools

## KeccakTools

*A set of C++ classes that can help analyze the Keccak sponge function family*

* Developers: Guido Bertoni, Joan Daemen, Michael Peeters, Gilles Van Assche
* [Direct download](http://keccak.noekeon.org/KeccakTools-3.3.zip)
* [Official website](http://keccak.noekeon.org/KeccakTools-doc/)

KeccakTools is a set of C++ classes aimed as an assitant in analyzing the sponge function family `Keccak`. These classes and methods were used to obtain the results reported in the paper `Differential propagation anaylsis of Keccak` presented at FSE 2012 (available here [IACR ePrint 2012/163](http://eprint.iacr.org/2012/163)).

## S-Box Mixed-Integer Linear Programming tool

*Toolkit for Counting Active S-boxes using Mixed-Integer Linear Programming (MILP)*

* Developer: Nicky Mouha
* [Direct download](http://www.ecrypt.eu.org/tools/uploads/sbox-milp.zip)

This toolkit can be used to prove the security of cryptographic ciphers against linear and differential cryptanalysis. This toolkit generates Mixed-Integer Linear Progreamming problem which counts the minimum number of (linearly or differentially) active S-boxes for a given cipher. The toolkit currently supports AES and xAES (both in the single-key and related-key setting), as well as Enocoro-128v2 (in the related-key setting). The paper that introduced this tookkit is [available online](https://www.esat.kuleuven.be/cosic/publications/article-2080.pdf).

## HashClash

*Framework for MD5 & SHA-1 Differential Path Construction and Chosen-Prefix Collisions for MD5*

* Developer: Marc Stevens
* Repo

This framework contains tools for the constructions of differential paths for MD5 and SHA-1, including chosen-prefix collisions for MD5.

## ARX Toolkit

*The ARX toolkit is a set of tools to study ARX ciphers and hash functions*

* Developer: Gaetan Leurent
* [Official website](http://www.di.ens.fr/~leurent/arxtools.html)

The ARX toolkit is a set of tools to study ARX ciphers and hash functions. This tookkit was presented at the SHA-3 conference in March 2012.

## Information Set Decoding

*A tool for information set decoding*

* Developers: Unknown?
* [Official source](https://github.com/isd-dev/isd/downloads)

This library, written in C++ that is efficient at finding low weight codewords of a linear code using information set decoding.

## Linear Hull Cryptanalysis of PRESENT

*A tool to compute linear hulls for PRESENT cipher*

* Developer: Bingsheng Zhang
* [Direct download](http://www.ecrypt.eu.org/tools/uploads/present-linear-hull.zip)
* [Paper](http://dx.doi.org/10.1007/978-3-642-10433-6_5)

This tool computes linear hulls for the original PRESENT cipher. It confirms and even improves on the predicted bias (and the corresponding attack complexities) of conventional linear relations based on a single linear trail.

## CodingTool Library

*Tool for cryptanalysis based on coding theory*

* Developer: Tomislav Nad
* [Direct download](https://www.iaik.tugraz.at/content/research/krypto/codingtool/downloads/CodingTool-0.9.zip)
* [Official websit](http://www.iaik.tugraz.at/content/research/krypto/codingtool/)

The CodingTool library is a collection of tools to use techniques from coding theory in cryptanalysis. The core part is an implementation of a probabilistic algorithm to search for code words with low Hamming weight. Additional functionalities like shortening and puncturing of a linear code or adding a weight to each bit of a code word are implemented. Furthermore, the library provides data structures to assist the user in creating a linear code for a specific problem. An easy to use interface to the provided algorithms, powerful data structures and a command line parser reduces the implementation work of a cryptanalyst to a minimum.

