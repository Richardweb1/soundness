Soundness Testnet Registration (NO VPS REQUIRED)
About Soundness Layer
Soundness Layer is a decentralized verification layer that aims to dramatically reduce on chain costs for verifying Zero Knowledge Proofs (ZKP) while ensuring fast finality and censorship resistance.
By leveraging parallel execution (Sui) Move secure contracts,
and Walrus decentralized storage, 
Soundness Layer supports a wide range of use cases from zk Rollups to zkApps without sacrificing performance or decentralization.

Backed Image

Key Features
Fast Finality: Proofs verified in seconds.
Censorship Resistance: No single entity can block or reorder transactions.
Shared Economic Security: Validators re-stake assets across multiple blockchains.
Cross-Chain Interoperability: Proofs efficiently verified across different networks using decentralized data availability.
Steps to Register for the Soundness Testnet
Visit the Official Website. 
https://soundness.xyz/
Submit your email (try to use the same email as your GitHub account).

Create a Repo on GitHub & Launch a Codespace
http://github.com/codespaces
Open a terminal in your Codespace and run the following commands:

sudo apt update && sudo apt upgrade -y
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness layer/main/soundnessup/install | bash
source /home/codespace/.bashrc
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
. "$HOME/.cargo/env"
soundnessup install
soundnessup update
Usefull commands

To Generate the key

soundness-cli generate-key --name my-key
Generate your key and save it , DO NOT SHARE IT!

To export the key

soundness-cli export-key --name my-key
To list generated keys

soundness-cli list-keys    
To import key from mnemonic

soundness-cli import-key  --name <NAME>  --mnemonic <MNEMONIC>
Join Discord
https://discord.gg/ZrCbgE2q
Go to # Testnet-access and submit your Pub-Key

The registration is currently closed but if you already registred you can now play the game and generate the proofs

Done!
sudo apt update && sudo apt upgrade -y
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
