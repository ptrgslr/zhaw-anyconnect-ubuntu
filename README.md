# quick guide to install Cisco Secure Client for Ubuntu (24.04)

go to ras.zhaw.ch and download Cisco Secure Client and follow Step 1 and Step 2 on the site
Locate the downloaded file cisco-secure-client-linux64-#.#.#####-core-vpn-webdeploy-k9.sh (Step 2)
befor installing (Step 3), you have to follow the instructions from https://www.wikihow.com/Execute-INSTALL.sh-Files-in-Linux-Using-Terminal
or as described here:
open terminal

open folder where the .sh file is, for example: cd Downloads/

make the install.sh file executable: sudo chmod +x cisco-secure-client-linux64-#.#.#####-core-vpn-webdeploy-k9.sh
If you don’t see an error, you’ll know the install script is now executable

install Cisco Secure Client
sudo bash cisco-secure-client-linux64-#.#.#####-core-vpn-webdeploy-k9.sh

start Cisco Secure Client: gtk-launch com.cisco.secureclient.gui

connect to: ras.zhaw.ch
