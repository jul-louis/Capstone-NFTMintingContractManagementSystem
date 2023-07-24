# NFT Minting and Contract Management System: Capstone Project
for ECE 493 at the University of Alberta
Sponsored by Suissa Design

## Technologies

### Hyperledger Fabric

Hyperledger Fabric Permissioned blockchain was selected as the underlying framework for our capstone project, leveraging its robust and secure open-source architecture. Hyperledger is a community-driven project under the Linux Foundation that aims to develop blockchain technologies for business applications. 

Hyperledger Fabric, a flagship project within the Hyperledger community, is a permissioned blockchain platform for enterprise use cases. It offers several unique features, such as modular architecture, plug-and-play consensus mechanisms, and support for smart contract programming 
languages. These capabilities make it a highly versatile and customizable platform, well-suited for diverse use cases in various industries. 

The network setup for the capstone project utilizes the test network provided by Hyperledger Fabric, allowing for convenient and efficient development and testing of our blockchain applications. This test network enables us to prototype and validate our applications in a sandbox environment before deploying them to production networks. It provides a safe and controlled environment for experimentation, ensuring we can start chain-code development without worrying about any configuration error in the network [3]. 
Currently, most art commission and trading websites, e.g., SuperRare and KnownOrigin, are based on public blockchains such as Ethereum Blockchain. Transactions or smart contract executions in a public blockchain generally require a payment called a gas fee, where gas is the unit that measures the computation efforts. Gas fees can vary depending on the congestion of the network, as well as the complexity and size of the transaction or smart contract execution. 

We have chosen to refrain from using a public blockchain due to the potential for high gas fees, which the sponsor undesired. Instead, we have opted to leverage the benefits of the Hyperledger Fabric blockchain for our art commission and trading platform. Hyperledger Fabric provides a permissioned blockchain platform that allows us to avoid gas fees while maintaining a secure and efficient network for transaction processing. With Hyperledger Fabric, we can control access to the network, tailor the consensus algorithm to our specific use case, and develop custom contracts using various programming languages. Additionally, we can leverage Hyperledger Fabric's modular architecture to customize the platform to our specific needs, allowing us to provide a seamless and user-friendly experience for the creative society. 

### Chaincode

### Database Design

A database is required to store authentication data and essential information not stored in the blockchain, and MongoDB was integrated into our project for exactly this purpose. 

MongoDB is an open-source document-oriented NoSQL database management system that uses a document-based model to store data. It is designed to handle extensive volumes of unstructured and semi-structured data, making it a favoured choice for big data and real-time web applications. 

### React/TypeScript



## Poster
Designed by Louis, Owen, and Paola.

## Code Base
The project is private as it's owned by the Sponsor.
