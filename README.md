# Hyperledger-Fabric & Composer

  Go through the following tutorials to configure the Fabric&Composer environment and to build a demo Fabric network:

  * https://hyperledger.github.io/composer/latest/installing/installing-prereqs.html
  * https://hyperledger.github.io/composer/latest/installing/development-tools.html

  **Note**: If you get a `connection timeout error` while executing `startFabric.sh`, please set the environment variable `FABRIC_START_TIMEOUT=30`, or to a larger value, if it still fails


# Ethereum

  We are going to build a docker-based private local Ethereum network with the following nodes:

  * 1 bootnode for bootstrapping the ethereum private network
  * 2 miner nodes for mining transaction blocks
  * 1 dev node that exposes RPC services for interacting with the blockchain
  * 2 swarm nodes for storing and distribute blockchain code and data
  * 1 truffle node for developing & deploying smart contracts
  * 1 explorer node for analyzing the state of the blockchain network


  In order to configure the network, execute the following commands:

  ```
  cd ./ethereum-private-network
  docker-compose up -d
  ```


# IPFS

  Go through the following tutorial to run an IPFS node in a docker container:

  * https://blog.ipfs.io/1-run-ipfs-on-docker/


# BigchainDB

  Go through the following tutorial to run an BCDB node in a docker container:

  * http://docs.bigchaindb.com/projects/server/en/v2.0.0b9/appendices/all-in-one-bigchaindb.html
