## Notes

### using web3 to test polygon smart contracts

https://replit.com/@steven4354/ShimmeringPortlyOpenlook#index.js

## didn't work

### using brownie to test smart contract functions on mainnet
https://iamdefinitelyahuman.medium.com/ethereum-mainnet-testing-with-python-and-brownie-82a61dee0222
https://betterprogramming.pub/getting-started-with-brownie-part-2-615a1eec167f


### adding polygon network to brownie
https://www.youtube.com/watch?v=DrMm7lKo_WY
https://www.quicknode.com/

```
brownie networks add Polygon poly_mainnet_1 host="https://lingering-morning-snow.matic.quiknode.pro/<>/" name="Polygon Mainnet - QuickNode" chainid=137 explorer="https://explorer-mainnet.maticvigil.com/"
```

```
brownie networks add Polygon poly_mainnet_2 host="https://lingering-morning-snow.matic.quiknode.pro/<>/" name="Polygon Mainnet - QuickNode Polyscan" chainid=137 explorer="https://polygonscan.com/"
```

```
brownie console --network poly_mainnet_1
```

note: brownie console accepts python code (not js)

some issue with Contract.from_explorer not sure what's up
