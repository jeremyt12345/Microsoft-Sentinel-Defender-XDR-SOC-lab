# Microsoft-Sentinel-Defender-XDR-SOC-lab
A SOC lab built on Sentinel &amp; Defender where I can learn some more incident response skills in a live environment. 


Creating a Resource Group
<img width="1557" height="646" alt="image" src="https://github.com/user-attachments/assets/2192e3fc-1ac9-4c7d-91ec-2685ac1b2f69" />


Next we will create a Virtual Network

<img width="1589" height="848" alt="image" src="https://github.com/user-attachments/assets/fa3f871a-1bd6-42cb-b282-3772f586ff67" />


Adding my address space

<img width="1207" height="828" alt="image" src="https://github.com/user-attachments/assets/7c4d7bb2-1079-4e30-b1a8-de79f0ed2581" />


Adding a subnet for the clients and servers

<img width="1899" height="846" alt="image" src="https://github.com/user-attachments/assets/99aec539-4f21-4d65-9773-c572eba942e2" />

Lastly building a subnet for the Azure Bastion

<img width="1908" height="901" alt="image" src="https://github.com/user-attachments/assets/aaf70a32-d6a8-4d82-9dda-f5004798362c" />


Now we want to create a Network Security Group

<img width="970" height="105" alt="image" src="https://github.com/user-attachments/assets/faaff200-9dd8-4cd5-b403-94287e78dfda" />


<img width="1865" height="859" alt="image" src="https://github.com/user-attachments/assets/16b9e28c-93b3-4a3f-8f2d-fa3d86f17aa6" />


Now within that NSG Im associating the subnets to it.

<img width="1890" height="963" alt="image" src="https://github.com/user-attachments/assets/9cc45d43-cf58-4c26-92a3-9b8fd74e0514" />

Next up is Bastions
<img width="1709" height="883" alt="image" src="https://github.com/user-attachments/assets/8a2a2024-3605-4db8-a33c-e06a5c6a74b2" />


Last part for the day is to setup my Log Analytics Workspace

<img width="1911" height="925" alt="image" src="https://github.com/user-attachments/assets/6693dcfa-9676-4d28-8dda-481377a68bee" />


Time to add Microsoft Sentinel

<img width="1708" height="896" alt="image" src="https://github.com/user-attachments/assets/9df1abdd-875a-4d8c-a3fe-092a414689b1" />

After adding Sentinel I then have to add Microsoft Defender XDR

<img width="1912" height="948" alt="image" src="https://github.com/user-attachments/assets/e9082159-6cdb-45a1-a628-099e71e3de49" />

