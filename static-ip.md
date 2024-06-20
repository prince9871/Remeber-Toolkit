# Set Static IP for Localhost LAN Connection

Follow these steps to set a static IP for your localhost LAN connection:

## Steps

1. **Open Network Settings:**
   - **Windows:** `Control Panel -> Network and Sharing Center -> Change adapter settings`
   - **Mac:** `System Preferences -> Network`

2. **Select Adapter:**
   - Right-click on your LAN connection and select `Properties`.

3. **Select IPv4:**
   - Select `Internet Protocol Version 4 (TCP/IPv4)` and click `Properties`.

4. **Set Manual IP:**
   - Select `Use the following IP address` and enter the following details:
     - **IP address:** `192.168.1.100`
     - **Subnet mask:** `255.255.255.0`
     - **Default gateway:** `192.168.1.1`

5. **Enter DNS Server:**
   - Select `Use the following DNS server addresses` and enter:
     - **Preferred DNS server:** `8.8.8.8`
     - **Alternate DNS server:** `8.8.4.4`

6. **Save Settings:**
   - Click `OK`, then `Close`.

7. **Restart Network:**
   - Disable and enable your network adapter or restart your system.

Your static IP is now set for your localhost LAN connection!
