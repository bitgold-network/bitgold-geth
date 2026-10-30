<p align="center">
  <img src="https://cdn.bitgold.network/images/brand/bitgold_icon_256.png" width="120" alt="Bitgold Network icon" />
</p>

# Bitgold-Geth

Bitgold-Geth is the client of **Bitgold Network**, an independent public chain network forked from
[BNB Smart Chain (BSC) v1.8.1](https://github.com/bnb-chain/bsc).

## Official links

| | |
| --- | --- |
| Website | <https://www.bitgold.network> |
| Documentation | <https://docs.bitgold.network> |
| GitHub organization | <https://github.com/bitgold-network> |
| Tools | <https://app.bitgold.network> |
| Validators | <https://app.bitgold.network/staking/validators> |

## Networks

### Bitgold Mainnet

| Parameter | Value |
| --- | --- |
| Network name | Bitgold Mainnet |
| Chain ID | `618` |
| Native coin | Bitgold (**BTG**) |
| Decimals | 18 |
| Total supply | 200,000,000 BTG |
| Block explorer | <https://www.bitgold.live> |

RPC endpoints:

- `https://mainnet1.bitgold.network`
- `https://mainnet2.bitgold.network`
- `https://mainnet3.bitgold.network`
- `https://mainnet4.bitgold.network`
- `https://mainnet5.bitgold.network`
- `https://mainnet6.bitgold.network`
- `https://mainnet-jp.bitgold.network`
- `https://mainnet-sg.bitgold.network`
- `https://rpc.bitgold.network`

WebSocket is supported on the same hosts as well, e.g. `wss://rpc.bitgold.network`.

### Bitgold Testnet

| Parameter | Value |
| --- | --- |
| Network name | Bitgold Testnet |
| Chain ID | `617` |
| Native coin | tBitgold (**tBTG**) |
| Decimals | 18 |
| Total supply | 200,000,000 tBTG |
| Block explorer | <https://testnet.bitgold.live> |
| Faucet | <https://faucet.bitgold.network> |

RPC endpoints:

- `https://testnet1.bitgold.network`
- `https://testnet2.bitgold.network`
- `https://testnet3.bitgold.network`

WebSocket is supported on the same hosts as well, e.g. `wss://testnet1.bitgold.network`.

## Brand assets

- Chain / coin icon: <https://cdn.bitgold.network/images/brand/bitgold_icon_256.png>
- Favicon: <https://cdn.bitgold.network/images/brand/favicon.png>

## Building

Building the client requires Go (see [`go.mod`](go.mod) for the required version) and a C compiler.
Once the dependencies are installed, run:

```shell
make geth
```

To build the full suite of utilities:

```shell
make all
```

## License

The library (i.e. all code outside of the `cmd` directory) is licensed under the
[GNU Lesser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html),
also included in this repository in the `COPYING.LESSER` file.

The binaries (i.e. all code inside of the `cmd` directory) are licensed under the
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html),
also included in this repository in the `COPYING` file.
