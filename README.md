# FreeDrawSimulator
This is an unofficial application FreeDrawSimulator. Feel free to report bugs and sugestions.

![image](https://github.com/jnalepka/FreeDrawSimulator/assets/70645322/823317c0-ad10-4d93-9632-51b28e063158)


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

# Known issues
- PrintText shows text over texture.

# Donate
If you find this project helpful, consider supporting its development by making a donation through PayPal.

<a href="https://paypal.me/plejader">
  <img src="https://github.com/andreostrovsky/donate-with-paypal/blob/master/PNG/blue.png" alt="Donate with PayPal" width="250">
</a>




