# RTD-VPN-Router

The RTD-VPN_Router is a simple script that you can use on a server, old PC, or a virtual machine at home or at a small business. It will automatically configure and setup that machine as a VPN router. 

After you have started the script you only have to direct all your traffic to the IP address of the VPN touter by updating the "gateway" on your DHCP service (usually on your internet router if you are a home user or small business). It is recommended that you set a static IP on the machine running the script.

For the simplest setup it is recommended that you install Debian or Ubuntu on the machine to be used as a VPN Router. 

### How to enroll...
Simply cut and paste this command in to a terminal on your computer. If you are using Windows, download the file "rtd-me.sh.cmd" and double click it. 

```

wget https://github.com/vonschutter/RTD-VPN-Router/raw/main/rtd-start-vpn-router && chmod +x rtd-start-vpn-router && bash rtd-start-vpn-router 

```

It would make me happy if any modification are shared back. 
