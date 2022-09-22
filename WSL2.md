# WSL-2 (Windows Subsystem for Linux 2)

1. Open PowerShell (Run as Administrator)
    - Command: `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux`
2. Note: Restart
3. Open PowerShell (Run as Administrator)
    - Command: `dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart`
    - Command: `dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart`
4. Note: Restart
5. Download Linux Kernel: https://aka.ms/wsl2kernel
    - Install the .exe file
6. Open PowerShell (Run as Administrator)
    - Command: `wsl --set-default-version 2`
7. Open Microsoft Store
    - Search for **“Kali Linux”**
    - Install it by clicking **“Get”** button
8. Run Kali Linux
    - Click **“Windows”** button
    - Search for Kali Linux —> Run it
9. Now it ask for Username and Password
    - Enter new username: <username>
    - New Password: <Enter-Password>
    - Re-Type New Password: <Enter-Password>
10. Done.

Kali Linux installation on windows 10 is complete. Now you can use it in command-Line Interface (CLI)
