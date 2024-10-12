# Nexus run on VPS ✨

## 🚀 Update packages
```bash
sudo apt update && sudo apt upgrade -y
```

## 📦 Install Dependencies
```bash
sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev  -y
```

## 🔧 Install Rust
```bash
sudo curl https://sh.rustup.rs -sSf | sh
```

## 📥 Add Rust to path
```bash
source $HOME/.cargo/env
export PATH="$HOME/.cargo/bin:$PATH"
```

## 🖥️ Create Screen
```bash
screen -S nexus
```

## 🛠️ Run Prover
```bash
sudo curl https://cli.nexus.xyz/install.sh | sh
```

⏳ **Please wait 10-20 minutes for the installation to complete. If successful, you will see it look like this:**  

![image](https://github.com/user-attachments/assets/835e8c7d-46f0-4b8a-a7aa-e62cb816691f)


✅ **Done!**

## 💾 Save your Prover Id:
```bash
cat $HOME/.nexus/prover-id
```

---

### 📌 Note:
There is no wallet or social connection yet, but the team is tracking your computer contributions and will add a leaderboard later.
Thank you for visiting! If you find this helpful, please give it a star ⭐.
