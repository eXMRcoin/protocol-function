#
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
