# MediaChain  
Decentralized media distribution system using Storage cess smart contracts.  

Imagine a platform where creators can sell their digital content (photos, videos, music) directly to fans—no middlemen, no extra fees, and with guaranteed authenticity.

✨ How It Works:
Creators Upload

Artists register their work on the blockchain with a unique fingerprint (hash)

They set their own price in cryptocurrency (ETH)

Fans Purchase

Buyers pay directly to the creator's digital wallet

Every sale is permanently recorded on the blockchain

Everyone Wins

✅ Creators keep 100% of earnings (no platform commissions)
✅ Buyers get verified authentic content (no fakes)
✅ All transactions are transparent (viewable by anyone)

🔍 Why This Matters:
No More Fakes: Each file has a unique blockchain ID

Instant Payments: Creators receive funds immediately

Global Access: Works for anyone with an internet connection

## 🛠️ Technologies Used  
- **Backend**: Solidity (Ethereum), Python (optional scripts).  
- **Frontend**: HTML, CSS, JavaScript, Web3.js.  
- **Database**: MySQL (for metadata, if applicable).  
- **Local Server**: XAMPP (Apache/MySQL).

## 🚀 How to Set Up  

### **1. Prerequisites**  
- Install:  
  - [XAMPP](https://www.apachefriends.org/download.html) (for MySQL and local server).  
  - [Python 3.10+](https://www.python.org/downloads/) (if using Python scripts).  
  - [MetaMask](https://metamask.io/download.html) (browser extension).

git clone https://github.com/Malaquiaslindo/scMediaChainn.git
cd MediaChain
Start XAMPP and run Apache + MySQL.

Open phpMyAdmin (http://localhost/phpmyadmin).

Create the database and tables:

sql
CREATE DATABASE proof_of_existence;
USE proof_of_existence;

-- Tables (paste the SQL from 'database_setup.sql' or run manually)
CREATE TABLE files (...);
CREATE TABLE transactions (...);

python app.py
