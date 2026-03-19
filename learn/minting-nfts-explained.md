# Minting NFTs on PrimePort

## Using the Drops System

The Drops system on PrimePort allows creators to launch NFT collections with configurable mint schedules, whitelist phases, and pricing waves. For collectors, it's the primary way to mint NFTs at primary sale prices before they reach secondary market.

> **Note:** The Drops system currently operates on **XDC Network**.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-03-19 a las 20.12.40.png" alt=""><figcaption></figcaption></figure>

***

### For Collectors. Minting a Drop

#### Finding Active Drops

Go to [primeport.xyz/drops](https://primeport.xyz/drops) and select the **Active** tab. Each drop card shows the collection name, mint price, and creator.

#### Minting

Open a drop and click **Mint**. Select the quantity you want to mint, confirm you meet any whitelist requirements if applicable, and click **Confirm**. Approve the transaction in your wallet.

Minted NFTs will appear in your profile immediately after the transaction confirms on-chain.

#### Upcoming Drops

The **Upcoming** tab lists drops that have not yet opened for minting. Check back on the listed launch date or follow the project's socials for whitelist announcements.

#### Past Drops

The **Past** tab shows completed drops. Click any past drop to view the collection on the secondary marketplace.

***

### For Creators. Launching a Drop

#### Step 1. Apply for Access

Drops are permissioned. Connect your wallet to PrimePort and click **Create A Drop** in the bottom-right corner. Fill out the application form — this is sent to the PrimePort team for review.

Applications take a minimum of **48 hours** to process. The team may request a call to verify project authenticity.

#### Step 2. Access My Drops

Once approved, disconnect and reconnect your wallet. A **My Drops** option will appear in your profile menu above **Sign Out**. Click it to enter the drop management dashboard.

#### Step 3. Configure General Settings

Click your drop and fill in the **General** section:

* Name, symbol, and description
* Mint dates and total quantity
* Collection image
* Image hosting: toggle **on** to let Prime Numbers manage your images via IPFS, or toggle **off** to self-host

Hit **Update** before navigating away, unsaved changes are lost.

#### Step 4. Deploy Your Smart Contract

Go to the **Contract** tab and click **New Contract**. Confirm the deployment transaction in your wallet. Once confirmed, your collection contract is live on XDC Network.

#### Step 5. Set Earnings Address

In the **Earnings** section, enter the wallet address where mint proceeds should be sent. Save and confirm the transaction.

#### Step 6. Upload Collection Assets

* **Gallery** — Up to four preview images shown on the drop page
* **Team** — Add team member names, roles, and photos
* **More Info** — Spotlight one NFT with detailed description; add a collection banner
* **FAQ** — Add anticipated questions and answers for your community
* **NFTs** — Upload NFTs individually or in bulk via the CSV template. The quantity here must match the number set in General, or scheduling will fail

#### Step 7. Update the Smart Contract (Critical)

In **Important Settings**, press both buttons in order:

1. **Update Metadata** → confirms with "Updated base URL"
2. **Update Total NFT** → confirms with "Updated max supply"

Both transactions must be confirmed in your wallet. Skipping either step will cause your drop to malfunction at mint time.

#### Step 8. Schedule Your Drop

Go to the **Schedule** section. If it shows an error, your NFT count in the NFTs section does not match the quantity in General, fix that first.

Click **Create New** to define a schedule. You can configure:

* **Whitelist phase** — restrict early minting to specific wallet addresses
* **Pricing waves** — lower prices during early windows to reward fast minters
* **Public phase** — open minting start date and time

Click **Create** to save the schedule. Your drop will now appear in the **Upcoming** section of the Drops page.

***

### Gas Costs

XDC Network gas fees are near-zero. Deploying a contract, updating metadata, and scheduling a drop costs a negligible amount of XDC in total.

***

### See Also

* Minting NFTs on PrimePort
* Supported Networks. XDC Network details and RPC
