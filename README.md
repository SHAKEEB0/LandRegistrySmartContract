<<<<<<< HEAD
# LandRegistrySmartContract
=======
# LandRegistrySmartContract
# Land Registry DApp
## Project Overview

The *Land Registry DApp* is a decentralized application (DApp) built on *Ethereum* using *Solidity* smart contracts. This DApp allows users to register land, transfer land ownership, and view land details securely on the blockchain.

The primary goal of this project is to demonstrate the use of smart contracts in managing land records, ensuring transparency, security, and immutability in land transactions.

---

## Features

- *Register Land:*  
  Users can register land by providing the land ID, location, and area (in square meters). Each land registration is stored on the Ethereum blockchain.

- *Transfer Ownership:*  
  Owners can transfer ownership of land parcels to new owners by specifying the land ID and the new owner's Ethereum address.

- *View Land Details:*  
  Anyone can query land details such as the location, area, current owner, and registration status by providing the land ID.

---

## Tech Stack

- *Solidity:* Smart contract development language for Ethereum blockchain.
- *Web3.js:* JavaScript library to interact with the Ethereum blockchain from the web.
- *Ganache:* A personal Ethereum blockchain used for testing and development.
- *MetaMask:* A browser extension for managing Ethereum accounts and interacting with Ethereum DApps.

---

## Installation & Setup

### *1. Install Dependencies*
To get started, you'll need to install *Ganache* and *MetaMask*:

- [Download Ganache](https://www.trufflesuite.com/ganache)
- Install the *MetaMask extension* in your browser from [here](https://metamask.io/).

### *2. Clone the Repository*
Clone the repository to your local machine:

bash
git clone https://github.com/yourusername/land-registry-dapp.git


### *3. Run Ganache*
Launch *Ganache* and create a new workspace for your project. This will start a local Ethereum blockchain at http://127.0.0.1:7545.

### *4. Connect MetaMask to Ganache*
Open *MetaMask* and switch the network to *Localhost 8545* (Ganache's network).

### *5. Deploy the Smart Contract*
1. Compile and deploy the smart contract using *Truffle* or *Remix*.
2. Copy the contract address after deployment and paste it into your DApp's JavaScript code (contractAddress).

### *6. Start the DApp*
- Open the *HTML file* in your browser using a local server (e.g., VS Code Live Server).
- Interact with the DApp to register land, transfer ownership, and view land details.

---

## Usage

1. *Register Land:*  
   - Enter the *Land ID, **Location, and **Area* to register a new land parcel.
   - Click on *Register* to submit the transaction.

2. *Transfer Ownership:*  
   - Enter the *Land ID* and the *New Owner's Ethereum address* to transfer ownership.
   - Click on *Transfer* to submit the transaction.

3. *View Land Details:*  
   - Enter the *Land ID* and click *Get Details* to retrieve and display the land information.

---

## Contributing

Feel free to fork this repository, contribute to the code, and suggest improvements. Pull requests are always welcome!

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
>>>>>>> cd90178 (Initial commit)
