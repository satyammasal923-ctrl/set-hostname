hey here are the command for
change hostname,IP Addresses,
Gateway and DNS in Linux <br>
change hostname:-<br>
#hostname <br>
#hostnamectl set-hotname <br>

server1\.lab.example.com <br>
#nmcli con show <br>
#nmcli con mod "System eth0" <br>
ipv4.addresses"172.25.250.11/24" <br>
gateway <br>
#nmcli con mod "System eth0"v,br>
ipv4.gateway 172.254.250.25 <br>
dns <br>
#nmcli con mod "System eth0" <br>
ipv4.dns 172.254.250.25 <br>
to set all of the <br>
#nmcli con up "system eth0' <br>
ping -c3 172.25.250.11 <br>
ping -c3 172.254.250.25 <br>
reboot <br>
