# On Prem to Huawei Cloud Connection via VPN Tunneling
This is a documentation to guide how to do on-premise connection in cloud via VPN Tunneling and IPSEC.

## Pre-quisites
1. On-premise site would need to have a gateway to connect to the cloud
2. You must have a cloud account and buy a VPN Gateway
3. Write down your On-premise Gateway/Firewall Public IP
4. Make a Virtual Private Cloud , Note down the subnets

## Step 1 : Creating a VPN Gateway
In the huawei cloud console you need to search for the VPN service. Here you will need to make and purchase the VPN Gateway
<img width="1261" height="710" alt="image" src="https://github.com/user-attachments/assets/2cfd57ba-5f71-4425-a1a1-e580efde22d4" />

You need to fill the configuration according to your VPC specification. 
On the bottom, you will also find many configuration, such as active-active and active-standby. You can pick either of those , for but you can choose the active-active if you want more HA. Huawei cloud will generate a random IP for you after purchasing this gateway.

## Step 2 : Creating Customers Gateway



