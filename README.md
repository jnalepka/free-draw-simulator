# FreeDrawSimulator
This is an unofficial application FreeDrawSimulator. Feel free to report bugs and sugestions.

![image](https://github.com/jnalepka/FreeDrawSimulator/assets/70645322/13d7fde9-b687-4983-bb7f-02516d20e4ac)

If you like what I do, buy me a `coffee`!

[![](https://img.shields.io/static/v1?label=Donate&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://tipply.pl/@jnalepka)


# Install

Download: https://github.com/jnalepka/FreeDrawSimulator/releases

### Windows
1. Extract the `.zip` file.
2. Run `FreeDrawSimulator.exe`.

#### How to add shortcut:
1. Right-click and select `Create shortcut` to add a shortcut to the program.
2. Open `C:\ProgramData\Microsoft\Windows\Start Menu\Programs` and paste the program shortcut there to display it in the Windows menu.

### Linux
1. Extract the `.zip` file.
2. Right click on `Linux-FreeDrawSimulator.x86_64` file and select `Properties`.
3. Go to `Permissions` and select "Allow executing file as program".
4. Run `Linux-FreeDrawSimulator.x86_64`.

#### How to add shortcut:
1. Open terminal and type `sudo nano /usr/share/applications/FreeDrawSimulator.desktop`
2. Paste the following content:
  ```
#!/usr/bin/env xdg-open
[Desktop Entry]
Version=1.0
Type=Application
Terminal=false
Exec=/home/ubuntu/Downloads/Linux-FreeDrawSimulator-v1.4/Linux-FreeDrawSimulator.x86_64
Name=FreeDrawSimulator
Comment=FreeDrawSimulator v1.4
Icon=/home/ubuntu/Downloads/Linux-FreeDrawSimulator-v1.4/Linux-FreeDrawSimulator/Resources/UnityPlayer.png
```
Replace yourapp with your application and save by pressing Ctrl+O, Enter and Ctrl+X.

3. Make this file executable: `sudo chmod +x /usr/share/applications/FreeDrawSimulator.desktop`
4. Log out and log in.

# User-manual
### Basic functions of the program:
1. Copy ready code from the Object Manager configurator to simulate the view on the SmartPanel screen.
2. Create ready code and then paste it into the Object Manager configurator.

![demo](https://github.com/jnalepka/FreeDrawSimulator/assets/70645322/d5a3136b-43d1-4e06-89c6-dc49fe9c9f86)

### How to edit element inside the code
1. Cut the line of code using Ctrl+X.
2. Open the appropriate add window, for example, `+PrintText`.
3. Paste the code using Ctrl+V and edit it as needed.

### How to use custom icons
1. Open `.../Icons` and paste your own icons.

### Export all workspaces
1. Click the "Save/Load" button.
2. Save your workspaces, then click the "Export" button.
3. The file will be saved in ".../Win64-FreeDrawSimulator\FreeDrawSimulator_Data\FreeDrawSimulator_ExportedData"
> NOTE: The file with the same name will be overwritten!

### Import your workspaces
1. Click the "Save/Load" button.
2. Click the "Import" button, check the file name, then click the "Upload" button.
> NOTE: All your local workspaces will be overwritten!

# Known issues
- PrintText shows text over texture.




