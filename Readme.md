![Logo](https://github.com/eXMRcoin/EXMR-INFO/blob/master/eXMR-master/backclear.png?raw=true)
# EXMR FDN. (EXMR FOUNDATION)
# Smart contract details<br>
NAME: EXMR FND.<br>
SYMBOL: EXMR <br>
DECIMALS: 18 <br>
CONTRACT ADDRESS: 0x331fA6C97c64e47475164b9fC8143b533c5eF529 <br>
Explorer: EXMR FND. code: https://etherscan.io/address/0x331fa6c97c64e47475164b9fc8143b533c5ef529#code
<details>
    <summary>
        Show ABI here:
    </summary>
    <p>
        [{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address","name":"from","type":"address"},{"indexed":false,"internalType":"uint256","name":"value","type":"uint256"}],"name":"Burn","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"internalType":"address","name":"target","type":"address"},{"indexed":false,"internalType":"bool","name":"frozen","type":"bool"}],"name":"FrozenFunds","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address payable","name":"previousOwner","type":"address"},{"indexed":true,"internalType":"address payable","name":"newOwner","type":"address"}],"name":"OwnershipTransferredEv","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address","name":"from","type":"address"},{"indexed":true,"internalType":"address","name":"to","type":"address"},{"indexed":false,"internalType":"uint256","name":"value","type":"uint256"}],"name":"Transfer","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"internalType":"address","name":"token","type":"address"},{"indexed":false,"internalType":"uint256","name":"amount","type":"uint256"}],"name":"releaseMyExmrEv","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"internalType":"address","name":"token","type":"address"},{"indexed":false,"internalType":"uint256","name":"amount","type":"uint256"},{"indexed":false,"internalType":"uint256","name":"earning","type":"uint256"}],"name":"tokenBalanceFreezeEv","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"internalType":"address","name":"token","type":"address"},{"indexed":false,"internalType":"uint256","name":"amount","type":"uint256"},{"indexed":false,"internalType":"uint256","name":"earning","type":"uint256"}],"name":"tokenBalanceMeltEv","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"internalType":"address","name":"token","type":"address"},{"indexed":false,"internalType":"address","name":"user","type":"address"},{"indexed":false,"internalType":"uint256","name":"amount","type":"uint256"},{"indexed":false,"internalType":"uint256","name":"balance","type":"uint256"}],"name":"tokenDepositEv","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"internalType":"address","name":"token","type":"address"},{"indexed":false,"internalType":"address","name":"user","type":"address"},{"indexed":false,"internalType":"uint256","name":"amount","type":"uint256"},{"indexed":false,"internalType":"uint256","name":"balance","type":"uint256"}],"name":"tokenWithdrawEv","type":"event"},{"constant":false,"inputs":[{"internalType":"address[]","name":"recipients","type":"address[]"},{"internalType":"uint256[]","name":"tokenAmount","type":"uint256[]"}],"name":"Bounty","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[],"name":"acceptOwnership","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"","type":"address"},{"internalType":"address","name":"","type":"address"}],"name":"allowance","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"_spender","type":"address"},{"internalType":"uint256","name":"_value","type":"uint256"}],"name":"approve","outputs":[{"internalType":"bool","name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"","type":"address"}],"name":"balanceOf","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"uint256","name":"_value","type":"uint256"}],"name":"burn","outputs":[{"internalType":"bool","name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"_from","type":"address"},{"internalType":"uint256","name":"_value","type":"uint256"}],"name":"burnFrom","outputs":[{"internalType":"bool","name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"burningRate","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[],"name":"changeWhitelistingStatus","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[],"name":"changesafeGuardStatus","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"decimals","outputs":[{"internalType":"uint8","name":"","type":"uint8"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"target","type":"address"},{"internalType":"bool","name":"freeze","type":"bool"}],"name":"freezeAccount","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"token","type":"address"}],"name":"freezingOnOffForTokenType","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"","type":"address"}],"name":"frozenAccount","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[],"name":"manualWithdrawEther","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"uint256","name":"_amount","type":"uint256"}],"name":"manualWithdrawToken","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"maximumSupply","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"meltHoldSeconds","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"target","type":"address"},{"internalType":"uint256","name":"mintedAmount","type":"uint256"}],"name":"mintToken","outputs":[{"internalType":"bool","name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"name","outputs":[{"internalType":"bytes23","name":"","type":"bytes23"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"newOwner","outputs":[{"internalType":"address payable","name":"","type":"address"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"token","type":"address"},{"internalType":"bytes23","name":"_tokenName","type":"bytes23"},{"internalType":"bytes8","name":"_tokenSymbol","type":"bytes8"},{"internalType":"uint256","name":"_decimalCount","type":"uint256"},{"internalType":"uint256","name":"_minFreezingValue","type":"uint256"},{"internalType":"uint256","name":"_rateFactor","type":"uint256"},{"internalType":"uint256","name":"_perDayFreezeRate","type":"uint256"}],"name":"newTokenTypeData","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"owner","outputs":[{"internalType":"address payable","name":"","type":"address"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"token","type":"address"}],"name":"releaseMyExmr","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"safeGuard","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"uint256","name":"_burningRate","type":"uint256"}],"name":"setBurningRate","outputs":[{"internalType":"bool","name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"token","type":"address"},{"internalType":"uint256","name":"_minFreezingValue","type":"uint256"}],"name":"setMinFreezingValue","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"token","type":"address"},{"internalType":"uint256","name":"_perDayFreezeRate","type":"uint256"}],"name":"setPerDayFreezeRate","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"token","type":"address"},{"internalType":"uint256","name":"_rateFactor","type":"uint256"}],"name":"setRateFactor","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"uint256","name":"valueInSeconds","type":"uint256"}],"name":"setWithdrawWaitingPeriod","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"symbol","outputs":[{"internalType":"bytes8","name":"","type":"bytes8"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"token","type":"address"},{"internalType":"uint256","name":"amount","type":"uint256"}],"name":"tokenBalanceFreeze","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"token","type":"address"},{"internalType":"uint256","name":"amount","type":"uint256"}],"name":"tokenBalanceMelt","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"token","type":"address"},{"internalType":"uint256","name":"amount","type":"uint256"}],"name":"tokenDeposit","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"","type":"address"}],"name":"tokenTypeDatas","outputs":[{"internalType":"bytes23","name":"tokenName","type":"bytes23"},{"internalType":"bytes8","name":"tokenSymbol","type":"bytes8"},{"internalType":"uint256","name":"decimalCount","type":"uint256"},{"internalType":"uint256","name":"minFreezingValue","type":"uint256"},{"internalType":"uint256","name":"rateFactor","type":"uint256"},{"internalType":"uint256","name":"perDayFreezeRate","type":"uint256"},{"internalType":"bool","name":"freezingAllowed","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"token","type":"address"},{"internalType":"uint256","name":"amount","type":"uint256"}],"name":"tokenWithdraw","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"","type":"address"},{"internalType":"address","name":"","type":"address"}],"name":"tokens","outputs":[{"internalType":"uint256","name":"totalValue","type":"uint256"},{"internalType":"uint256","name":"freezeValue","type":"uint256"},{"internalType":"uint256","name":"freezeDate","type":"uint256"},{"internalType":"uint256","name":"meltValue","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"totalMintAfterInitial","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"totalSupply","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"_to","type":"address"},{"internalType":"uint256","name":"_value","type":"uint256"}],"name":"transfer","outputs":[{"internalType":"bool","name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"_from","type":"address"},{"internalType":"address","name":"_to","type":"address"},{"internalType":"uint256","name":"_value","type":"uint256"}],"name":"transferFrom","outputs":[{"internalType":"bool","name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address payable","name":"_newOwner","type":"address"}],"name":"transferOwnership","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"token","type":"address"}],"name":"viewMyReward","outputs":[{"internalType":"uint256","name":"freezedValue","type":"uint256"},{"internalType":"uint256","name":"rewardValue","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"userAddress","type":"address"}],"name":"whitelistUser","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"","type":"address"}],"name":"whitelisted","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"whitelistingStatus","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"}]

    </p>
