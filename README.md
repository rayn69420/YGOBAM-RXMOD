# YGOBAM-RXMOD
Resurrection of the Yu-Gi-Oh! BAM mobile game.
---


If you have any question or suggestion, feel free to join the project's discord server: https://discord.gg/KPQQahS884

Thank you **youtube.com/@Odd-Eyes19** for sharing your backup of the game!

---

REQUIREMENTS:
- Android 5.1 with root access.
  - Download MEmu from: https://www.memuplay.com/
  - Install.
  - Open the Multi-MEmu.
  - Press the "New" button at the bottom right.
  - Select "Android 5.1".
  - Open the instance when its ready.
  - After startup, press the hamburger icon on the top of the window and select "Settings".
  - In the Settings menu, select the "Engine" tab at the left side.
  - Switch the "Root mode" to "ON".
  - Restart instance.
- Download the latest release.
---
INSTALLATION:
- Install the apk in the package root: "titanium-backup-root-8-4-0-2.apk"
  - How to install? You can just drag'n'drop it to the MEmu desktop.
- MEmu creates a shared directory with your Android instance, open that directory:
  - "C:\Users\<User>\Downloads\MEmu Download\"
- Copy "ygobam-data" directory there.
- Open the "File Manager" app in the MEmu instance.
- Go to "0/Download", there is the directory you just copied.
- Open it, select the 3 files in it.
  - App should write "3 files selected." at the bottom.
- Now go to "0/TitaniumBackup".
- Press the 3 dots button up-right.
- Press "Copy selection here".
- After it finished, you should have the 3 files in the "0/TitaniumBackup" directory.
- Open the "Titanium Backup" app.
- Navigate to the "Backup/Restore" tab.
- Select "Yu-Gi-Oh! 1.11.1". (Its at the bottom of the list)
- Press the button with the blue "Restore" text.
- Choose the "App+Data" option.
- Press "Install".
- Press "Done".
  - Don't press "Open", Titanium have to install the data after the app install, the game won't work without it.
- When Titanium finished with the restore. You can open the game from the desktop,
- Enjoy!

---
TROUBLESHOOTING:
- Q: Why is my screen black after I start the game?
  - A: If the **Render Mode** in MEmu's System settings is on DirectX, switch it to **OpenGL**.
