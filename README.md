# V380FTP-Telnet
FTP and Telnet for V380 cameras, Also HTTP server

V380 cameras operating system is Linux. To running FTP and Telnet server, Also HTTP server at V380 cameras (only with anyka ak3918 chipset) do:

1- Place current repository files in a SD card less than 64GB which is formatted with FAT32 filesystem.

2- Put SD card into V380 camera and turn it on.

3- Wait couple of minutes while you hear sounds say setup is completed and etc.

4- Find IP of V380 camera in your network, It is usually `192.168.1.1`.

5- To checking servers if running navigate your browser to address: `http://IP_of_camera`, You'll see a page that show text "It is working ..." if servers are running.

6- Connect to V380 camera with FTP client and Telnet with username `root` and password `gzhongshi`.