</details>

<details>
    <summary>
      Staking System
    </summary>
    <p>
        We will be to holders who can add their own tokens inside in our Freeze to staking  (extend IERC20.sol)
    </p>
</details>
<details>
    <summary>
      Burn % Voting System
    </summary>
    <p>
        Now our community can vote to increase the percentage to burn our token for each transfer (into our EXMR_FDN.sol)
    </p>
</details>
<details>
    <summary>
      Bounty System
    </summary>
    <p>
        Now the developer community can earn EXMR FDN. by our Bounty program (into our EXMR_FDN.sol)
    </p>
</details><br>

# About us: <br>
We are motivating blockchain developers to integrate their Dapp's with EXMR FDN, and thus receive Bounty rewards, additionally you can start a custom Dapp's for EXMR FDN. and submit it to this repository of EXMR FOUNDATION, so that all developers can integrate into the work and thus all win rewards. <br>

# People can now start staking their EXMR FDN. <br> 
here: https://dapp.exmr.io <br>
New exchanges and Dapp's coming this 2020!!<br>

# About our current project <br>
We have the repository in private for security. <br>
You can visit here https://GetCryptoPayments.com® <br>

# About getcryptopayments.com
➥A project based on Merchants tools: payment gateway, multi-coins wallet and point of sales, will make EXMR FDN increase its value.<br> 
➥A large number of stores and online businesses, will be able to receive payments in our EXMR FDN and other cryptocurrencies.<br>
➥GetCryptoPayments.com® by EXMR FDN. Will support more than 130 to 2000 Cryptocurrencies on your platform and will be added by our voting system or payment fee.<br>
➥Offering integration plugins for all the popular webcarts used today: Prestashop; Oscommerce; Magento; woocommerce; WHMCS. etc

# Developer Team for this project<br>
➥pnija<br>
➥albertnanita<br>
➥Krishna<br>
➥Vipin Mohan<br>

# Milestones<br>
⌘ Beta Version August 2018 "Ongoing"<br>
 🍀 Services: <br>
✦ Fiat and coin services.<br> 
✦ Vault Wallet.<br> 
✦ Voting system to add coins per reach 70,000 points.<br> 
✦ From 1 to 100 token wallets services in operation.<br> 
⌘ Beta Version this September 2018<br>
✦ The function of add store profiles. <br>
✦ Merchant tools From 1 to 10 coins to receive online payments.<br>
✦ Swap between those 10-15 coins & more.<br>
⌘ Exchange + API  and IEO and Staking services for all coins developers
⌘ New UI-UX May 2019<br>
⌘ Launch this December 2020<br>

🍀 Features: <br>
✦ Swap between coins or tokens<br>
✦ Store profiles<br>
✦ Voting system<br>
✦ Fiat Services<br>
✦ Merchant Tools<br>
✦ Pay by Name<br>
✦ Multi Wallet<br>
✦ Payment Gateway<br>
✦ Vault Wallet<br> 
✦ Voting system<br>
✦ Point of Sales (POS)<br>
✦ Airdrop Sevices<br>
✦ ICO Sevices<br>
✦ Exchange Api<br>
& More..



