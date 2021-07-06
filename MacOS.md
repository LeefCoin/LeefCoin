
# Download

Download the latest LeefCoin core wallet release [here](https://github.com/LeefCoin/LeefCoin/releases/download/1.0/LeefCoinMacOS.dmg)

Open the downloaded file, and you'll see an installation window, complete the installation instructions.

If you're not familiar with LeefCoin core don't change the installation path!

# Connect to the network

* Close LeefCoin Core

* Go to $HOME/Library/Application Support/LeefCoin/

* Create a leefcoin.conf file with the following info:


       rpcuser=user

       rpcpassword=password

       rpcbind=0.0.0.0

       rpcallowip=127.0.0.1

       listen=1

       server=1
       
       addnode=104.248.117.139
       
       addnode=46.101.93.246



* Save the file, and open LeefCoin Core.



