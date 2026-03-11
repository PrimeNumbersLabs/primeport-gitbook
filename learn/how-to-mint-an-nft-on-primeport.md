# How to Mint an NFT

PrimePort lets creators deploy their own ERC-721 smart contract and mint NFTs directly on-chain, no third-party launchpad required. The minting flozw runs on **XDC Network**, with near-zero gas fees.

> **Prerequisites:** An EVM-compatible wallet (MetaMask recommended) connected to XDC Network with a small amount of XDC for gas. See Getting Started for network setup.

***

### Single NFT vs. Batch Minting

|               | Single NFT                | Batch NFT                      |
| ------------- | ------------------------- | ------------------------------ |
| Use case      | One-of-a-kind pieces      | Collections of multiple NFTs   |
| Upload method | Individual form           | Individual or CSV bulk upload  |
| Contract      | Shared per creator wallet | Same contract, multiple tokens |

Both options follow the same contract deployment flow below.

***

### Step 1. Deploy on TestNet First

Before minting to MainNet, test your setup on the XDC TestNet at zero cost.

1. Connect your wallet to [primeport.xyz](https://primeport.xyz) on the **XDC Network**
2. Click **Upload** on the homepage
3. Click **New Contract** and fill in the form:
   * **Name** — your contract/collection name
   * **Symbol** — short ticker (e.g. `ARTXYZ`)
   * **Type** — ERC-721
   * **Ascii Mark** — a text-based trademark for your collection. Click **TOOL** to open the generator, create your mark, copy it back into the field
4. Agree to Terms of Service and click **Deploy on TestNet**
5. When prompted, switch to the XDC TestNet in your wallet
6. Get free Test XDC from the faucet link shown on screen _(your address must start with `xdc` — replace `0x` if using MetaMask)_
7. Return to PrimePort and click **Continue** to deploy the contract

***

### Step 2. Mint a TestNet NFT

Once your TestNet contract is deployed, click **Mint A NFT On TestNet** from the Next Steps list. Select **Single NFT** or **Batch NFT**.

Fill in the NFT form:

* **Image** — upload your artwork file
* **Title** and **Description**
* **Properties** — add any trait metadata (key / value pairs)

Click **Update Metadata**, then **Deploy on TestNet**. Choose whether to mint to your own wallet or airdrop to another address. Click **Mint** and confirm the transaction.

Go to your profile to verify the NFT looks correct before proceeding to MainNet.

***

### Step 3. Deploy Your Contract on MainNet

Once you're satisfied with the TestNet result:

1. Click **Upload** and select your existing contract
2. Click **Deploy Contract on MainNet**
3. Switch back to XDC MainNet when prompted and click **Continue**
4. Confirm the deployment transaction, this uses a small amount of real XDC

***

### Step 4. Mint on MainNet

Click **Mint A NFT On MainNet** from the Next Steps list. Follow the same form as TestNet — upload image, add title, description, and properties.

Click **Update Metadata**, then **Deploy on Mainnet**. Select mint-to-self or airdrop, click **Mint**, and confirm the transaction.

Your NFT is now live on XDC MainNet and visible on PrimePort.

***

### Step 5. Configure Royalties and Collection Info

The final step is **Update Collection**:

* **Cover photo and image** — displayed on the collection page
* **Description and slug** — your collection's public identity
* **Website link**
* **Fee recipient** — wallet address that receives royalty payments
* **Royalty percentage** — applied to all secondary sales of your NFTs

Click **Update Collection** and confirm. Your royalty settings are now written on-chain.

***

### Gas Costs

XDC Network gas fees are near-zero. A full deployment, TestNet test, MainNet contract, minting, and royalty setup, costs a negligible amount of XDC in total.

***

### See Also

* Using the Drops System — Launch a full collection with schedules and whitelists
* How to Sell an NFT — List your minted NFTs for sale
* Supported Networks — XDC Network RPC details
