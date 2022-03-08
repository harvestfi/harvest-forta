# Hardhat Forta Agent

This repo contains the smart contract code for the Harvest Forta agent (https://forta.org/) which triggers potential security alerts for Harvest on-chain presence.

It uses the Forta Agent Template by Arbitray Execution: https://github.com/arbitraryexecution/forta-agent-templates

### Development

Create and setup `./forta-config.json`:

```
{
    "jsonRpcUrl": "https://eth-mainnet.alchemyapi.io/v2/<your-key>"
}
```

### Testing 

Simple manual testing for now:

```
npm run tx 0x5c8ed6a6c3558a1ccbfeb875a59b0159e6e0f91af2cde5f871d78da57162bd00
```