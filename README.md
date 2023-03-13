Gianluca Di Vita - 101415332 Nader Fathzadeh - 101441256 Umut Yorulmaz - 101410083 Sarim Sohail - 101416162

# **BCDV1026 - Blockchain Platforms**

# **Cosmos Social Media Dapp**

# **Solution Design Document & Project Overview**

# **TEAM**

Gianluca Di Vita - 101415332 MAIN: Business Analyst ASSIST: Full Stack Developer

Umut Yorulmaz - 101410083 MAIN: Architect ASSIST: Business Analyst

Nader Fathzadeh - 101441256 MAIN: Blockchain Developer ASSIST: Architect

Sarim Sohail - 101416162 MAIN: Full Stack Developer ASSIST: Blockchain Developer

# **REQUIREMENTS**

Operating system: Cosmos is compatible with various operating systems, including Linux, Windows, and macOS.

Docker: Docker containers can be used to run the network nodes.

Programming Language: GO programming language, Rust and NodeJS.

# **SECTION I: BUSINESS**

**Project Abstract**

A social media decentralized application that allows content creators to tokenize their content as an NFT and make cross chain operations easy for them. For instance, cross-chain reward mechanism and moving in between chains and different social media dapps with their tokenized contents (NFTs) without losing them.

**An Interchain Operable Social Media Dapp**

Building next generation decentralized interactive social media dapps is an important concept of web3. Utilizing the capability of the interchain operations of Cosmos, our Youtube like social media dapp will bring a great solution to the market. There will be two important feature:

1.  Content creators will be able to tokenize their contents as NFT form which allows them to freely move in between dapps on different blockchains. Cosmos makes this possible by its IBC protocol.
2.  Content creators will be rewarded based on their content views and rewards can be smoothly transferred from all different blockchains. Which enables and makes payments and interactions possible between consumers and content creators, no matter on which blockchain they are.
3.  Project’s native token (SMT) will be used to cover transaction fees, reward mechanism, conversion fees and calculations.

This report will explain each component of the project in detail and provide a comprehensive understanding of how the project functions.

# **Project Components**

Network Architecture - Overview The network component of the social media dapp consists of docker, go, vueJS. In order to run blockchain the blockchain ignite container is used. In order to scaffold the blockchain \</\>**ignite scaffold chain**[ ](http://github.com/alice/checkers)[**github.com/alice/checkers**](http://github.com/alice/checkers) \</\> command is used and a sample blockchain is built based on the related Github repo. For front end vueJS is used.

# **Project Workflow**

**Content Creation**: Anytime users publish or create a content its hash is saved on blockchain and the file itself saved on the cloud.

**Interactions:** Anytime an interaction occurs such as, like, dislike, subscribe, unsubscribe, follow, message, comment etc. it is saved on blockchain and based on the interaction reward mechanism is activated, to reward content creators and active followers and users.

**Wallets:** they will be the representation of the users in the blockchain ecosystem. Users can interact with the blockchain by connecting their wallets to the dapp by using the front end application.

# **Business Model**

Small fees are applied to cover the maintenance cost of the blockchain. Apart from that, there won't be any data processing, advertising activity will take place for business purposes. All fees and transactions can be followed on the blockchain explorer of the dapp. Team earnings will be provided by the 10% locked tokens. Project is expected to be successful and correlatively the value of the native token of the dapp is expected to rise to reward the founder team.

# 

# **Project Diagrams**

# **Use Case Diagram**

This workflow shows the system being used in an ideal application setting with full capabilities. Consumers are represented as different blockchain users to show the power of using cosmos; interchain operability. Consumers can be in the Cosmos ecosystem as well. ![](media/d89f92f3d30b82c75cfcf80eea5bd7d1.png)

# **Roles and Policies**

**Roles**

In the social media dapp built on Cosmos, there are three main roles: content creator, user, and developer. Each role has specific permissions and access to perform certain actions on the blockchain network. For example, the creator has permission to create and broadcast a content, while the developer has permission to maintain the network and broadcast updates. The consumer has the same permission as the creator. So consumer = creator. They are called creator or consumer based on their current activity if they are broadcasting something they are a creator if they are watching or reading something they are a consumer . These roles are defined in the smart contract, and the code enforces the policies to ensure that the participants can only perform actions they are authorized to perform.

**Policies**

The policies for the social media dapp are also defined in the smart contract. The policies govern who can perform actions on the blockchain network, and what actions they can perform. For example, a policy may state that only the developer can reach certain layers of the dapp, or that the consumer must reward a content based on their interaction. These policies ensure that the supply chain process is followed correctly and that the integrity and the security of the network is maintained smoothly without confusion and flaws.
