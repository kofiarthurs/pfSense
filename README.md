<h1>Routing Internet Traffic Through a pfSense Firewall</h1>

<h2>Description</h2>
For the setup, I have a domain controller, a pc and a firewall. These are their IPs:</br>
DC: 192.168.20.1/24</br>
PC: 192.168.20.2/24</br>
pfSense FW: 192.168.20.254/24</br>
</br>
The pc is connected to the DC and they both point to pfSense as the gateway. I configured pfSense to route the pc traffic to the internet.

<h2>Internet Access</h2>
<img src="https://imgur.com/Y97i3Fx.png" height="80%" width="80%"/>
<img src="https://imgur.com/zUwG8Ad.png" height="80%" width="80%"/>


<h2>Blocked Internet Access</h2>
<img src="https://imgur.com/txfw2ON.png" height="80%" width="80%"/>
<img src="https://imgur.com/9r2i6CC.png" height="80%" width="80%"/>

