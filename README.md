# Image-Chain-Blockchain-
This Project is application of Blockchain on ImageChain


Research Paper : https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7796195/

Abstract : 

Abstract
Imagechain is a cryptographic structure that chain digital images with hash links. The most important feature, which differentiates it from blockchain, is that the pictures are not stored inside the blocks. Instead, the block and the image are combined together in the embedding process. Therefore, the imagechain is built from standard graphic files that may be used in the same way as any other image, but additionally, each of them contains a data block that links it to a previous element of the chain. The presented solution does not require any additional files except the images themselves. It supports multiple file formats and embedding methods, which makes it portable and user-friendly. At the same time, the scheme provides a high level of security and resistance to forgery. This is achieved by hashing the whole file with embedded data, so the image cannot be altered or removed from the chain without losing integrity. This article describes the basic concept of an imagechain together with building blocks and applications. The two most important issues are embedding methods and block structure.

Keywords: imagechain, image watermarking, image cloud technologies

### Example 1: 

ImageChain uses Blockchain technology to solve the exponentially growing problem of storing medical imaging data in a secure, accessible and useful way. Our platform empowers patients by giving them full control of their imaging data in one central place.

Patients can then grant permission for a set period of time to healthcare agents like clinicians and hospitals to view their imaging when required. By utilizing Blockchain, patients will be able to see who has accessed their data in a completely transparent manner on an immutable record.

For the first time ever, patients using our platform will be able to opt into selling their imaging data anonymously to interested parties like research institutions and pharmaceutical companies. With our underlying Blockchain technology patients can be completely confident that only the organisations they have granted permission to can access their data and no erroneous use has occurred.

### Example 2: 

Proof of image authentication on a blockchain
Abstract
Disclosed is improved technology for authenticating electronic images and storing proof of tampering or non-tampering on the blockchain. An image authentication application of a user device may generate an image. The user device may generate an image hash of the image using a hash function. The image hash may be written to the blockchain. This may occur immediately after the image has been taken. The user device may upload the image to an authentication server, which authenticates the image. At various times, such as after receipt, during authentication, and/or after authentication, the authentication server may generate an image hash of the image using the hash function. The authentication server may write the image hash(es) to the blockchain. As such, a state of the image at various times may be recorded on the blockchain to determine whether or not the image has been tampered with between various times.

### Example 3: 

Preferred Alternative
Store the image in a distributed file store (for example, Swarm or IPFS), and store a hash of the image on-chain, if it's really important for the image to provably untampered. If that's not important, then maybe don't put anything on chain.

What technical limit is there?
Primarily, the block's gas limit. Currently, Ethereum mainnet has an 8Mgas block limit. Every new 32bytes of storage uses 20k gas. So you can't store data that sums to more than 12.8kb, because it doesn't fit in the block.

### Example 4:

Medical Images Sharing System Based on Blockchain and Smart Contract of Credit Scores

At present, medical images account for nearly 70% of medical diagnostic data, which is an important basis for disease diagnosis. However, medical data leakage incidents have occurred in more than 90% medical institutions, the protection of patients' medical data is of great urgency. At present, all types of medical institutions involved in the medical imaging business use the PACS to archive, manage, and use the collected medical images, but only sharing the managed video resources within the organization. This method applies only the traditional data protection strategy and cannot guarantee a stronger protection for patients' private information. And patients have no control over medical information at the time of treatment. For this reason, this paper proposes a method of secure sharing of medical images based on smart contracts of block chain and credit scores. Through a blockchain based on distributed, reliable database of recording image sharing process, we realize a cross-organizational, cross-regional, trustworthy, and supervisory medical image sharing system. And the establishment of smart contracts based on credit scores of patients and medical institutions guarantee intelligent sharing by rules and conditions. Compared with traditional PACS, the method proposed in this paper extends its scope of application on the basis of PACS, increases its robustness, and provides new ideas for more extensive, multi-level, safe and reliable medical images sharing.

### Example 5: 

Decentralized autonomous imaging data processing using blockchain

Imaging studies are one of the leading drivers of modern medical decision making, and thus, their accessibility to healthcare providers and patients is of critical importance. However, current techniques for storage and transferring medical imaging data are inconvenient and sometimes wholly inadequate. In this paper, we propose a decentralized autonomous medical image processing approach using blockchain technology. Blockchain will enable the sharing of key relevant data using a distributed, decentralized, shared ledger that is available to participants. We outline a framework that utilizes blockchain to enable users to access imaging data in a secure and autonomous manner. A user case is experimentally investigated to validate our proposed approach.
