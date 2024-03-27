# COCO ecosystem contract deployments and relevant addresses

## COCO Contract on ETH mainnet

This is the original COCO address that has been our home since the beginning. Most (If not all) of the liquidity is on ETH Mainnet.

`0xe6dbeadd1823b0bcfeb27792500b71e510af55b3`

## COCO Uniswap v2 Pool on ETH mainnet

This is the uniswap pool that holds the liquidity for COCO transactions. The LP tokens are locked for 100 years.

`0xeae4c727ea43990ea92f427da36ddff8e72f6854`

This is a link to the Uniswap v2 pool as viewed on Dextools.
`https://www.dextools.io/app/en/ether/pair-explorer/0xeae4c727ea43990ea92f427da36ddff8e72f6854?t=1711118201308`


## COCO Community Fund

This is the community fund wallet, which holds treasury for giveaways and other purposes. This may be migrated to a gnosis multisig wallet when it's value exceeds 10kUSD
```
cococommunityfund.eth
0x76B7D88dd499C8D707eaaBFAfDf64451995Fe138
```

## COCO Contract on Arbitrum
This is not the same as the original CA because of how arbitrum works, but it is sort of like how WETH works, where actual COCO is deposited and held on a deposit contract on mainnet and then tokens are minted and then transferred around on arbitrum. Arbitrum COCO is then burned when they are subsequently withdrawn from the contract on ETH which causes the effect of not having any effect on the total supply.

To find the uniswap v3 pool on arbitrum, in MetaMask, set the network to Arbitrum and paste this address into the Token selector on the uniswap page.

0x12dd9147c2d03e13df492619e66899527575723b

## COCO Uniswap v3 Pool on Arbitrum

We are working to establish a market maker to set up arbitrage bots between the arbitrum pool and the mainnet pool. 

If you search for the Arbitrum contract on dextools, you can also find the contract address and information about the contract. 

0x9c758131591ef731340cac9b6dba2e8b93accb9f

https://www.dextools.io/app/en/arbitrum/pair-explorer/0x9c758131591ef731340cac9b6dba2e8b93accb9f

The Uniswapv3 LP tokens for this pool are held by cococommunityfund.eth and can be viewed on OpenSea.io

Note: There is an issue with updating arbiscan.io because they want a signature from the deployer, and we arent the original deployers so it is difficult populating the arbitrum pool with actual information.


## COCO Airdropper

This is a contract which was deployed to send COCO tokens to multiple people. It is occasionally used for different purposes. 

`0x9bb0cd0fa0e533f024c57e1954d896416208fdf4`

## AiCOCO

This is the AiCOCO contract, an NFT that was made in order to add a deflationary utility to COCO. You burn COCO in order to mint an NFT.

`0x2c64a8d8462960a687E586F2b3303774390948Cb`

Minted tokens can be viewed on opensea. You can mint tokens at [the main website](cocoethtoken.com)

`https://opensea.io/collection/aicoco`