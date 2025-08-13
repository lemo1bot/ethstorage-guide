# 🚀 How I Contributed to EthStorage's Trusted Setup Ceremony

Hey crypto fam! 👋 Just finished contributing to EthStorage's trusted setup ceremony and wanted to share how easy it was. Here's my step-by-step guide:

## What is EthStorage?
EthStorage is a modular and decentralized storage Layer 2 that offers programmable key-value storage powered by DA. It enables long-term DA solutions for Rollups and opens up new possibilities for fully on-chain applications like games, social networks, AI, etc.

## Why This Ceremony Matters
This ceremony is conducted for EthStorage's Groth16 zk-SNARK circuits, which are integral to the proof-of-storage algorithm. Every participant makes the network stronger; your contribution helps safeguard the transparency, decentralization, and long-term security of EthStorage for the entire community.

## My Setup Process (took me about 10 minutes):

### 1. Prerequisites ✅
- GitHub account (at least 1 month old)
- At least 1 public repo
- Follow 5+ accounts and have 1+ follower
- Stable internet connection
- Node.js version 18 or higher

### 2. Installation Steps:
```bash
# Create working directory
mkdir ~/trusted-setup-tmp && cd ~/trusted-setup-tmp

# Install the CLI tool
npm install -g @p0tion/phase2cli

# Authenticate with GitHub
phase2cli auth
```

### 3. The Authentication Part:
- Run `phase2cli auth`
- Visit https://github.com/login/device
- Copy the auth code from terminal
- Paste it on GitHub and authorize p0tion
- Boom! You're in! 🎉

### 4. Start Contributing:
```bash
# For background running (recommended)
screen -S ceremony
phase2cli contribute -c ethstorage-v1-trusted-setup-ceremony
```

## What Happens Next:
- You'll join a queue (might take hours)
- When it's your turn, you'll be asked for entropy ("toxic waste")
- You can let CLI generate it automatically OR enter it manually
- The process runs automatically
- You'll get a completion message when done! 🎊

## Pro Tips:
- Use `screen` so it keeps running if you close terminal
- If connection drops, just restart the same command
- The ceremony runs until August 22, 2025
- After completion, clean up with `phase2cli clean && phase2cli logout`

## Why This Matters:
This ceremony ensures EthStorage's zk-SNARK circuits are secure. Every contribution adds randomness, making the system more decentralized and trustworthy. As long as one participant is honest and destroys their secret, the entire system remains secure.

## My Experience:
Honestly, it was super smooth! The CLI tool is well-made, and the process is straightforward. Took me about 10 minutes to set up, then just waited for my turn in the queue.

The best part? You're helping secure the future of on-chain data storage! 🌟

---

**Ceremony Status**: Running until August 22, 2025
**Time Investment**: ~10 minutes setup + queue wait time
**Difficulty**: Easy peasy! 🥧

If you're into crypto and want to contribute to something meaningful, this is a great way to get involved!

---

*Guide by @bank_of_btc | Based on official EthStorage documentation*

**Official Source**: https://blog.ethstorage.io/join-the-ethstorage-v1-trusted-setup-ceremony/

#EthStorage #TrustedSetup #Crypto #Blockchain #Contribution
