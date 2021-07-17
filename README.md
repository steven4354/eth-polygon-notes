# eth-polygon-notes

## using brownie to test smart contract functions on mainnet:
https://iamdefinitelyahuman.medium.com/ethereum-mainnet-testing-with-python-and-brownie-82a61dee0222
https://betterprogramming.pub/getting-started-with-brownie-part-2-615a1eec167f


## adding polygon network to brownie:
https://www.youtube.com/watch?v=DrMm7lKo_WY
https://www.quicknode.com/

```
brownie networks add Polygon poly_mainnet_1 host="https://lingering-morning-snow.matic.quiknode.pro/1810b4dd0f0623879a12fdec9ff6323e2dc42e4f/" name="Polygon Mainnet - QuickNode" chainid=137 explorer="https://explorer-mainnet.maticvigil.com/"
```

```
brownie console --network poly_mainnet_1
```
