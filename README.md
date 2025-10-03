# Enable Discord Developer Tools (Dev Mode)

⚠️ **Disclaimer:**  
This method is **unofficial** and involves modifying Discord’s configuration files.  
Use at your own risk. Enabling developer tools can expose you to security risks if you paste unknown code into the console.  

---

## Steps

### 1. Enable Discord Developer Mode
1. Open **Discord**.
2. Go to **Settings → Advanced → Developer Mode** and turn it on.

---

### 2. Edit Discord Settings File
1. Close Discord completely (make sure it’s not running in the system tray).
2. Navigate to the following folder:

C:\Users\YourUser\AppData\Roaming\discord

Copy code

3. Locate the file **`settings.json`**.
4. Open it with a text editor (e.g., Notepad).
5. Add the following line inside the JSON object:

```json
"DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true,
```json
Save the file and close the editor.

3. Relaunch Discord
Start Discord again.

Press CTRL + SHIFT + I to open the Developer Tools.

4. Allow Console Pasting
In the Console tab, type:

Copy code
allow pasting
Press Enter.

5. Paste Your Script
Now, copy the contents of the script file you have.

Paste it into the console and press Enter.

