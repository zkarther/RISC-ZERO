# RISC-ZERO TRUSTED SETUP

![image](https://i.hizliresim.com/atsj0mj.png)



### Linkler
 * [Telegram](https://t.me/emir111)
 * [Twitter](https://twitter.com/emirrfeyza)
 * [Discord](https://discord.gg/zkarther)


## 🟢 Sistem özellikleri

- Herhangi bir sunucu olur

## Kurulum
* Node Version Manager (NVM)

curl -sL https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh -o install_nvm.sh

## Daha sonra terminale aşağıdaki komutu girerek NVM'yi kuracağız

sh install_nvm.sh

## Lisans koşullarını kabul etmeniz gerekebilir

sudo xcodebuild -license


## KATKIDA BULUNACAĞIMIZ KISMA GEÇELİM


## 🟢 Sistemi güncelleyelim

sudo apt update
sudo apt upgrade -y
sudo apt install curl

## 🟢 Yeniden başlatalım

reboot


## 🟢 NVM İNDİRELİM [Burada hata alırsanız en alta bakın]

nvm install 16.20
nvm use 16.20

## 🟢 Temp oluşturalım

mkdir ~/p0tion-tmp
cd ~/p0tion-tmp

## 🟢 Yeni screen açalım

screen -S risc


## 🟢 Phase2cli İNDİRELİM

npm i @p0tion/phase2cli


## 🟢 Github ile kimlik doğrulaması yapalım

npx phase2cli auth

* Bu kodu yazdıktan sonra github doğrulaması için yönelendirileceksiniz. Verdiği kodu oraya yapıştıralım. Daha sonrasında sorduğu soruya enter tıklayın random seçip tekrar enter tıklayın

## 🟢 Sıranız geldiğinde otomatik olarak kendisi yapmış olacak. Twitterda paylaşmayı unutmayın.

![image](https://i.hizliresim.com/smgw5pz.png)



* NVM hatası alanlar sırasıyla aşağıdaki kodları yazın sonra nvm kısmından devam edin

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

command -v nvm

nvm install --lts

