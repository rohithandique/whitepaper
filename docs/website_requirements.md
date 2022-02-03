# Common requirements
Check the [whitepaper](https://github.com/chatpuppy/whitepaper).

Design style: flat and simple, like material UI(https://mui.com)

Programmer should give good suggestion of aboved tasks according their experience.

# 1- Landing page

Refer to:
![](https://tva1.sinaimg.cn/large/008i3skNgy1gyyciozmt6j30u023u0xn.jpg)

## Elements of Landing page
### 1.1- logo: 
![](https://tva1.sinaimg.cn/large/008i3skNgy1gz0ggpenvqj30go0goaab.jpg)

### 1.2- name left to the logo: 
`ChatPuppy` 
(Make sure the lower or upper case)

### 1.3- Slogon
* A super secured NFT-based wallet-to-wallet instant messanger dapp for web3
(find place to put)

### 1.4- menu
* Home(this landing page)
* Open Chat Dapp
* Marketplace
* Mint

### 1.5- Buttons
* Open Chat Dapp
* Marketplace
* Mint
(Find suitable place to put these buttons, let user easy to enter)

### 1.6- Features
(Find places to put these features with suitable images)

* NFT-based and crypto wallet-to-wallet instant messanger. Any blockchain accounts can use this messenger with limited functionality, but unlimited to the NFT holders.
* 3rd-part NFTs integrated, such as `CryptoPunk` etc.
* Support group chat and peer-to-peer messaging.
* No need register or login by email, phone number or any of your identity.
* Put your chat URI or chat room URI on any websites or dapps, click and chat, never easy like this.
* Supporting by xxnetwork, messaging is fully decentralized, crypted, mixed, and throught random gateways all over the world. 
* No servers, AI, companies or goverments can see the messages, inercept the  messages, save the messages, anylize the messages, modify the messages or delete the messages.
* Quantum secured encrypt algorithm(optioned) protects messages safest in the future.
* Sending or recieving messages over multi-chains available.
* No any messages save on blockchains. Fully peer-to-peer instant messaging.

### 1.7- NFTs showcase
Can download some NFT images from https://www.nft-stats.com/collection/fastfooddoge to design.

### 1.8- Social
* Twitter: @chatpuppynft
* Discord: https://discord.gg/QN658sJWkk
* Telegram: https://t.me/chatpuppy
* Github: https://github.com/chatpuppy
* Whitepaper: https://github.com/chatpuppy/whitepaper

### 1.9- joint the mail list

### 1.10- Privacy Policy & Terms of user

----------------

# 2- NFT Mint
Mint NFTs according to the random traits/variants and rarity by user.
Check the [whitepaper](https://github.com/chatpuppy/whitepaper) for details.

Refer to https://nft.doge-punks.io/

## 2.1- Smart contracts:
  * NFTCore: https://github.com/chatpuppy/contracts/blob/main/contracts/ChatPuppyNFTCore.sol
  * NFTManager: https://github.com/chatpuppy/contracts/blob/main/contracts/ChatPuppyNFTManager.sol

## 2.2- Elements
### 2.2.1- Contract Address
### 2.2.2- Buy Mystery box and mint
Mint a mystery box and unbox. After this operation, the user can get a random NFT.

Similar to the pic, but UI should be same as landing page.
![](https://tva1.sinaimg.cn/large/008i3skNgy1gz0hibbd0xj30r40e8dgt.jpg)

### P.S Metadata of NFT
JSON file format:
```
{
	"name": "Name_Collection #1",
	"description": "Name_NFT_Collection",
	"image": "ipfs://Name/1.png",
	"dna": "23868c0bcb4f98cd025894359a3b7e5cfd4e668d",
	"edition": 1,
	"date": 1643541947732,
	"attributes": [{
			"trait_type": "Background",
			"value": "Yellow"
		}, {
			"trait_type": "Skin body",
			"value": "Black"
		}, {
			"trait_type": "Eyes",
			"value": "Angry"
		}, {
			"trait_type": "Mouth",
			"value": "Cheeky"
		}, {
			"trait_type": "Hat",
			"value": "Halo"
		}, {
			"trait_type": "Cloth",
			"value": "White shirt"
		}
	]
}
```

-----

# 3- Marketplace
Refer to https://market.dragonkart.com/

The only purchase token is `BNB`.

## 3.1- Smart contracts:
* Marketplace contract: https://github.com/chatpuppy/contracts/blob/main/contracts/ChatPuppyNFTMarketplace.sol

## 3.2- Elements
### 3.2.1- All salable NFTs list
Click the NFT item, open the buy details page and buy.

### 3.2.2- My owned NFTs list
Click the NFT item, open the sell details page and sell.

### 3.2.3- Onsale list
Click the NFT item, open the nft details page and change price.


