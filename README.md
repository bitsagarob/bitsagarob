Building bitcoin privacy & usability.


### Silent payments

Get paid by a static name and maintain full privacy.

- [silentpayments.net](https://silentpayments.net) : get your silent payment static name & combine it with a static lightning in a single QR 
- [payment-name-startos](https://github.com/bitsagarob/payment-name-startos) : your own node publishes your payment name, and watches if your name still points to your address.
- [spcommit-checkpoint-startos](https://github.com/bitsagarob/spcommit-checkpoint-startos) : catches a silent payment scan server hiding a payment.
- [blindbit-v1-shim](https://github.com/bitsagarob/blindbit-v1-shim) : Keep older silent payment scanning clients alive
- [silentpayments-measurements](https://github.com/bitsagarob/silentpayments-measurements) : Silent payments light clients measurements & spec draft


### MuSig2

One signature from several signers: multisig that is cheaper and maintains privacy on-chain.

- [Seedkeeper-Applet fork](https://github.com/bitsagarob/Seedkeeper-Applet/tree/musig2-nonce-vault) : MuSig2 nonce pool on a Seedkeeper smartcard
- [embit fork](https://github.com/bitsagarob/embit/tree/musig2) : BIP-390 musig keys in embit, the bitcoin library DoomSigner runs on


### Payment names

- [pydnssec-prover fork](https://github.com/bitsagarob/pydnssec-prover/tree/ecdsa-backend) : checks a payment name offline, on the device


### DoomSigner, where it all comes together

- [doomsigner-os](https://github.com/bitsagarob/doomsigner-os) : the OS that serves Doomsigner, boots into Doom first
- [doomsigner](https://github.com/bitsagarob/doomsigner) : the Doomsigner (Seedsigner fork) with support for silent payments & Musig2

### Other fun stuff

- [seedsigner-simulator](https://github.com/bitsagarob/seedsigner-simulator) : Run Seedsigner firmware in your browser
- [seedsigner-verify](https://github.com/bitsagarob/seedsigner-verify) : download & check the seedsigner firmware
- [btc-core-in-browser](https://github.com/bitsagarob/btc-core-in-browser) : Run Bitcoin Core in your browser
