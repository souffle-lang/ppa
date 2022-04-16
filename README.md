# Souffle repository

## Fedora

dnf install https://souffle-lang.github.io/ppa/fedora/36/x86_64/souffle.fedora36repo.rpm
dnf install souffle

## Oracle Linux 8

dnf install https://souffle-lang.github.io/ppa/ol/8/x86_64/souffle.ol8repo.rpm
dnf install souffle


## Ubuntu

sudo wget https://souffle-lang.github.io/ppa/souffle-key.public -O /usr/share/keyrings/souffle-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/souffle-archive-keyring.gpg] https://souffle-lang.github.io/ppa/ubuntu/ stable main" | sudo tee /etc/apt/sources.list.d/souffle.list
sudo apt update
sudo apt install souffle
