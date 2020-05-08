# Awesome Hyperledger Fabric [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of resources for creating applications with Hyperledger Fabric

[<img src="https://www.hyperledger.org/wp-content/uploads/2018/03/Hyperledger_Fabric_Logo_Color.png" align="right" width="250">](https://www.hyperledger.org/projects/fabric)

## Contents

- [Apps](#apps)
- [Boilerplates](#boilerplates)
- [Tools](#tools)
- [Documentation](#documentation)
- [Articles](#articles)
- [Community](#community)


## Apps

### Open source

[Supply chain](https://github.com/ialberquilla/hlf1.4-supply-chain) - Supply chain PoC App with four organizations exposing a Rest API created in Hyperledger Fabric.

### Closed

- [Monetago](https://monetago.com) - Reduce instances of fraud around receivables financing.
- [Tellus](https://worldsibu.tech/tellus/) - Smart contracts transaction designer without coding.

### Samples

- [Fabric samples](https://github.com/hyperledger/fabric-samples) - Official maintained samples created by the Hyperledger team and contributors.
- [Marbles](https://github.com/IBM-Blockchain/marbles) - Marbles sample created by IBM visually demonstrating all the possibilities.
- [Hyperledger composer samples](https://github.com/hyperledger/composer-sample-applications) - Official samples for Hyperledger composer.
- [Kuma token](https://github.com/Kunstmaan/hyperleder-fabric-kuma-token-example/) - Example token implementation.
- [Land Ownership Tracking](https://github.com/ronaldlong46/hyperledger-land-tracking) - Sample Hyperledger Composer application that allows government agencies to track ownership and transactions.

## Boilerplates

### Client

- [Backend typescript boilerplate](https://github.com/wearetheledger/hyperledger-typescript-boilerplate) - Client boilerplate for interacting with the Fabric network using a REST API (Typescript, Nestjs, swagger, pusher).

### Network

- [Fabric starter](https://github.com/olegabu/fabric-starter) - Starter Application and Deployment Scripts.
- [Hyperledger Fabric network boilerplate](https://github.com/wearetheledger/fabric-network-boilerplate) - Network boilerplate for easily setting up a new network.


## Tools

### Client

- [hyperledger-fabric-client-utils](https://github.com/Kunstmaan/hyperledger-fabric-client-utils) - Set of utility functions which can be used to interact with chaincode.
- [fabric-node-chaincode-utils](https://github.com/wearetheledger/fabric-node-chaincode-utils) - A Nodejs module that helps you build your Hyperledger Fabric nodejs chaincode faster and easier.
- [hlf-sdk-go](https://github.com/s7techlab/hlf-sdk-go) - A third-party Golang Hyperledger Fabric SDK.

### Network

- [hyperledger-fabric-network-setup](https://github.com/Kunstmaan/hyperledger-fabric-network-setup) - Helper functions for generating configurations for more advanced network setup.
- [Chainstack managed blockchain](https://chainstack.com/) - Deploy a running network in minutes on Google Cloud or Amazon Web Services.
- [IBM Cloud blockchain platform](https://console.bluemix.net/catalog/services/blockchain) - Managing and hosting a live network on IBM Cloud.
- [Hurley](https://worldsibu.tech/convector/hurley-development-environment/) - Quickly setup your network development environment.
- [WorldSibu - Forma](https://worldsibu.tech/forma/) - Real Multi-cloud Remote Blockchain Infrastructure Orchestrator.
- [Zeeve](https://www.zeeve.io/) - Deploy and Manage Blockchain Network on multiple cloud providers like GCP, AWS, Azure, Digital Ocean or On-premise

### Chaincode

- [hyperledger-fabric-chaincode-dev-setup](https://github.com/Kunstmaan/hyperledger-fabric-chaincode-dev-setup) - Setup which makes it easy to develop Nodejs chaincode.
- [hyperledger-fabric-node-chaincode-utils](https://github.com/Kunstmaan/hyperledger-fabric-node-chaincode-utils) - Utility functions for Nodejs chaincode on Hyperledger Fabric blockchain.
- [fabric-shim-types](https://github.com/wearetheledger/fabric-shim-types) - Typescript types for the `fabric-shim` chaincode package.
- [fabric-mock-stub](https://github.com/wearetheledger/fabric-mock-stub) - Mock implementation of the `fabric-shim` stub for testing Nodejs chaincode.
- [fabric-shim-crypto-types](https://github.com/wearetheledger/fabric-shim-crypto-types) - Typescript types for the `fabric-shim-crypto` package.
- [CCKit](https://github.com/s7techlab/cckit) - Library for creating and testing golang chaincode, includes extended Mockstub implementation.

### Other

- [hyperledger composer playground](https://composer-playground.mybluemix.net) - Online playground for developing applications using composer.
- [tineola](https://github.com/tineola/tineola) - Command line interface and packaged chaincode built for offensive security testing.


## Documentation

### Docs

- [Official docs](http://hyperledger-fabric.readthedocs.io) - Officially maintained docs for the Hyperledger Fabric project.
- [Official CA docs](http://hyperledger-fabric.readthedocs.io) - Officially maintained docs for the Hyperledger Fabric project CA client and server.
- [Couchdb query docs](docs.couchdb.org/en/2.1.0/api/database/find.html?highlight=find#post--db-_find) - Official CouchDB documentation required for writing rich queries.
- [Node SDK docs](https://fabric-sdk-node.github.io)

### Courses

- [Blockchain for Business - An Introduction to Hyperledger Technologies](https://www.edx.org/course/blockchain-business-introduction-linuxfoundationx-lfs171x) - FREE.
- [Hyperledger - Blockchain Technologies for Business by Иван Ванков](https://www.youtube.com/watch?v=7EpPrSJtqZU&list=PLjsqymUqgpSRXC9ywNIVUUoGXelQa4olO) - Youtube series explaining Hyperledger Fabric.
- [Hyperledger Fabric - build first network by Иван Ванков](https://www.youtube.com/watch?v=MPNkUqOKhVE&list=PLjsqymUqgpSTGC4L6ULHCB_Mqmy43OcIh) - Technical youtube series Hyperledger Fabric.

### Tutorials

- [Hyperledger Fabric SDK Go: How to build your first app?](https://github.com/chainHero/heroes-service) - Chainhero tutorial on how to build applications on Hyperledger Fabric v1.0.5.
- [Hyperledger Development within 21 days](https://medium.com/@grsind19/hyperledger-development-with-in-21-days-day-1-ed3c5df88113)
- [Hyperledger Fabric dev env setup Kubernetes](https://medium.com/kokster/set-up-a-hyperledger-fabric-development-environment-on-kubernetes-6428c63e018b)
- [Fabric on Google Cloud Platform](https://medium.com/google-cloud/fabric-on-google-cloud-platform-97525323457c)
- [Write your first Chaincode (v1.4) using Node, Babel, Model/Controller and Test it using Mocha](https://medium.com/@jojoooo/write-your-first-hyperledger-fabric-1-4-chaincode-bab3c484c35a)
- [Start Developing Hyperledger Fabric Chaincode in Node.js](https://medium.com/coinmonks/start-developing-hyperledger-fabric-chaincode-in-node-js-e63b655d98db)
- [Walkthrough of Hyperledger Fabric Node SDK and Client Application](https://medium.com/datadriveninvestor/walkthrough-of-hyperledger-fabric-client-application-aae5222bdfd3)
- [Deploy a Hyperledger Fabric v2 Web App Using the Node.js SDK](https://chainstack.com/deploy-a-hyperledger-fabric-v2-web-app-using-sdk-for-node-js/)

#### Composer

- [Debug your Blockchain business network using Hyperledger Composer](medium.com/@mrsimonstone/debug-your-blockchain-business-network-using-hyperledger-composer-9bea20b49a74)

### Whitepaper
- [White paper Hyperledger projects](https://www.hyperledger.org/wp-content/uploads/2018/04/Hyperledger_Arch_WG_Paper_2_SmartContracts.pdf)


## Articles

### Architecture

- [Hyperledger Fabric and how it isn’t concurrent out of the box.](https://medium.com/wearetheledger/hyperledger-fabric-concurrency-really-eccd901e4040)
- [Trust your competitor? How you can do that with a Hyperledger Fabric blockchain.](https://medium.com/blockchainspace/trust-your-competitor-how-you-can-do-with-hyperledger-fabric-5939bacffe76) - Explaining consensus mechanisms in Hyperledger Fabric
- [Understanding Hyperledger Fabric Gossip](https://medium.com/kokster/understanding-hyperledger-fabric-gossip-512a217d5d1e)
- [Private and confidential transactions with Hyperledger Fabric](https://www.ibm.com/developerworks/cloud/library/cl-blockchain-private-confidential-transactions-hyperledger-fabric-zero-knowledge-proof/index.html)
- [Two Enter, One Leaves](https://developer.ibm.com/code/2018/05/11/two-enter-one-leaves/) - Early attempts to bring Ethereum to Hyperledger Fabric.
- [Demystifying Hyperledger Fabric (1/3): Fabric Architecture](https://medium.com/coinmonks/demystifying-hyperledger-fabric-1-3-fabric-architecture-a2fdb587f6cb)
- [Demystifying Hyperledger Fabric (2/3): Private Data Collection](https://medium.com/coinmonks/demystifying-hyperledger-fabric-2-3-private-data-collection-164220ecafa5)
- [Demystifying Hyperledger Fabric (3/3): Network Traffic Handling, Service Discovery, and Operations Service](https://medium.com/coinmonks/demystifying-hyperledger-fabric-3-3-network-traffic-handling-service-discovery-and-operations-f9a2046b4067)

### Private Data

- [Private data, a built-in “GDPR compliant” solution for Hyperledger Fabric](https://medium.com/wearetheledger/private-db-a-built-in-gdpr-compliant-solution-for-hyperledger-fabric-1a082da1b301) - Theoretical guide on private data and sideDBs.
- [A Beginner’s Guide to SideDBs and Private Data for Hyperledger Fabric Nodejs Chaincode](https://medium.com/wearetheledger/a-beginners-guide-to-sidedbs-and-private-data-for-hyperledger-fabric-nodejs-chaincode-38d2c1bee198) - Practical guide on how to write private data chaincode.

### CouchDB

- [Fantastic queries and where to find them](https://medium.com/wearetheledger/hyperledger-fabric-couchdb-fantastic-queries-and-where-to-find-them-f8a3aecef767) - Guide on how to write rich queries.

### Devops

- [Hyperledger Fabric on Multiple Hosts](https://medium.com/@wahabjawed/hyperledger-fabric-on-multiple-hosts-a33b08ef24f) - Multi-host Hyperledger Fabric deployment using docker swarm.

### Composer

- [Developing multi-user application using the Hyperledger Composer REST Server](https://medium.com/@CazChurchUk/developing-multi-user-application-using-the-hyperledger-composer-rest-server-b3b88e857ccc)

### Other

- [Tools that will help create your first Hyperledger Fabric application](https://medium.com/kunstmaan/tools-that-will-help-create-your-first-hyperledger-fabric-application-b8345317792)
- [How to deploy (early) production ready Hyperledger Fabric applications using IBM Cloud](https://medium.com/wearetheledger/how-to-deploy-early-production-ready-hyperledger-fabric-applications-using-ibm-cloud-caa7ecec22b5?source=collection_home---4------1----------------)
- [The new and exciting features in Hyperledger Fabric 1.1(-preview)](https://medium.com/wearetheledger/the-new-and-exciting-features-in-hyperledger-fabric-1-1-preview-4261ece3590d)
- [How to start writing your Hyperledger Fabric Nodejs chaincode](https://medium.com/wearetheledger/how-to-start-writing-your-hyperledger-fabric-nodejs-chaincode-4052393933ab)
- [How to start testing your Hyperledger Fabric Nodejs chaincode](https://medium.com/wearetheledger/how-to-start-testing-your-hyperledger-fabric-nodejs-chaincode-229453c3c214)
- [How to prevent key collisions in Hyperledger Fabric chaincode](https://medium.com/@gatakka/how-to-prevent-key-collisions-in-hyperledger-fabric-chaincode-303700716733)
- [Tools that will help create your first Hyperledger Fabric application](https://medium.com/kunstmaan/tools-that-will-help-create-your-first-hyperledger-fabric-application-b8345317792)
- [On the origins of Hyperledger Fabric](https://www.linkedin.com/pulse/origins-hyperledger-fabric-maciek-jędrzejczyk/)
- [Hyperledger Fabric smart contract data model: protobuf to chaincode state mapping](https://medium.com/coinmonks/hyperledger-fabric-smart-contract-data-model-protobuf-to-chaincode-state-mapping-191cdcfa0b78)
- [Hyperledger Fabric chaincode test driven development (TDD) with unit testing](https://medium.com/coinmonks/test-driven-hyperledger-fabric-golang-chaincode-development-dbec4cb78049)
- [Start Developing Hyperledger Fabric Chaincode in Node.js](https://medium.com/coinmonks/start-developing-hyperledger-fabric-chaincode-in-node-js-e63b655d98db)
- [Walkthrough of Hyperledger Fabric Node SDK and Client Application](https://medium.com/datadriveninvestor/walkthrough-of-hyperledger-fabric-client-application-aae5222bdfd3)
- [How to write unit tests for Hyperledger Fabric Go chaincode](https://blogs.sap.com/2019/01/11/how-to-write-unit-tests-for-hyperledger-fabric-go-chaincode/) - Applied for Fabric v1.x

## Community

- [Community chat](http://chat.hyperledger.org)
- [Hyperledger wiki for Fabric](https://wiki.hyperledger.org/projects/fabric)
- [Support mailing list](https://lists.hyperledger.org/g/fabric/join)


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first. If you found this resource helpful, give it a 🌟 otherwise [contribute](contributing.md) to it and give it a ⭐️.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, TheLedger has waived all copyright and
related or neighboring rights to this work.
