## Liquidity Pools

A decentralised liquidity pool is a smart contract which holds two assets of balanced value for the purpose of facilitating decentralised finance features such as swapping one asset for another without the need for a traditional order book and custody of assets.

Providing liquidity is when you provide one or both of the assets to a liquidity pool. In doing so, you will be improving the depth of the pool and helping it become more effective at facilitating larger and cheaper swaps for users looking to utilize these liquidity pools. Obviously people don't do this just out of the kindness of their hearts, there must be some incentives in place to ensure there is a sustainable feedback loop in place.

## Revenue Potential

When users utilize a pool by swapping assets through it, they pay a proportionate fee which stays inside the pool. By providing liquidity, you receive LP tokens which represent a percentage share of all assets in the pool, this includes those fees which are absorbed by the pool during a swap. They are instantly attributed to the liquidity providers during that very swap.

It is very important to re-highlight the point that liquidity providers do not 'stake' their assets in a pool expecting back the exact same amount of tokens when they leave, but rather they receive LP tokens that represent a share of _all_ assets in the pool.

## Impermanent Loss

This presents a 'risk' of course, for instance, the number of units you put in is not the number of units you get out later on when you withdraw your liquidity. If the assets you put in change price between adding and removing, you might end up with more of one asset and less of the other. This can obviously work out in your favour, however, when this is unfavourable for you it is often referred to as 'impermanent loss'.

'Impermanent loss' is an issue that Spartan Protocol aims to combat through sustainable pools with circular incentives focused on rewarding the users who provide liquidity and utility to the protocol. 100% of the fee revenue is injected into the pools for the liquidity providers; there is no middleman taking a cut in this community-built-and-driven protocol.

## Curated Pools

Spartan Protocol pools have a special status reserved for the most active pools called 'Curated'. The community DAO decides which pools are added or removed from the Curated list using the on-chain DAO functionality. If a pool is Curated, it is enabled for a range of extra features and incentives. Curated LP tokens earn extra 'Dividends' ontop of the usual revenue and are able to also be staked in the DaoVault for extra yield and governance weight in proposals. For a Synth to be deployed/created, it must use an underlying Curated pool.

## Dividends

Most important of the Curated points to discuss here is 'Dividends', which are injected into the pool (in the form of SPARTA) whenever a qualifying swap is performed within a the pool. It doesn't come from the user performing the swap as the slip fee does, instead coming from the 'Reserve' contract which controls the flow of emitted SPARTA incentives throughout the protocol.

---

## Listing / Creating a Pool

Another way Spartan Protocol hands over control to its users is through its open listing policy. Literally anyone is free to permissionlessly list any standard BEP20 token any time they like by clicking a few buttons and providing the initial liquidity. You don't need permission from us or the token project or CZ 😂 if you want a pool, you are free to go ahead and create the pool.

It is advised to think and plan carefully before doing so though, as a general rule, pools become an efficient swap option at a minimum of ~$100,000 in liquidity. Ideally, all pools should aim to have more than $200,000 in liquidity so that they can have low swap fees and become a viable route for aggregators, therefore earning sustainable revenue to grow deeper in a feedback loop.

## Symmetrical Liquidity Add (Add Both)

When you add an equal value of each pooled asset, this is called a 'Symmetrical Liquidity Add'. This involves adding the two assets directly from your wallet to the pools in exchange for LP tokens representing your percentage ownership of assets in the pool.

## Asymmetric Liquidity Add (Add Single)

An asymmetric liquidity-add is when someone adds an amount of one or two assets to a pool that does not match the ratio of assets held within that pool (non-equal value). This results in the ratio of the pool slipping away from the outside market which will incentivize arbitrageurs (or users looking for a cheap deal on the respective token) to perform revenue-generating swap transactions.

When you do an 'Asymmetrical Add' (like in the screenshot above) half of your input will first be swapped through the pools for the other token, and then they will then both be added to the pools. It's kind of like interfacing two transactions, a swap and a 'Symmetrical Liquidity Add'. Be careful not to do this with large amounts or in shallow pools without checking the resulting LP units, USD value and percentage of loss in spot value.

## LP Tokens

You receive LP tokens at the same time as the respective liquidity add functions outlined above. You can choose to hold them in your wallet or if they are from a 'Curated' pool, you can stake them in the DaoVault for extra yield. You do not need to do anything with your LP tokens to have them earning the swap revenue and dividends.

Providing liquidity is generally regarded to be a longer-term time preference activity. You should do your own research on what pools you think will perform well and how long you think it will take to have the revenue build up to a level where the benefits outweigh the risks.

## Symmetrical Liquidity Removal (Remove Both)

When removing liquidity you can choose to receive both assets evenly just like when adding liquidity. Remember, your LP tokens represent a percentage share of the total pooled assets, by default that includes both assets.

## Asymmetric Liquidity Removal (Remove Single)

If you however choose to remove liquidity to 'one side' the process is very similar to the asymmetrical liquidity add. Firstly, a normal 'Symmetrical Liquidity Removal' is performed where both assets leave the pool of equal value. Then a swap is performed of the unwanted asset to the desired asset to leave you with only the asset you chose to receive. Keep in mind once again that performing a swap will result in slippage so always check your output amount and make sure you are happy with the result.

---

## Guides

- [Create / List Pool *Guide Coming Soon*](/liquidity-pools?id=guides)
- [Analyze Pools](/guides/liquidity/analyze.md)
- [Add Liquidity (Both)](/guides/liquidity/add-both.md)
- [Add Liquidity (Single)](/guides/liquidity/add-single.md)
- [Remove Liquidity (Both)](/guides/liquidity/remove-both.md)
- [Remove Liquidity (Single)](/guides/liquidity/remove-single.md)