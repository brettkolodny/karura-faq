## Why is the Karura app not connecting to my Polkadot.js extension?
The Karura app may have trouble connecting to your Polkadot.js extension for a few reasons. Please try the following:

Make sure that your extension is set to “Allow use on any chain.” Refresh the web page.
![](https://i.imgur.com/mU8Edl5.png)

Make sure that you are allowing the website access to your extension. Open “Manage Website Access” and make sure that apps.karura.network is allowed. Refresh the web page.
![](https://i.imgur.com/xLXSnU2.png)

If both of those attempts fail, it’s possible that another browser extension is interfering or there is some other unknown issue with your browser. Consider downloading a new web browser and redownloading the polkadot.js extension. You can import your account to the polkadot.js extension in the new browser by selecting “import account from pre-existing seed” and entering your seed phrase. Then proceed to connecting the karura app at apps.karura.network
![](https://i.imgur.com/u0NwVY3.png)

## Can I use Polkawallet to connect to Karura?
Yes. Open the Polkawallet app and click on the three lines in the upper right corner.

Then, select the Karura logo and tap on the account you’d like to connect. You are now connected to the Karura network.

## How do I transfer KSM from Kusama to Karura?
Read our guide [here](https://wiki.acala.network/karura/defi-hub/inter-kusama-transfer#transfer-ksm-from-kusama-to-karura).

## How do I transfer KSM from Karura to Kusama?
Read our guide [here](https://wiki.acala.network/karura/defi-hub/inter-kusama-transfer#transfer-ksm-from-karura-to-kusama).

## Why is the KSM I sent to the exchange not showing up?
When sending KSM from Karura to an exchange, you should first send your KSM to Kusama. Please follow the instructions posted [here](https://wiki.acala.network/karura/get-started/karura-account/exchange). If you didn't do it this way, and instead send directly to the exchage from Karura, your KSM tokens won't show up in your exchange account. The reason for this is that the exchanges don't offer the right type of support for these transfers yet. Please contact them regarding how to get your KSM.

## Can I participate in bootstrapping?
You can participate in bootstrapping during the bootstrap period. The bootstrap period is the process by which new token pairs launch on the Swap. If a token pair exists on the Swap, that means the bootstrap period has ended for that trading pair. You can learn more [here](https://wiki.acala.network/karura/defi-hub/swap/bootstrap-a-pool).

## Can I participate in bootstrapping in Polkawallet?
Yes. Connect to the Karura network (see “Can I use Polkawallet to connect to Karura?” for instructions). Select the Kaura logo at the bottom of the page.

Then, select Swap and then Bootstrap and proceed the flow to provide your liquidity.

## Can I provide liquidity after the liquidity targets are met?
Yes.

## Can I provide liquidity after the bootstrapping period ends?
Yes. Once the token pair launches for trading, you can provide liquidity. However, you will not be able to provide single-sided liquidity. You must provide liquidity in token pairs.

## Are there additional incentives for users that participate in bootstrapping?
No. However, users that participate in bootstrapping are the pioneers that enable a new trading pair for the entire protocol, so you have that going for you, which is nice. Like all liquidity providers, users that provide liquidity during the bootstrapping period will receive their proportionate share of the trading fees for their trading pair.

## Are there liquidity mining rewards that will be given to liquidity providers (LPs)?
We may provide liquidity mining rewards for certain pairs, but will announce those rewards prior to when the bootstrapping begins for a given trading pair. 

There are no liquidity mining rewards being given for the KAR/KSM trading pair

## Can I withdraw my liquidity during the bootstrapping period?
No. You will have to wait until the trading pair is live to withdraw your liquidity.

## Can I provide liquidity multiple times throughout the bootstrap period?
Yes.

## What happens if I provide only one token as liquidity during the bootstrapping period?
If you are contributing to only one side of the pool (say Token A), you are effectively converting 50% of Token A into Token B based on the exchange rate when the Bootstrap ends (and the pool opens for trading).

## What tokens are the trading fees that I earn paid in?
Your trading fees will be paid in the same two coins that you provide liquidity to. The ratio of these tokens reflects the ratio in the pool.

## What are the risks with adding to an LP pool?
Providing liquidity to pools comes with some risks. You can learn more about those risks [here](https://wiki.acala.network/karura/defi-hub/swap/lp-returns-and-risks).

## Do I need to claim my LP tokens?
Yes.

## Why am I unable to provide liquidity?
Liquidity must always be provided in token pairs. The bootstrapping period is the only time that liquidity providers are able to provide single-token liquidity.

## Why am I getting "1010: Invalid Transaction: Inability to pay some fees, e.g. account balance too low?"
You may be getting this error if you don't have any KAR. We will be doing an upgrade the week of July 26 to address this issue.

If you do have KAR, try doing a slightly smaller transaction so that you can cover your fees.
