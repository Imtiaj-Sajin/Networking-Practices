<b>Subnetting</b>
Router is connected to 4 switces. so subnetting is needed.
first usable ip is needed to be assigned in one port of router.

first switch:
usable range: 192.168.1.1 to 192.168.1.62
subnet mask:255.255.255.192

<h2>Router config technique:</h2>
1. en :enables
2. conf f /   :config
3. int fa 0/0
4. ip adddress 192.168.1.1 255.255.255.192
5. no shut      //for start
6. exit 

<h2>Simulation Picture:</h2>

![image](https://github.com/user-attachments/assets/1c2946bb-9c63-4fc3-a62c-18861b225f60)


<h2>example code for configuring first router:</h2>
<bash>
Router> en
Router# conf t
Enter configuration commands, one per line.  End with CNTL/Z.

Router(config)# int fa 0/0
Router(config-if)# ip address 192.168.1.1 255.255.255.192
Router(config-if)# no shut
%LINK-5-CHANGED: Interface FastEthernet0/0, changed state to up
%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/0, changed state to up

Router(config-if)# exit
%SYS-5-CONFIG_I: Configured from console by console



Router con0 is now available
</codebase></bash>




