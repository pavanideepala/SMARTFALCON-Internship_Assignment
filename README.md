# Hyperledger Fabric Asset Management System

This project implements a blockchain-based system for managing and tracking assets using Hyperledger Fabric. The project is divided into three levels:

1. **Level-1**: Setting up a Hyperledger Fabric test network.
2. **Level-2**: Developing and testing a smart contract.
3. **Level-3**: Creating a REST API to interact with the deployed smart contract.

## Project Structure

- `fabric-test-network/`: Hyperledger Fabric test network setup.
- `smart-contract/`: Go-based smart contract for asset management.
- `rest-api/`: REST API for smart contract interaction, with Docker support.
  
## Setup Instructions

1. **Prerequisites**:
   - Docker
   - Golang
   - Hyperledger Fabric binaries
   - Node.js (for network setup)

2. **Level-1**: Setup Hyperledger Fabric Test Network
   - Follow the steps in the [Hyperledger Fabric Test Network Documentation](https://hyperledger-fabric.readthedocs.io/en/latest/test_network.html).

3. **Level-2**: Smart Contract Development
   - Develop and test the smart contract following the example in the [Hyperledger Fabric Chaincode Guide](https://hyperledger-fabric.readthedocs.io/en/latest/smartcontract/smartcontract.html).
   
4. **Level-3**: REST API Development
   - Implement a REST API in Go to interact with the deployed smart contract and create a Docker image for the API.

## References

- [Hyperledger Fabric Documentation](https://hyperledger-fabric.readthedocs.io/en/latest/)
- [Hyperledger Fabric Samples](https://github.com/hyperledger/fabric-samples)

## License

This project is licensed under the MIT License - see the LICENSE file for details.
