# Windows Repair Utility

<!---![Windows Repair Screenshot](screenshot-placeholder.png)-->

A Windows Forms application designed to perform various system cleanup and repair tasks with administrator privileges.

## Features

- **System Cleanup Tasks**:
  - 🗑️ **Temp Files**: Cleans temporary files from `%TEMP%` and `Windows\Temp` directories
  - 📦 **Software Distribution**: Clears Windows Update cache and resets related services
  - 🗑️ **Recycle Bin**: Force clears all Recycle Bin contents
  - ⏳ **Restore Points**: Deletes oldest system restore points
  - 🌐 **Browser Cache**: Clears cache for Chrome, Edge, Firefox, and thumbnail cache

- **System Repair Tasks**:
  - 📶 **Network Reset**: Resets network adapters, DNS, and Winsock
    - <details>
      <summary>What does "Network Reset" do?</summary>

        - Renews your IP address
        - Clears DNS cache
        - Resets network adapters to default
  - 🔧 **System Repair**: Runs comprehensive repair tools:
    - `sfc /scannow`
    - DISM health checks and repairs
    - Event log clearing
    - Component cleanup

- **Additional Options**:
  - ⏻ **Automatic Restart**: Option to immediately restart system after cleanup

## Installation

### Prerequisites
- .NET Framework 4.0 or newer
- Windows 7/8/10/11 (64-bit recommended)
- Administrator privileges

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/windows-repair-utility.git

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z5TRISN)
