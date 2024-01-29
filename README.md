<div align="center">
    <img src="readme-assets/logo-readme.png" alt="Logo" height="80">
  </div>

# OpenVote: Blockchain-based Voting System

*OpenVote: Empowering Democracy, One Block at a Time with a blockchain-based voting system, ensuring secure, transparent and tamper-proof elections.*

## The Problem
Traditional voting systems suffer from security vulnerabilities, lacking mechanisms for voter verification and real-time tallying. Electoral fraud concerns and the absence of a transparent system for verifying voter identity compromise the democratic process, eroding public trust.

## OpenVote's Features
- Secure and Tamper-Proof Voting: OpenVote records only one vote and each in a decentralized, tamper-proof manner, guaranteeing supreme security and integrity.

- Prevention of Electoral Fraud: The transparency and immutability of the blockchain
make it virtually impossible to commit electoral fraud.

- Voter Anonymity and Verification: OpenVote assigns unique cryptographic identifiers to verify each vote securely without disclosing individual identities along with AES Encryption.

- Real-Time Vote Tallying: Real-time vote tallying, eliminating manual counting and reducing result announcement time.

- Zero-Trust Security: Unique Zero-Trust Security based authentication method using Aadhar, Voter ID and 2 OTPs at different stages to cast vote securely maintaining integrity.

- Vote from Anywhere: Voters can cast their vote from anywhere in the globe with just a smartphone and an internet connection.

- NFT Rewards for Voters: Transforming voter participation into a unique experience. This NFT Reward also serves as a receipt for their vote.

- Data Analytics:  Data analytics to derive meaningful insights from voting patterns and preferences.

## Getting Started

### Prerequisites

* Node
* Python Flask
* Postgres
* Metamask
* Metamask configuration for CosVM - https://doc.cosvm.net/welcome-to-cosvm/user-guide/metamask-configuration
* HardHat - For Local Testing

### Installation



1. Clone the repo
   ```
   git clone https://github.com/harikrish-s/OpenVote-
   ```
   
2. cd into repo
   ```
   cd OpenVote-pragyan
   ```
   
#### Now we have three modules, lets start each step by step:

3. Front End Dashboard
   ```
   cd client
   npm i
   npm run dev
   ```
   

4. Backend
   ```
   pip install requirements.txt
   python app.py
   ```
   

5.   

<!-- USAGE EXAMPLES -->
## Usage

- At First, Create Election, Register the Candidates and Add voters from Admin.
- Run Python API
- Login as Voter, by uploading fingerprint images(download link given above), and cast the votes!

## Creating a New Election

#### 1. Copy the Code from the output

![](/screenshots/c1.png)

#### 2. Paste it as deploy.js, after that deploy using hardhat

   sh
   cd Contracts
   npx hardhat compile
   npx hardhat run --network cosvm scripts/deploy.ts
   

#### 3. You have Deployed your Election!

## Workflow

![](/screenshots/fc.png)


## Screenshots

![](/screenshots/a1.png)

![](/screenshots/a2.png)

![](/screenshots/a3.png)

![](/screenshots/a4.png)


## Built With

- ReactJS
- TailwindCSS
- Ethers.JS
- Solidity
- CosVM
- Flask
- PostgreSQL

## Video Demo
<a href="https://drive.google.com/file/d/1RPO9ZHSPX-sjxImTTyCg-KXOBzhnSeWx/view?usp=sharing">Click here</a>


## Support Us

Contributions, issues, and feature requests are welcome!

Give a ⭐️ if you like this project!
