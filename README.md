## Raspberry Pi 5 - PIVPN Setup 

1.1 First, create a port forwarding rule on your firewall/router for port 51820 UDP.
1.2 Once Pi-hole is successfully installed and configured,see the following [Pi5 Installation and Pihole](https://github.com/ManolisCraftedTech/RaspberryDNS) visit https://www.pivpn.io/.
2. Run the following command to install PiVPN

<img width="495" alt="image" src="https://github.com/user-attachments/assets/a2ad238e-5915-42a5-a7f5-a0bf133bad3b" />


3. Follow the on-screen instructions.

<img width="536" alt="3" src="https://github.com/user-attachments/assets/9cb564e3-56ea-422f-8e76-886af72ca1fb" />
<img width="523" alt="4" src="https://github.com/user-attachments/assets/8001d18d-f76b-40eb-aff8-9b2153ba8b67" />
<img width="515" alt="5" src="https://github.com/user-attachments/assets/f2adee99-565e-4ed7-97cc-90656bd061dd" />

4. Enter the static IP address of your Raspberry Pi.

<img width="369" alt="6" src="https://github.com/user-attachments/assets/4718c1a8-92d2-4e8f-afde-0a8733825b42" />

5. Choose WireGuard for better performance, especially if the main use case is for mobile devices.(Improved battery performance compared to OpenVPN)

<img width="416" alt="8" src="https://github.com/user-attachments/assets/a5a72260-43d9-4979-995e-1b301c2e4fea" />


6.  Use port 51820 and press Enter.

  <img width="534" alt="9" src="https://github.com/user-attachments/assets/01108dfd-7a47-4074-aa88-783cd598ad11" />

7. You will now have two options:

- Use your public IP
- Use a public DNS entry

<img width="503" alt="4444" src="https://github.com/user-attachments/assets/4ab6f36a-a633-43de-ad6e-dbe84190fbb1" />


8. Once everything is set up, reboot your Raspberry Pi.

9. Now, it's time to create users for PiVPN using the command:
pivpn -a
To generate a QR code for easy mobile configuration, use the command:
pivpn -qr


<img width="445" alt="image" src="https://github.com/user-attachments/assets/342d0e44-5751-47c9-b443-d8865575dbd3" />

This QR code can then be scanned from your mobile device for quick setup.



10. Now, download WireGuard from the Play Store and scan the QR code that was previously created for the user. This will complete the setup.



<img width="186" alt="666" src="https://github.com/user-attachments/assets/184dfb7f-8f6e-49ea-8774-6971bfe091e5" />


<img width="203" alt="2222" src="https://github.com/user-attachments/assets/4584108b-3821-4ea1-883f-67a3b7481575" />


<img width="200" alt="3333" src="https://github.com/user-attachments/assets/d5e878af-9f94-42b2-a9be-d8813ee4520f" />


11. Once connected to PiVPN from your mobile device, you can now perform automation tasks from home and enjoy access and anonymity on public networks.

As can be seen below , acces to personal network router is available with 5G LTE mobile phone usage.Because we have successfuly setup PIvpn.

<img width="194" alt="111" src="https://github.com/user-attachments/assets/a6bd3db1-22c7-452d-9c76-4259dba8b584" />


12. Some additional useful apps from the Play Store include:

- ConnectBot
- Pi-hole Connect
- PingTools





