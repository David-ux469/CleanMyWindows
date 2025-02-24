# 🖥️ Reset Windows Script

A **PowerShell** script to clean Windows without formatting. It removes unnecessary programs, cleans temporary files, clears cache, and resets system settings.

## 🚀 Features
- 🔥 **Removes user-installed programs** (except essential ones)
- 🗑️ **Cleans temporary files and cache**
- 🔄 **Resets network and firewall settings**
- 📝 **Cleans unnecessary registry entries**
- 👥 **Deletes unnecessary user accounts**
- 🔄 **Automatically restarts Windows after cleanup**

## 📌 How to Use the Script
1. **Download the script** and save it as `reset-windows.ps1`
2. **Run PowerShell as Administrator**
3. **Allow script execution** (if necessary) with:
   ```powershell
   Set-ExecutionPolicy Unrestricted -Force
   ```
4. **Run the script with:**
   ```powershell
   .\reset-windows.ps1
   ```
5. **Windows will automatically restart after the cleanup**

## ⚠️ Warning
This script removes configurations, temporary files, and some programs. **Use it at your own risk.**

## 📜 License
This project is under the **MIT** license. Feel free to use and modify it! 🎯
