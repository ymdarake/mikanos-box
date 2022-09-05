# image for developing MikanOS

## setup
```zsh
vagrant up
vagrant ssh
### then vagrant terminal
wget -q https://www.ubuntulinux.jp/ubuntu-ja-archive-keyring.gpg -O- | sudo apt-key add -
wget -q https://www.ubuntulinux.jp/ubuntu-jp-ppa-keyring.gpg -O- | sudo apt-key add -
sudo wget https://www.ubuntulinux.jp/sources.list.d/xenial.list -O /etc/apt/sources.list.d/ubuntu-ja.list
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install ubuntu-desktop
```

## TODO
- [ ] improve provision.sh

