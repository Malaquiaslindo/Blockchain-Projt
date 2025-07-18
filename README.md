# MediaChain  
Decentralized media distribution system using Storage cess smart contracts.  

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
