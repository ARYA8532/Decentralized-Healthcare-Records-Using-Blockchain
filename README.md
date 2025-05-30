Decentralized Healthcare Records Using Blockchain

A secure, patient-centric eVault system built on Ethereum and IPFS to manage Electronic Health Records (EHRs).

🔐 Features
- Full patient ownership of medical records
- Real-time access control with smart contracts
- IPFS-based tamper-proof document storage
- Interoperability between doctors, hospitals, and insurers
- AI-ready structure for future disease prediction and fraud detection

🛠 Tech Stack
- Ethereum (Solidity Smart Contracts)
- IPFS & Web3.Storage
- React.js Frontend
- Web3.js integration

🚀 Getting Started
Follow the steps below to run the Decentralized Healthcare Records Using Blockchain (DocPad) project on your local machine.

🧩 1. Prerequisites
Make sure the following tools are installed:

- Node.js (v16 or above)
- npm
- MetaMask extension in your browser
- Ganache (local Ethereum blockchain) OR a testnet setup
- IPFS Daemon (optional if not using Web3.Storage)
- Git

📦 2. Clone the Repository

--> git clone https://github.com/ARYA8532/Decentralized-Healthcare-Records-Using-Blockchain.git
    cd Decentralized-Healthcare-Records-Using-Blockchain
📁 3. Install Dependencies ---  npm install
🔧 4. Configure IPFS / Web3.Storage

ipfs daemon
Make sure it runs at http://localhost:5001.

⚙️ 5. Smart Contract Deployment (using Truffle)

npm install -g truffle
truffle compile
truffle migrate --network development
Ensure Ganache is running before migration.

💻 6. Run the React Frontend
npm start
Open your browser and go to:
http://localhost:3000

Connect MetaMask to the same network as Ganache or your testnet.



🛠 Optional: Recompile Contracts

truffle compile
truffle migrate --reset --network development
