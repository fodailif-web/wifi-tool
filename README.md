# **WiFi Password Generator - Chrome Extension**

A Google Chrome extension that generates WiFi passwords based on a custom encryption algorithm.

## **📁 Project Structure**
```
wifi-password-generator/
├── manifest.json
├── background.js
├── wifi-popup.html
├── wifi-popup.css
├── wifi-popup.js
└── icon.png
```

## **🚀 Installation Guide**

### **Method 1: Direct Installation in Chrome**
1. **Download all files** into one folder
2. **Open Chrome browser** and navigate to:
   ```
   chrome://extensions/
   ```
3. **Enable "Developer Mode"** in the top right corner
4. **Click "Load unpacked"**
5. **Select the folder** containing the extension files
6. **Installation complete!** 🎉

### **Method 2: From Compressed Archive**
1. **Compress all files** into a ZIP folder
2. **Change extension** from `.zip` to `.crx` (optional)
3. **Drag the file** to `chrome://extensions/` page

## **🎮 How to Use**

### **1. Open the Extension**
- Click on the extension icon in Chrome's toolbar
- A small popup window will open

### **2. Enter WiFi Network Name**
- Enter the WiFi network name in this format:
  ```
  fh_xxxxxx
  ```
  Where `xxxxxx` are 6 characters/digits

### **3. Correct Examples:**
```
fh_2e9908
fh_a67d89
fh_a3cbc1
fh_167fac
```

### **4. Generate Password**
- Click the **"Generate Password"** button
- The password will appear in this format:
  ```
  wlan + [encrypted part]
  ```

### **5. Copy Password**
- Click the **"Copy to Clipboard"** button to copy the password
- Use it to connect to the WiFi network

## **🔐 How It Works**

The extension applies a character substitution algorithm to the part after `_` in the network name and prepends `wlan` to the result.

### **Example:**
```
Input:      fh_2e9908
Processing: Encrypts "2e9908" using custom algorithm
Output:     wland166f7
```

## **🎯 Features**

✅ **Simple and clean interface**  
✅ **Instant password generation**  
✅ **One-click copy to clipboard**  
✅ **Built-in examples for guidance**  
✅ **Modern and attractive design**  
✅ **No special permissions required**  

## **🛠 Troubleshooting**

| Issue | Solution |
|-------|----------|
| Icon not appearing | Reload the `chrome://extensions/` page |
| Popup not opening | Verify correct installation |
| Incorrect password | Ensure format: `fh_xxxxxx` (6 chars after _) |
| Copy button not working | Check clipboard permissions |

## **📝 Important Notes**

1. **Required Format:** Network name must start with `fh_`
2. **Fixed Length:** Part after `_` must be exactly 6 characters
3. **Allowed Characters:** a-f and 0-9 only
4. **Output Format:** Always starts with `wlan`

## **🔒 Privacy & Security**

- The extension **does not collect** any personal data
- **No information is sent** to external servers
- **Works locally** on your device only
- **Open code** that anyone can inspect

## **📞 Support & Issues**

If you encounter any problems:
1. Verify the network name format
2. Try the built-in examples in the interface
3. Reload the extension from the extensions page

---

**Developed by: fateh_dz_MRX**  
*A useful tool for quickly generating WiFi passwords!* 🚀
