# upgraded-succotash
# Artists Marketplace for NFTs

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
Hardhat was used for handling ethereum smart contracts. The smart contracts were inspired by https://dev.to/dabit3/building-scalable-full-stack-apps-on-ethereum-with-polygon-2cfb.

## Available Scripts

In the project directory, you can run:

npx hardhat node 

deploy the first marketplace contract using:

npx hardhat run --network localhost scripts/nftMarketDeploy.js 

taking note of the marketplace address it was deployed to, add the address in 
scripts/nftdeploy.js at marketaddressdeployed and src/contractconfig.js at NFT_MARKET_ADDRESS
before deploy the first marketplace contract using:

npx hardhat run --network localhost scripts/nftdeploy.js 

Then add the nft address it was deployed to and add it to src/contractconfig.js at NFT_ADDRESS

Now, start react app with:
npm start

You can view the website on your computer and even interact with it by using metamask chrome extension to list your own nfts! Yay!


<img src="ezgif-2-46d34f5c214b.gif" width="600" height="350"/>
