
![הוסף כותרת](https://user-images.githubusercontent.com/85453562/124459621-2b10ca00-dd43-11eb-8f60-52ab5262143c.png)

# How to setup LeefCoin on your computer

# Windows

# Download and install
Download the latest LeefCoin Core release [Here](https://github.com/LeefCoin/LeefCoin/releases/download/1.0/LeefCoinWindows.zip)

Unzip the zip file, and Run LeefCoin.exe\
if you're not familier with LeefCoin Core, don't change the installation path.

# Connect to the network
After downloading and installing LeefCoin Core, LeefCoin Core should pop up automatically.
Close LeefCoin Core, and go to %APPDATA%/LeefCoin
then, create a file and name it leefcoin.conf, Copy and Paste the folowing info the file:

rpcuser=user
rpcpassword=password
rpcbind=0.0.0.0
rpcallowip=127.0.0.1
listen=1
server=1
addnode=104.248.117.139
addnode=46.101.93.246

save the file, and you're done! you can open LeefCoin.exe again!
