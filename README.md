
# 🛠 EthStorage V1 Trusted Setup Ceremony
**Purpose:** Generate secure zk-SNARK parameters for EthStorage’s circuits, ensuring transparency, decentralization, and long-term security for the entire community.

<img width="1500" height="840" alt="image" src="https://github.com/user-attachments/assets/0b5fa0a6-9e3a-4353-a739-27c8dd9943da" />

----
## 📋 Participation Requirements
- **OS:** Linux, macOS, or Windows with WSL2.
- **GitHub:**  
  - Account ≥ 1 month old  
  - ≥ 1 public repo  
  - Follows ≥ 5 accounts & has ≥ 1 follower  
  - Allows GitHub Gist read/write access
- **Internet:** Stable connection with good upload speed.
- **Dependencies:** Node.js ≥ 18, npm ≥ 9.2.0 (install via NVM recommended).
-----

## 📌 Why Participate
- **Strengthen Security** ; Prevent manipulation of zk-SNARK parameters.
- **Ensure Decentralization** ; Multiple participants reduce trust in any single party.
- **Guarantee Transparency** ; Fully auditable, open-source process.


## 🤝 How You Can Contribute
1. Join during the event window (Aug 13–22, 2025) and run the provided ceremony CLI tools to generate your randomness.
2. Submit your contribution to strengthen the setup.
3. Verify your participation and share proof to inspire others.

--------

## **Update & Upgrade System**
```
sudo apt update && sudo apt upgrade -y
```

## **Build Essentials Tools**
```
sudo apt install -y build-essential \
  curl \
  wget \
  git \
  unzip \
  pkg-config \
  software-properties-common
```

## **Install NVM** 
### Required for ceremony CLI 
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

```
nvm install 18
nvm use 18
nvm alias default 18
```

```
source ~/.bashrc
```

<img width="4028" height="900" alt="image" src="https://github.com/user-attachments/assets/4c8c343f-96ef-4d26-9390-74cbf61caa06" />


## **Create and Navigate into directory``
``
mkdir ceremony && cd ceremony
``

## Install NPM package
```
npm install -g @p0tion/phase2cli
```
<img width="4020" height="920" alt="image" src="https://github.com/user-attachments/assets/775d9017-7516-47c3-b088-312ccff7a152" />


## **Authenticate Github**
Running this line of code will show you alink to click that will direct you to [Github - http://github.com/login/device ](http://github.com/login/device)
```
phase2cli auth
```
<img width="4020" height="1396" alt="image" src="https://github.com/user-attachments/assets/c47b38e1-0e90-4c49-b213-6a44e4c89183" />

- [ ] Authenticate Github and copy the code from terminal
- [ ] Paste code on Github page
- [ ] Check back terminal to confirm you're IN. 

<img width="3552" height="624" alt="image" src="https://github.com/user-attachments/assets/e0d34f7d-ac68-4a81-840b-3bb47effea87" />


## Open a new screen/session with command 
```
screen -S ceremony
```
### Contribute to Ceremony 
```
phase2cli contribute
```
- [ ] Use the arrow key, select the second option **(EthStorage V1 Trusted Setup Ceremony)**
- [ ] Select ENTER and continue
- [ ] Select ENTER again to use the Random selection. 
<img width="4020" height="1058" alt="image" src="https://github.com/user-attachments/assets/7603d8cb-c81e-45fd-b89f-7a5feebb092a" />


## Screen Commands
- **Minimize / Detach session:** `Ctrl + A + D`
- **Reattach session:** `screen -r ceremony`
- **List sessions:** `screen -ls`
- **Close session from outside:** `screen -XS ceremony quit`


## 📚 Resources
- [Official Blog Post](https://blog.ethstorage.io/join-the-ethstorage-v1-trusted-setup-ceremony/)




