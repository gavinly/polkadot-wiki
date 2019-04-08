# Node Operator / Validator

Validators secure the relay chain by staking DOTs, validating proofs from collators and participating in consensus with other validators.

These participants will play a crucial role in adding new blocks to the Relay Chain and, by extension to all parachains, such that parties can complete cross-chain transactions via the Relay Chain. Validators perform two functions. First, verifying the information contained in an assigned set of parachain blocks is valid (such as the identities of the transacting parties and the subject matter of the contract). Their second role is to participate in the consensus mechanism to produce the Relay Chain blocks based on validity statements from other validators. Any instances of non-compliance with the consensus algorithms result in punishment by removal of some or all of the validator’s staked DOTs, thereby discouraging bad actors. Good performance, however, will be rewarded, with validators receiving transaction fees in the form of DOTs in exchange for their activities.

## Guides

- [How to validate on PoC-4](./guides/how-to-validate.md) - Guide on how to set up a validator for PoC-4 and the Alexander testnet.
- [How to run your validator as a systemd process](./guides/how-to-systemd.md) - Guide on running your validator as a `systemd` process so that it will run in the background and start automatically on reboots.

## Other References

- [How to run a Polkadot node (Docker)](https://medium.com/@acvlls/setting-up-a-polkadot-node-the-easy-way-3a885283091f)
- [Getting Testnet DOTs](../learn/DOT.md#getting-testnet-dots)
- [VPS list](./guides/how-to-validate.md#vps-list)

## Security / Key Management

- [Validator Security Overview](https://github.com/w3f/validator-security)

## Monitoring Tools

- [Polkadot Telemetry Service](https://telemetry.polkadot.io/#/Alexander) - Network information including what nodes are running your chain, what software versions they are running, and sync status.
- [Polkadash](http://polkadash.io/) - Validator monitor
- [Other Useful Links](https://forum.web3.foundation/t/useful-links-for-validators/20)