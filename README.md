<div align="center">
    <img src="openVote-logo.png" alt="OpenVote" height="80">
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
   
3. Solidity
   ```
   cd smartContract
   npx hardhat run --network cosvm scripts/deploy.ts
   ```
   *Copy the Smart Contract Address generated & paste it in the constants.js file of utils folder under client*
  

4. Backend
   ```
   cd flask
   pip install requirements.txt
   python app.py
   ```
      
5. Front End Dashboard
   ```
   cd client
   npm i
   npm run dev
   ```

<!-- USAGE EXAMPLES -->
## Usage

- At First, Register the Candidates, Then add the Voters & Finally Start the Election.
- Now to Login as Voter, Enter your official document details & then verify your Identity by entering the OTP generated to your registered mobile.
- If there is an ongoing election, you could cast your vote by passing a ZTA (Zero Trust Athentication) which is again generated as a key to your mobile.
- After successful verify you can now cast your vote to your desired candidate.
- Once the vote is casted, A NFT is generated as a Token of Acknowledgement.
- Now on the Admin side, you can view the Live Vote Count under each candidates & once the election is concluded a deteailed report & analytics will been generated.

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
- Openzeppelin
- CosVM
- MetaMask
- Flask
- PostgreSQL

## Video Demo
<a href="https://drive.google.com/file/d/1RPO9ZHSPX-sjxImTTyCg-KXOBzhnSeWx/view?usp=sharing">Click here</a>


## Support Us

Contributions, issues, and feature requests are welcome!

Give a ⭐️ if you like this project!
