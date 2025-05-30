Decentralized Healthcare Records Using Blockchain

A secure, patient-centric eVault system built on Ethereum and IPFS to manage Electronic Health Records (EHRs).
The integration of blockchain technology in healthcare has the potential to revolutionise the management of patient data by enhancing security, transparency, and accessibility. Traditional healthcare systems face challenges such as data breaches, lack of interoperability, and inefficiencies in record-keeping. Blockchain, with its decentralized and immutable ledger, offers a solution by enabling secure, tamper-proof, and transparent data transactions. This research explores the application of blockchain in healthcare, focusing on patient data security, interoperability among healthcare providers, and decentralized health record management. By leveraging smart contracts and cryptographic techniques, blockchain ensures that only allowed personnel can access and change sensitive medical information, reducing fraud and unauthorized alterations. The study also discusses the challenges of implementing blockchain, including scalability, regulatory compliance, and integration with existing healthcare infrastructures. Through an analysis of existing blockchain-based healthcare models, this research highlights how blockchain can enhance patient trust, improve data integrity, and create a more efficient and secure healthcare ecosystem.

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
