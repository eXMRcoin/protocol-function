![Logo](https://github.com/eXMRcoin/Ethereum-Monero/blob/master/eXMR-master/logo1.png?raw=true)
# EXMR 
Our repository is private for security.. 
# Project visit GetCryptoPayments.org®
➥A project based on Merchants tools: payment gateway, multi-coins wallet and point of sales, will make EXMR increase its value.<br> 
➥A large number of stores and online businesses, will be able to receive payments in our EXMR and other cryptocurrencies.<br>
➥GetCryptoPayments.org® by EXMR  Will support more than 130 Cryptocurrencies on your platform and will be added by our voting system.<br>
➥Offering plugins for all the popular webcarts used today: Prestashop; Oscommerce; Magento; woocommerce; WHMCS

# ANDROID & iOS APP<br>
➥Here you can send and receive your virtual coins.<br>
➥You can receive instant payments in any Cryptocurrency you choose, using your wallet or a qr code. <br>
➥Synchronization of your account to see the payments or deposits received.<br>

# Developer Team<br>
➥pnija<br>
➥albertnanita<br>
➥JulianIsrael<br>
➥anand230999<br>
➥vipinmohan22<br>

# Milestone<br>
⌘ Alpha Version August 2018 "Ongoing"<br>
 🍀 Features: <br>
✦ Registration and log in with OTP system.<br>
✦ Voting system to add coins per reach 70,000 points.<br> 
✦ From 1 to 5 wallets in operation.<br> 
⌘ Beta Version this September 2018<br>
✦ The function of add store profiles. <br>
✦ Merchant tools From 1 to 5 coins to receive online payments.<br>
✦ Swap between those 1-5 coins & more testnet functions.<br>
⌘ Official Launch this December 2018<br>
⌘ First bonus December 2018 <br>
# About Smart contract 
 <article class="markdown-body entry-content" itemprop="text"><h1><a href="#protocol-Function" aria-hidden="true" class="anchor" id="user-content-protocol-demo"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d=""></path></svg></a>Protocol-Function</h1>
<p>This repository of smart contracts contains the EXMR Protocol to demonstrate Leverage on-chain using 0x and Relayers</p>
<h1><a href="#experimental-code" aria-hidden="true" class="anchor" id="user-content-experimental-code"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d=""></path></svg></a>Experimental code</h1>
<p>This repository contains experimental code and is not suitable for production usage.</p>
<h1><a href="#smart-contracts" aria-hidden="true" class="anchor" id="user-content-smart-contracts"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d=""></path></svg></a>Smart Contracts</h1>
<p>The smart contracts are being built using truffle, and tested on the Kovan network. All contracts currently belong in the same file for ease of use while importing to the Remix IDE for quick tests.</p>
<details open="">
    <summary>
        Oracle.sol
    </summary>
    <p>
        Provides price feeds sourced from various price feed in payment gateway.
    </p>
</details>
<details>
    <summary>
      PriceFeed module
    </summary>
    <p>
        We will be use price feed from api.coinmarketcap.com via Oraclize. This module will be open to users who can add their own tokens inside our Payment Gateway (extend token.sol)
    </p>
</details>
<details>
    <summary>
      Wallet.sol
    </summary>
    <p>Contains business logic to calculate price, Margin account, &amp; EXMR balances. Also calculates margin balances.
    </p>
</details>
<details>
    <summary>
      SalesManager.sol
    </summary>
    <p>Handles accounts. Contains simple Payments operations on Sales objectives.
    </p>
</details>
<details>
    <summary>
      PaymentsManager.sol
    </summary>
    <p>Handles positions. Contains simple Sales operations on Payments objectives.
    </p>
</details>
<details>
    <summary>
      A placeholder OrderManager.sol
    </summary>
    <p>Temporarily handles orders for demo purposes.
    </p>
</details>
</article>
