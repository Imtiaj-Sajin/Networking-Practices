<b>Subnetting</b>
Router is connected to 4 switces. so subnetting is needed.
first usable ip is needed to be assigned in one port of router.

first switch:
usable range: 192.168.1.1 to 192.168.1.62
subnet mask:255.255.255.192

<h2>Router config codes:</h2>
1. en :enables
2. conf f /   :config
3. int fa 0/0
4. ip adddress 192.168.1.1 255.255.255.192
5. no shut      //for start
6. exit 

<h2>Simulation Picture:</h2>

![image](https://github.com/user-attachments/assets/1c2946bb-9c63-4fc3-a62c-18861b225f60)

