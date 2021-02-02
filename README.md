# hg8310m-vfpt
https://pt.aliexpress.com/item/32976208543.html?spm=a2g0s.9042311.0.0.1997b90aiszjhp

telecomadmin/admintelecom

##network settings computer:
 - ip: 192.168.100.2
 - subnetmask: 255.255.255.0
 - router: 192.168.100.1

Setting as CLASS B+ product (came class C+)

##terminal:
> telnet 192.168.100.1
username: root
password: admin

`su
set optmode mode 196
`

##Authentication:
passcode: ASCII 
Number: Do one provided bt vdf (the hard part)
SN: Copied from Smart router

Testing on the mac:

- Network preferences
- In the toolbar below all of your network interfaces, click the gear wheel to access a dropdown menu
- Manage Virtual Interfaces...
- From that dropdown menu, select New VLAN...
- Enter an appropriate name for your new VLAN, e.g. DMZ
- Enter the desired tag: 100
- activate DHCP on this new connection
