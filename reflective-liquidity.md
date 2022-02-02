# ⛓ Reflective Liquidity

> _‘‘The enlightened one employs his mind as a mirror; it grasps nothing; it refuses nothing; it receives, but does not keep.”_\
> __\
> __— Chuang-tzu

The Eden Protocol introduces a set a new DeFi mechanism by composing properties of Constant Function Market Makers (like Uniswap, Sushiswap) and the mechanism of Protocol Owned Liquidity (pioneered by Olympus DAO).&#x20;

Let's take the example of a FRAX / USDC Uniswap V2 pool. The weight of FRAX and USDC are both 50% of the total value in that pool. In perfect conditions, if there were 500,000 FRAX in the pool, so too would there be 500,000 USDC. Since there is 500,000 each of FRAX and USDC, the total value is US$1,000,000.

Now we apply the _dao_ of Protocol Owned Liquidity — the user can bond their LP position for a governance token, let's call it gEDN. Now you have US$1,000,000 of protocol owned liquidity.

**If you replaced the 500,000 USDC with 500,000 EDN, you would still have US$1,000,000 of protocol owned liquidity.** As before, when 1 FRAX = 1 USDC, now 1 FRAX = 1 EDN. The liquidity is owned by the DAO. It's locked there. Token holders now hold gEDN, a fungible share of the protocol owned liquidity.&#x20;

EDN, however is not backed. It is a reflection of the locked FRAX. FRAX is directly bonded for gEDN. Under the hood, atomically, EDN is minted to reflect the FRAX, and both are deposited on behalf of the DAO to the LP pool. Since bonder and protocol contribute equal parts to the added protocol owned liquidity, they each receive 50% of the minted gEDN.

This is one of the things that makes Eden Dao Protocol truly unique — Reflective Liquidity creates a money-source carbon removal market to disrupt the existing money-sink markets.
