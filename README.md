# 🦄 buildspace x thirdweb - Build an DAO -
This project is for devs that want to better understand what the heck a DAO is by just building one themselves.
We'll be using this fancy tool called [thirdweb](https://thirdweb.com/?utm_source=buildspace) which lets us work with smart contracts using just JavaScript.

### **Welcome 👋**
To get started with this app., clone this repo and follow these commands:

1. Run `npm install` at the root of your directory
2. Run `npm start` to start the project
3. Start coding!

### **👻 How does a DAO work?**
Simply put, a DAO is a community of people with a shared bank account. Decisions around how that bank account is used are made by voting on different proposals that members create. When a proposal gets enough votes, it is executed on-chain!

### **💎 What we're going to do**
Build a web app for people to: connect their wallet → mint a membership NFT → receive a token airdrop → and actually vote on proposals. The web app is what I'll be calling our "DAO Dashboard". It's where our new members can join and it allows existing members to see what the DAO is up to.

### **🦊 Get Metamask**
Download the browser extension and set up your wallet [here](https://metamask.io/download/). Even if you already have another wallet provider, just use Metamask for now.
Once you set up your wallet, be sure to switch the network to "Rinkeby" which is the test network we'll be working with.

### ***📝 Create a place to run thirdweb scripts**
Now we need to actually write some scripts that let us create/deploy our contract to Rinkeby using thirdweb. The first thing we're going to do is create a .env file that looks like this in the root of our project.
```
PRIVATE_KEY=YOUR_PRIVATE_KEY_HERE
WALLET_ADDRESS=YOUR_WALLET_ADDRESS
ALCHEMY_API_URL=YOUR_ALCHEMY_API_URL
```
### ***🚀 Alchemy***
The last thing you need in your .env file is ALCHEMY_API_URL.
Alchemy essentially helps us broadcast our contract creation transaction so that it can be picked up by miners on the testnet as quickly as possible. Once the transaction is mined, it is then broadcasted to the blockchain as a legit transaction. From there, everyone updates their copy of the blockchain.

The last thing you need in your .env file is ALCHEMY_API_URL.
Alchemy essentially helps us broadcast our contract creation transaction so that it can be picked up by miners on the testnet as quickly as possible. Once the transaction is mined, it is then broadcasted to the blockchain as a legit transaction. From there, everyone updates their copy of the blockchain.

### **Questions?**
Have some questions: [buildspace Dashboard](https://app.buildspace.so/projects/COb520aae3-7925-42f4-a5e7-eaf718933766) and link your Discord account so you can get access to helpful channels and your instructor!

<p align="center">
<a href="https://www.linkedin.com/in/marjorie-ngoupende-dev/" target="_blank" >
  <img alt="Linkedin - Marjorie Ngoupende" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
</a>
<a href="mailto:marjorie.ngoupende@gmail.com" target="_blank" >
  <img alt="Email - Marjorie Ngoupende" src="https://img.shields.io/badge/Email--%23F8952D?style=social&logo=gmail">
</a> 
<br/>
  Made with :coffee: and ❤️ by <b>Marjorie Ngoupende</b>.
<p/>
