# Complete Beginner Guide: Setting Up a Hyperliquid API Wallet

This guide is written for complete beginners who have never used a Web3 wallet before.

⚠️ **Important:** For the best experience, use a **desktop computer with Google Chrome browser**. Most Web3 wallets (including MetaMask) work most smoothly on Chrome desktop. Avoid using mobile phones for this setup process.

By the end of this guide, you will:
- Create your first Web3 wallet
- Connect it to Hyperliquid
- Enable trading
- Deposit ETH and USDC to Arbitrum
- Fund your Hyperliquid account
- Create a secure API wallet for automated trading

---

# Part 1: Create Your First Web3 Wallet (MetaMask)

Hyperliquid works with Web3 wallets. A Web3 wallet lets you control your crypto directly.

We will use **MetaMask**.

## Step 1.1: Install MetaMask

1. Go to the official MetaMask website (https://metamask.io) and click "Download MetaMask" at the top-right corner.
2. Install the browser extension.
3. Click **"Create a new wallet"**.
4. Create a password.
5. Write down your 12-word recovery phrase.

⚠️ This recovery phrase is extremely important. Anyone who has it can control your funds. Never share it.

After setup, you now have your own crypto wallet.

---

# Part 2: Visit Hyperliquid First (Before Depositing Funds)

Before moving any money, it's important to connect your wallet to Hyperliquid.

## Step 2.1: Go to Hyperliquid

Visit:

https://app.hyperliquid.xyz

If you are in the US or UK, you may need a VPN set to a supported region.

## Step 2.2: Connect Your Wallet

1. Click **Connect** (top-right corner).
2. Choose **MetaMask**.
3. Approve the connection.
4. Sign the message when prompted.

You are now connected.

## Step 2.3: Click "Enable Trading"

After connecting for the first time:

1. Click the **Enable Trading** button.
2. Sign the message in MetaMask.

This step activates your trading account on Hyperliquid.

Do this before sending funds.

---

# Part 3: Deposit ETH and USDC to Arbitrum

Hyperliquid uses the **Arbitrum network**.

You must have:
- **USDC on Arbitrum** (used as trading collateral)
- **ETH on Arbitrum** (used to pay gas fees)

If you're coming from Web2 (like Binance, Coinbase, etc.), this step means withdrawing crypto to your MetaMask wallet.

Follow the simple steps below to withdraw directly from a centralized exchange.

## Withdraw Directly from a Centralized Exchange (Recommended for Beginners)

If you already use Binance, Coinbase, Kraken, etc.:

### Step 1: Copy Your Wallet Address (Latest MetaMask UI)

In MetaMask:

1. Look at the **top-left corner** where you see **stacked network icons**.
2. **Hover** your mouse over those network icons.
3. A list of wallet addresses will appear.
4. Select the **first row** that shows **"Ethereum"** and your wallet address.
5. Click the **copy icon** on the right to copy the address.

### Step 2: Withdraw ETH to Arbitrum

On your exchange:
1. Go to Withdraw.
2. Select ETH.
3. Paste your MetaMask wallet address.
4. Select **Arbitrum network** (very important).
5. Confirm withdrawal.

### Step 3: Withdraw USDC to Arbitrum

Repeat the same steps for **USDC**.

Again, make sure you choose **Arbitrum network**.

After confirmation, your funds will appear in MetaMask on Arbitrum.

---

## Step 3.1: Verify USDC on Arbitrum

If USDC does not show in MetaMask:

1. Click "Import Token"
2. Enter the official Arbitrum USDC contract:

```
0xaf88d065e77c8cC2239327C5EDb3A432268e5831
```

Now you should see your balance.

---

# Part 4: Fund Hyperliquid

Now that you have ETH and USDC on Arbitrum, you can fund Hyperliquid.

### Method 1: Deposit from Inside Hyperliquid

1. Go to Hyperliquid.
2. Click **Deposit**.
3. Ensure the **Deposit Chain is set to Arbitrum**.
4. Enter the USDC amount.
5. Confirm in MetaMask.

After confirmation, your collateral will appear in Hyperliquid.

---

# Part 5: Create Your Hyperliquid API Wallet

The API wallet is used for bots.

It can trade but cannot withdraw funds.

## Step 5.1: Go to API Page

1. Click **More**.
2. Click **API**.

Or visit:

https://app.hyperliquid.xyz/API

---

## Step 5.2: Create API Wallet

1. Click **Create API Wallet**.
2. Enter a name (e.g., trading-bot-01).
3. Click **Generate** to create a random wallet address.
4. Click the **Authorize API Wallet** button next to the generated address.

---

## Step 5.3: Save the Private Key (Very Important)

You will only see it once.

1. Copy it immediately.
2. Store it in a password manager.
3. Never share it.
4. Never upload it to GitHub.

---

## Step 5.4: Authorize the API Wallet

1. Set validity to MAX (180 days).
2. Click **Authorize**.
3. Sign the message.

Your API wallet is ready.

---

Your Hyperliquid account is now fully set up for trading.

