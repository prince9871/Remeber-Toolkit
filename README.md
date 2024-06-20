# Remember-Toolkit

## Useful for changing the default React port by making changes in your `package.json` file.

```json
"scripts": {
  "start": "set PORT=5001 && react-scripts start",
  "build": "react-scripts build",
  "test": "react-scripts test",
  "eject": "react-scripts eject"
}
```
## Check Outdated Packages in Node.js

To check for outdated packages within your Node.js project, you can utilize the following commands:

### Check for Outdated Packages
Run the command:
```bash
npm outdated
```

### Update a Specific Package:
```bash
npm update <package-name>
```
## React Node Solutions

### Resolve CORS Issues
Package Installations & Configs:
```bash
npm i cors
```

```bash
const cors=require('cors')
app.use(cors())
```



## VS Code Boosters

### Change All Occurrences in VS Code

**Shortcuts:** `Ctrl+F2`

This shortcut allows you to select a word in your code and then use `Ctrl+F2` to highlight and simultaneously edit all occurrences of that word in your file. It's a handy way to make quick, simultaneous changes throughout your code.

### Copy Line Above/Below

**Shortcuts:** `ALT+SHIFT+UP/DOWN`

Use `ALT+SHIFT+UP` or `ALT+SHIFT+DOWN` to duplicate the current line in the editor and place the copy either above or below the current line. This feature is helpful for quickly duplicating lines of code without the need for manual copy-pasting.




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
