# taproot-marketplace-sc

```text
ETH, USDT, ...
buy: 2.5% sell: 2.5%

oBTC
buySell: 1%
```

## 1.24 Goerli Testnet

```text
OrdinalMarket
    Implement - OrdinalMarket (0.8.7 run 200)
    0xA1Ab6a54053Ebe1d7371e0A5F8cd8e8D880eA767

    ProxyAdmin - ProxyAdmin (0.8.7 run 200)
    0xEAf977b265e1E801a262EF03d3f2d8F52e3b7ce8

    TransparentUpgradeableProxy(Proxy) - (0.8.7 run 200)
        MockETH:
        0x0000000000000000000000000000000000000eee
        0x0000000000000000000000000000000000000Eee
        decimals: 18

        MockUSDT: 
        0x5c4773F833E6C135aAC582b3EF62176809da226c
        0x5c4773f833e6c135aac582b3ef62176809da226c
        decimals: 6

        MockUSDC: 
        0x26a24Ed2a666D181e37E1Dd0dF97257b3F4B214E
        0x26a24ed2a666d181e37e1ed0df97257b3f4B214e
        decimals: 6

        MockoBTC: 
        0x30163F5CbfDe7007a3CEE0a117eF8eAb4Db36726
        0x30163f5Cbfde7007a3cee0a117ef8eab4db36726
        decimals: 18

        Admin: 
        0x2faf8ab2b9ac8Bd4176A0B9D31502bA3a59B4b41
        0x2faf8ab2b9ac8bd4176a0b9d31502ba3a59b4b41

        _DATA:
        0xf8c8765e0000000000000000000000005c4773f833e6c135aac582b3ef62176809da226c00000000000000000000000026a24ed2a666d181e37e1dd0df97257b3f4b214e00000000000000000000000030163f5cbfde7007a3cee0a117ef8eab4db367260000000000000000000000002faf8ab2b9ac8bd4176a0b9d31502ba3a59b4b41

    0x4eef20eB413Ab25aAfD6bBc57ec742A393D710c3

OrdinalBTCInscribe
    Implement - OrdinalBTCInscribe (0.8.7 run 200)
    0xbF609036C023C739c943e55f6507484A9bFB8f51

    ProxyAdmin - ProxyAdmin (0.8.7 run 200)
    0x080932d5D794EaDA25AAE2D51c3dA80FCfFbcB1A

    TransparentUpgradeableProxy(Proxy) - (0.8.7 run 200)
        MockWBTC:(clone WBTC(0x2260FAC5E5542a773Aa44fBCfeDf7C193bc2C599) on etherscan)
        0x6f034EfD11f0b5b5322A5C8aB9e72547438a13c3
        decimals: 8

        _WETH: 0x47693bCC8B81f108D8d809ed73aC6D4897908805
        _WBTC: 0x6f034EfD11f0b5b5322A5C8aB9e72547438a13c3
        _USDT: 0x5c4773F833E6C135aAC582b3EF62176809da226c
        _oBTC: 0x30163F5CbfDe7007a3CEE0a117eF8eAb4Db36726
        _pool_WBTC: 0x254af7D1e4fbb892Bf0BeCA9A1f4460068fB4d45
        _pool_USDT: 0xbffD03dA1245466B068058BC395a70F78C5d11cB
        _pool_oBTC: 0xc7C04F09feC92dAE39Efef8267CDF1cC018D35e0

        Admin: 
        0x2faf8ab2b9ac8Bd4176A0B9D31502bA3a59B4b41
        0x2faf8ab2b9ac8bd4176a0b9d31502ba3a59b4b41

        _DATA: 
        0x8a29e2de00000000000000000000000047693bcc8b81f108d8d809ed73ac6d48979088050000000000000000000000006f034efd11f0b5b5322a5c8ab9e72547438a13c30000000000000000000000005c4773f833e6c135aac582b3ef62176809da226c00000000000000000000000030163f5cbfde7007a3cee0a117ef8eab4db36726000000000000000000000000254af7d1e4fbb892bf0beca9a1f4460068fb4d45000000000000000000000000bffd03da1245466b068058bc395a70f78c5d11cb000000000000000000000000c7c04f09fec92dae39efef8267cdf1cc018d35e00000000000000000000000002faf8ab2b9ac8bd4176a0b9d31502ba3a59b4b41

    0xCe11e6E40bea0A0F361a81d50d52555AB710b503
```
