# Install requirements

Open Spotlight Search and type the following:

terminal

Double click on terminal.

Execute the following command, to open your downloads directory:

cd Downloads

Install Homebrew with the following command:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

Enter your sudo password to install Homebrew.

Install wget with the following command:

brew install wget


# Download

Download the MacOS wallet with the following command:


wget "https://github.com/LeefCoin/LeefCoin/releases/download/1.0/LeefCoinMacOS.dmg"


Download the MacOS Daemon & tools for your wallet with the following command:


wget "https://github.com/LeefCoin/LeefCoin/releases/download/1.0/LeefCoinDaemonMacOS.tar.gz"


# Extract the files

Extract the files with the following command:

tar -xzvf LeefCoinDaemonMacOS.tar.gz

# Install

Create the data directory for your wallet with the following command:


mkdir "$HOME/Library/Application Support/LeefCoin/"


Create the leefcoin.conf file with the following command:


nano "$HOME/Library/Application Support/LeefCoin/leefcoin.conf" -t


Paste the following info:

rpcuser=user

rpcpassword=password

rpcbind=0.0.0.0

rpcallowip=127.0.0.1

listen=1

server=1

addnode=104.248.117.139

addnode=46.101.93.246



Save the file with the keyboard shortcut ctrl + x.



