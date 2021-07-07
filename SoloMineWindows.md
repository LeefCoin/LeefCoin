# Download the LeefCoin Core tools

If you don't have LeefCoin core installed on your computer, please do that first.

The LeefCoin core tools can be downloaded from [here](https://github.com/LeefCoin/LeefCoin/releases/download/1.0/LeefCoinWindows.zip)
 
After downloading, unzip the zip file, and place the "leefcoin-cli.exe" and "leefcoin-tx.exe" in the same folder LeefCoin.exe is in.

You can delete delete "leefcoin-qt.exe" from your computer.
# Start Mining

Go to the folder where LeefCoin.exe is in.
Create a new file and name it Mine.bat, paste the following information into Mine.bat:

    @echo off
    set SCRIPT_PATH=%cd%
    cd %SCRIPT_PATH%
    echo Press [CTRL+C] to stop mining.
    :begin
     for /f %%i in ('leefcoin-cli.exe getnewaddress') do set WALLET_ADDRESS=%%i
     leefcoin-cli.exe generatetoaddress 1 %WALLET_ADDRESS%
    goto begin
    
    
Save the file, and open LeefCoin.exe, then Open Mine.bat.

Every time you want to start Mining, just open LeefCoin.exe and Mine.bat!
