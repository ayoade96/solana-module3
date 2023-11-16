# Module3-Candymachine

A concise overview of the purpose and usage.

## Description

This initiative brings together Solana tokens and the development of a Candy Machine UI for a specialized Candy Machine NFT Contract. The distinctive feature here is the encouragement for users to make payments using a custom SPL token during the minting process.

## Getting Started

- Ensure the existence of a deployed Candy Machine NFT Contract with minted NFTs.
- Create a new SPL token for payment or utilize an existing one.

### Installations

- Nodejs installed (version 16.15 or higher)
- Solana CLI installed
- Phantom Wallet or Solflare extension installed
- Metaplex Sugar installed (Legacy Version, V1.x)

### Executing the Program

1. **Create an SPL token**:

    - Implement an SPL token following lessons or leverage a previously created token.

2. **UI Development for Candy Machine**:

    - Set up a UI for the Candy Machine following the provided tutorial.
    - Update the start script in package.json to mitigate ERR_OSSL_EVP_UNSUPPORTED errors.

3. **Token Payment Integration**:

    - Ensure the UI supports payment using the SPL token created in Step 1.
    - Test minting by transferring or minting the SPL token to a Phantom account and attempting to mint on the website.

## Authors

Ayoade Abdulrahman 
[@ayoade96](https://twitter.com/psalmuel1st)

## License

This project operates under the MIT License. Refer to the LICENSE.md file for comprehensive details.
