<img width="2260" height="2232" alt="image" src="https://github.com/user-attachments/assets/eeeefa68-49b7-4440-bb99-79d2cffca402" />



## **1. Update & Upgrade System**
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






