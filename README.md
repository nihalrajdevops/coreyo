Usage

First, clone the folder by using the below command:

git clone https://github.com/nihalrajdevops/coreyo.git

navigaate to the folder using below command(you need to have root access going forward)
cd /coreyo

once done copy the below command 
chmod +x openvpn-install.sh
Then run it:

./openvpn-install.sh
You need to run the script as root and have the TUN module enabled.

The first time you run it, you'll have to follow the assistant and answer a few questions to setup your VPN server.

When OpenVPN is installed, you can run the script again, and you will get the choice to:

Add a client
Remove a client
Uninstall OpenVPN
In your home directory, you will have .ovpn files. These are the client configuration files. Download them from your server and connect using your favorite OpenVPN client.
