# 👷‍♂️🚧 This library is under construction 🚧👷‍♂️
## multichain-wallet-sdk [multichain wallet development kit]

### 📡Supported Network List
- EVM based networks
- Solana
- BNB Beacon Chain (Temporarily disabled)

[Documentation](https://cybers-organization-5.gitbook.io/multichain-wallet-sdk-documentation)

### installation

```
npm install multichain-wallet-sdk
```

### import example (es5)

```javascript
const { EthereumWallet } =  require('multichain-wallet-sdk');
```

### import example (es6)

```javascript
import { EthereumWallet } from  'multichain-wallet-sdk';
```

### functions(Ethereum)

- Create wallet
- Recover wallet from phrase words
- Create master seed from mnemonic
- Create account
- Get token detail
- Get token balance
- Send ETH
- Token approve
- Token transfer
- Check address is contract address (util function)
- Check contract is NFT contract (util function)
- Check contract is ERC721 NFT (util function)
- Check contract is ERC1155 NFT (util function)
- Get contract object from address and ABI interface(util function)
- Convert GWEI to WEI (util function)
- Convert GWEI to ETH (util function)
- Convert WEI to ETH (util function)
- Get latency of JSON RPC endpoint (util function)
- GET latency of websocket endpoint (util function)
  
### functions(Solana)
 - Create wallet
 - Recover wallet from mnemonic phrase
 - Get key pair from private key
 - Create account
 - Recover account from private key
 - Get token/SOL balance of address
 - Send SOL
 - Transfer token
 - Get provider from RPC url (util function)
 - Get transaction from hash (util function)
 - Get existing token list of network (util function)
 - Get token detail from token address (util function)

### functions(BNB Beacon Chain)
- Create wallet
- Recover wallet from mnemonic phrase
- Recover account from private key
- Get BNB balance
- Send BNB
- Transfer tokens

Contribute [here](https://github.com/mohnate/multichain-wallet-sdk/fork).
Submit issues [here](https://github.com/mohnate/multichain-wallet-sdk/issues).

### More blockchains and networks will be added.

## Enjoy your work !
Made with ❤ by [mohnate](https://github.com/mohnate)
