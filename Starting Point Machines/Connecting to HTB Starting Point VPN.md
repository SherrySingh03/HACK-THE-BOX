In order to access any server on HackTheBox, first, we need to connect to HackTheBox VPN. Since, in this module, we're going to be convering Starting Point Machines, hence, we've to connect to Starting Point VPN.

## Procedure:

- Click on the icon that says **CONNECT TO HTB** in the top right hand corner of your screen.
    

      ![0f79b5fd6d826743a0d037c4e08dd886.png](../_resources/0f79b5fd6d826743a0d037c4e08dd886.png)

- Now, since we'll be dealing with Starting Point Machines, we'll connect to the **Starting Point VPN**.
    

      ![8e902c7c0a3df9186f76185947d247da.png](../_resources/8e902c7c0a3df9186f76185947d247da.png)

- Click on **OpenVPN** or **Pwnbox**, (based on personal preference). I'll be connecting to OpenVPN. Click on OpenVPN. Then set it up, choose the access points, after that, click on **Download VPN**.
    ![aa5e9508e9bcbcad972136726bad7b04.png](../_resources/aa5e9508e9bcbcad972136726bad7b04.png)
    

- After downloading the **.ovpn** file, fire up a terminal, and Use the `apt install openvpn` to install the OpenVPN module.
    

- After installing OpenVPN, use the `cd Downloads` command to access the Downloads folder. Then, use the `openvpn starting_point_{Your_Username_on_HTB}.ovpn` to start connecting to HTB VPN.
    

      ![3622a28efb9798566b2935b0b40be262.png](../_resources/3622a28efb9798566b2935b0b40be262.png)

- After executing these commands successfully, you'll see something like this on HackTheBox.
    

     ![b476c3805fcd9cf300f0e36fb07b675d.png](../_resources/b476c3805fcd9cf300f0e36fb07b675d.png)

- And with this, you've successfully made the connection with HackTheBox VPN.