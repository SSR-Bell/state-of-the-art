
# awesome-verifiable-streaming [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a curated list of resources about **Verifiable Streaming**. It is designed to have a central place where everyone can find research literature on verifiable streaming as well as their implementations.


## Contents

- [Theory](#theory)
	- [Introductory Papers](#introductory-papers)
	- [Authenticated Data Structures](#authenticated-data-structures)
	- [Proof-Carrying Data](#proof-carrying-data)
	- [Streaming Interactive Proofs](#streaming-interactive-proofs)
	- [Surveys](#surveys)
	- [Applications](#applications)
	- [Blogs](#blogs)
	- [Videos](#videos)
- [Implementations](#implementations)  


## Theory

### Introductory Papers

- 2012 - [Verifiable data streaming](https://eprint.iacr.org/2013/038) [Schröder-Schröder]
- 2015 - [VeriStream – A Framework for Verifiable Data Streaming](https://link.springer.com/chapter/10.1007/978-3-662-47854-7_34) [Schröder-Simkin]
- 2015 - [Semi-Streaming Algorithms for Annotated Graph Streams](https://arxiv.org/abs/1407.3462#:~:text=We%20put%20forth%20the%20notion,text%7Bpolylog%7D(n)).) [Justin Thaler]
- 2015 - [Verifiable Stream Computation and Arthur-Merlin Communication](http://dimacs.rutgers.edu/~graham/pubs/papers/oipccc.pdf) [Chakrabarti et al.]
- 2015 - [Streaming Verification in Data Analysis](https://arxiv.org/abs/1509.05514) [Daruki-Thaler-Venkatasubramanian]
- 2016 - [Nearly Optimal Verifiable Data Streaming](https://www.iacr.org/archive/pkc2016/96140168/96140168.pdf) [Krupp et al.]
- 2017 - [Efficient Verifiable Databases With Insertion/Deletion Operations From Delegating Polynomial Functions](https://ieeexplore.ieee.org/document/8055577) [Miao et al.]
- 2017 - [Dynamic Chameleon Authentication Tree for Verifiable Data Streaming in 5G Networks](https://ieeexplore.ieee.org/abstract/document/8113470) [Xu et al.]
- 2018 - [VENUS: Verifiable range query in data streaming](https://ieeexplore.ieee.org/document/8406898) [Tsai et al.]
- 2019 - [New efficient constructions of verifiable data streaming with accountability](https://link.springer.com/article/10.1007/s12243-018-0687-7) [Zhang et al.]
- 2019 - [Secure data stream outsourcing with publicly verifiable integrity in cloud storage](https://www.sciencedirect.com/science/article/abs/pii/S2214212619300547) [wu et al.]
- 2020 - [Efficient and Lightweight Data Streaming Authentication in Industrial Control and Automation Systems](https://ieeexplore.ieee.org/document/9136873) [Xu et al.]
- 2020 - [TimeCrypt - Encrypted Data Stream Processing at Scale with Cryptographic Access Control](https://www.usenix.org/conference/nsdi20/presentation/burkhalter) [Burkhalter et al.]
- 2021 - [Optimal Verifiable Data Streaming Protocol with Data Auditing](https://link.springer.com/chapter/10.1007/978-3-030-88428-4_15) [Wei et al.]
- 2022 - [Verifiable data streaming protocol supporting update history queries](https://onlinelibrary.wiley.com/doi/abs/10.1002/int.23045) [Miao et al.]
- 2022 - [Efficient Verifiable Unbounded-Size Database From Authenticated Matrix Commitment](https://ieeexplore.ieee.org/document/9965561) [xx et al.]
- 2022 - [New Unbounded Verifiable Data Streaming for Batch Query with Almost Optimal Overhead](https) [Yang et al.]
- 2022 - [Efficient Zero-Knowledge Proofs on Signed Data with Applications to Verifiable Computation on Data Streams](https://eprint.iacr.org/2022/1393) [Fiore et al.]
- 2023 - [Optimal Verifiable Data Streaming Under Concurrent Queries](https://ieeexplore.ieee.org/document/10232858) [Wei et al.]
- 2023 - [Communication-Efficient Verifiable Data Streaming Protocol in the Multi-User Setting](https://ieeexplore.ieee.org/document/10149518) [Jing et al.]


### Authenticated Data Structures

- 2003 - [Authenticated Data Structures](https://link.springer.com/chapter/10.1007/978-3-540-39658-1_2) [Tamassia]
- 2004 - [A General Model for Authenticated Data Structures](https://link.springer.com/article/10.1007/s00453-003-1076-8) [Martel et al.]
- 2013 - [Streaming Authenticated Data Structures](https://www.iacr.org/archive/eurocrypt2013/78810351/78810351.pdf) [Papamanthou et al. ]
- 2014 - [Authenticated Data Structures, Generically](https://dl.acm.org/doi/abs/10.1145/2578855.2535851) [Miller et al.]
- 2014 - [Streaming Authenticated Data Structures: Abstraction and Implementation](https://www.cs.yale.edu/homes/cpap/published/STREAMING14.pdf) [Qian et al.]
- 2017 - [Dynamic authenticated data structures with access control for outsourcing data stream](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/iet-ifs.2015.0243) [Sun et al.]
- 2018 - [Dynamic Fully Homomorphic encryption-based Merkle Tree for lightweight streaming authenticated data structures](https://www.sciencedirect.com/science/article/abs/pii/S1084804518300286) [Xu et al.]
- 2020 - [An Adaptive Authenticated Data Structure With Privacy-Preserving for Big Data Stream in Cloud](https://ieeexplore.ieee.org/document/9063421) [Sun et al.]


### Proof-Carrying Data

- 2010 - [Proof-Carrying Data and Hearsay Arguments from Signature Cards](https://ic-people.epfl.ch/~achiesa/docs/CT10.pdf) [Chiesa et al.]
- 2015 - [Cluster Computing in Zero Knowledge](https://link.springer.com/chapter/10.1007/978-3-662-46803-6_13) [Chiesa et al.] - "Distributed SNARK for MapReduce"
- 2020 - [Proof-Carrying Data from Accumulation Schemes](https://eprint.iacr.org/2020/499) [Bünz et al.]
- 2021 - [Proof-Carrying Data without Succinct Arguments](https://eprint.iacr.org/2020/1618) [Bünz et al.]
- [Arkworks implementation of PCD](https://github.com/arkworks-rs/pcd)


### Streaming Interactive Proofs

- 2011 - [Verifying Computations with Streaming Interactive Proofs](https://arxiv.org/abs/1109.6882) [Cormode et al.]
- 2012 - [Practical Verified Computation with Streaming Interactive Proofs](https://arxiv.org/abs/1105.2003) [Cormode et al.]
- 2023 - [Streaming Zero-Knowledge Proofs](https://arxiv.org/abs/2301.02161) [Cormode et al.]


### Surveys

- 2015 - [Stream Verification](https://arxiv.org/pdf/1507.04188.pdf) [Justin Thaler]
- 2018 - [Primitives towards verifiable computation: a survey](https://link.springer.com/article/10.1007/s11704-016-6148-4) [Ahmad et al.]


### Applications

- 2024 - [zk-IoT - Securing the Internet of Things with Zero-Knowledge Proofs on Blockchain Platforms](https://arxiv.org/abs/2402.08322) [Ramezan et al.]


### Blogs

### Videos


## Implementations

