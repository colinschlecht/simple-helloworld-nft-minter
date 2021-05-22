This is a simple NFT minting (completed) walkthrough posted by alchemy - https://docs.alchemy.com/alchemy/tutorials/how-to-create-an-nft/how-to-mint-a-nft.

To mint an NFT using this code:

1. Clone down this repo and run npm install. You will need to create a .env file and include the following:

    * API_URL "https://eth-ropsten.alchemyapi.io/v2/<your-key-here>"
    * PRIVATE_KEY (found in your metamask account)
    * PUBLIC_KEY (found in your metamask account)

2. Upload an image file to the pinata pin managing site https://pinata.cloud/. 

3. Add the necessary metadata.

4. replace the tokenURI in scripts/mint-nft.js with the url that points to the json metadata.

5. run "node scripts/mint-nft" in the command line.

Please checkout the alchemy documentation above for further detailed instructions, including details on using their API, Metamask, and Pinata.