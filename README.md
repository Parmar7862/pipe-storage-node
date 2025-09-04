# ✨Pipe-Firestarter-Storage-Node
A step by step guide on how to Run Pipe Firestarter Storage node on Devnet.

**What is pipe firestarter ?**
</div>
Pipe Firestarter is a decentralized storage and delivery network, offering a blockchain-powered alternative to services like Google Drive and Cloudflare.

---

## Install All Dependencies👇

```
sudo apt update && sudo apt upgrade -y
```

```
sudo apt install curl iptables build-essential git wget lz4 jq make gcc postgresql-client nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev tar clang bsdmainutils ncdu unzip libleveldb-dev libclang-dev ninja-build -y
```

## Install rustup👇

```
curl https://sh.rustup.rs -sSf | sh
```

```
source $HOME/.cargo/env
```

Check version

```
rustc --version
cargo --version
```
---
# Lets start Installation👇

### Clone the PIPE Repo

```
git clone https://github.com/PipeNetwork/pipe.git
cd pipe
```

### Install pipe-cli

```
cargo install --path .
```

### Set-Up a NEW 

```
pipe new-user <your_username>
```

### Set-Up Your Password

```
pipe set-password
```

### Save Your `all file data`

```
nano ~/.pipe-cli.json
```

---
### Referral Program

Earn PIPE tokens by referring friends to the Pipe Network!

#### How It Works

1. **Generate Your Code**: Run `pipe referral generate` to get your unique referral code
2. **Share**: Give your code to friends who want to join Pipe Network
3. **Earn**: Receive 100 PIPE tokens when they complete a qualifying swap (1+ DevNet SOL)

#### Program Rules

- **Minimum Swap**: Referred user must swap at least 1 DevNet SOL to activate reward
- **Reward Amount**: 100 PIPE tokens per successful referral
- **Processing Time**: Rewards may take up to 24 hours to process
- **Fraud Prevention**: All referrals are subject to automated fraud checks
- **DevNet SOL**: Get free DevNet SOL at [https://faucet.solana.com/](https://faucet.solana.com/)

#### Commands

```
pipe referral apply 
```

#### Get Your referral code:

```
pipe referral generate
```

#### Check your referral stats

```
pipe referral show
```

---

### Swap to Pipe 

* Get Sol Devnet Faucet from [here](https://faucet.solana.com/)

* Swap

```
pipe  swap-sol-for-pipe <AMOUNT_SOL>
```

---
### Now lets Upload a file

```
pipe upload-file <FILE_PATH> <FILE_NAME>
```

* >Replace <FILE_PATH> & <FILE_NAME> with their actual file name : 

```
~/Name_of_your_file
```

### Create Public Link

```
pipe create-public-link <FILE_NAME>
```
* >Replace <FILE_NAME> which you have used earlier while uploading a file:

### Check Token-Usage

```
pipe token-usage
```
# Now Get the Firestarter Role on Discord 

</div>

### [Pipe Discord Channel](https://discord.gg/uWzVcHTT)

</div>

1. GO TO #FIRE-STARTER-SHARE AND UPLOAD YOUR NODE Link & Screenshoot
2. Upload more than 100+ GB Downloads to get Firestarter Role
3. Wait for 6 to 7 day to get Firestarter Role 

---

