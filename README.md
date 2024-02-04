# debian_based_setup


sudo apt update


# For_installing_brave_browser

sudo apt install curl

sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg

echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg] https://brave-browser-apt-release.s3.brave.com/ stable main"|sudo tee /etc/apt/sources.list.d/brave-browser-release.list

sudo apt update

sudo apt install brave-browser



# General utilities

sudo apt install gcc

sudo apt install python3-pip

sudo apt install ranger

sudo apt install neofetch



# Install vscode

sudo apt install snapd

sudo snap install code --classic


# discord

sudo snap install discord

