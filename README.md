## Merkle Claim Implementation

Merkle Claim smart contract is a solidity smart contract implementation of a Merkle drop mechanism, allowing users to claim ERC1155 tokens by providing a valid Merkle proof that is generated off-chain.


## Features 
- Efficient distribution of ERC1155 tokens using a Merkle tree. 
- Prevents duplicate claims by tracking claimed addresses. 
- Easy integration with off-chain Merkle tree generation tools. 
- Supports dynamic token URI retrieval for improved flexibility. 

## Getting Started

To use this smart contract in your project, follow these steps:

- **Deploy the Contract:** Deploy the Merkle.sol contract to your Ethereum network of choice. Make sure to provide the Merkle root hash during deployment.

- **Whitelist Users:** Generate a Merkle tree off-chain including the addresses eligible for claiming tokens and their respective amounts. Compute the Merkle root hash and provide it during contract deployment.

- **Claim Tokens:** Users can claim their tokens by providing a valid Merkle proof, proving their eligibility for the tokens.

## Author

👤 **Ijay Abby**

- Github: [@IjayAbby](https://github.com/IjayAbby)
- Twitter: [@Ijay_js](https://twitter.com/Ijay_js)
- LinkedIn: [Abigael Nyangasi](https://www.linkedin.com/in/ijayabby4/)

## Show your support

Give a :star2: if you like this project! :blush:

## Acknowledgments

- Thanks are owed to [Temitayo Daniel](https://github.com/Timidan/merkle-distributor), for the template.

