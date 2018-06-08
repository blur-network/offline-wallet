# Blur Offline Wallet Generator

The file above will generate a new wallet address and associated keys with a mnemonic for a BLUR wallet.  The generator is written purely in HTML so that it may be downloaded and opened on a computer that is not, or may never be, connected to the internet.

If you need to restore a wallet from your generated mnemonic, start the wallet binary with the option --restore-deterministic and you will be prompted to enter your mnemonic seed.

<h3>MS Windows: </h3?

Open Powershell and run: 

> ./blur-wallet-cli --restore-deterministic

<h3>Linux</h3>

Open a terminal and run:

> ./blur-wallet-cli --restore-deterministic

