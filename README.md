# WindowsGSM.ASKA
🧩 Plugin for WindowsGSM to run an ASKA Dedicated Server!!

### WindowsGSM Install

1. Download WindowsGSM from https://windowsgsm.com/
2. Create a Folder where you want the progame installed.
3. Extract the downloaded file.
4. Move the WindowsGSM.exe to the folder created in Step 2.
5. Run the WindowsGSM.exe

### Plugin Install

1. Download [latest](https://github.com/tadavispmd040507/WindowsGSM.ASKA/releases/download/v1.0/WindowsGSM.ASKA.zip) release.
2. You have 2 options...
    - Extract the file file downloaded and move the **ASKA.cs** folder to **WindowsGSM/plugins** then press the **Puzzle** icon in the bottom left corner and press the **[RELOAD PLUGINS]** or **Restart** WindowsGSM.
    - Press the **Puzzle** icon in the bottom left corner then press the **[IMPORT PLUGIN]** and select the downloaded zip file.

### Official Documentation

📋 This can be found in the install directory of the server **WindowsGSM/servers/{Server ID}/serverfiles/ASKA Dedicated Server Setup - EN.pdf**

### Steam Store Page

🎮 https://store.steampowered.com/app/1898300/ASKA/

### Dedicated Server SteamDB Page

🖥️ https://steamdb.info/app/3246670/info/

### Port Forwarding (REQUIRED)

- If you don't know how to do this then Google is your friend.
- 7777 TCP/UDP - Steam Game Port (Unless Port Was Changed)
- 27015 TCP/UDP - Steam Query Port (Unless Port Was Changed)

### Backup

- Recommended to use External Program or Script via Task Scheduler (WindowsGSM will backup the entire server minus the saves since they aren't located in the server install location)
- Recommended Files
    - WindowsGSM/servers/{Server ID}/serverfiles/server properties.txt
    - C:/Users/{USER}/AppData/LocalLow/Sand Sailor Studio/Aska/data/server/savegame_{Save Game ID In "server properties.txt"}
    - WindowsGSM/servers/{SERVER ID}/configs

### Parameters/Config Guide

Currently there are none. You need to edit the **server properties.exe** directly, it can be found at **WindowsGSM/servers/{Server ID}/serverfiles/** The settings seen below are default options, descriptions can be found in the **"server properties.txt"**
- save id = {Will Auto Fill On First Launch}
- display name = {Required}
- server name = {Required}
- seed = {Not Required}
- password = {Not Required}
- steam game port = {Required}
- steam query port = {Required}
- authentication token = {Required}
- region = default {Options: default, asia, japan, europe, south america, south korea, usa east, usa west, australia, canada east, hong kong, india, turkey, united arab emirates, usa south central}
- keep server world alive = false {Options: true or false}
- autosave style = every morning {Options: every morning, disabled, every 5 minutes, every 10 minutes, every 15 minutes, every 20 minutes}
- mode = normal {Options: normal or custom}
    - ALL OPTIONS BELOW THIS WILL ONLY WORK WITH **CUSTOM** MODE SELECTED
- terrain aspect = normal {Options: smooth, normal, rocky}
- terrain height = normal {Options: flat, normal, varied}
- starting season = spring {Options: spring, summer, autumn, winter}
- year length = normal {Options: minimum, reduced, default, extended, maximum}
- precipitation = 3 {Options: 0 (sunny) through 6 (soggy)}
- day length = normal {Options: minimum, reduced, default, extended, maximum}
- structure decay = medium {Options: off, easy, normal, hard}
- invasion dificulty = normal {Options: off, easy, normal, hard}
- monster density = medium {Options: low, medium, high}
- monster population = medium {Options: low, medium, high}
- wulfar population = medium {Options: low, medium, high}
- herbivore population = medium {Options: low, medium, high}
- bear population = medium {Options: low, medium, high}

### Key Notes

This game is in **Early Access**, WindowsGSM and this plugin is not responsible for any lost data that could occure to your server.

### WindowsGSM Support
[WindowsGSM](https://windowsgsm.com/discord)

### Donations

[Paypal](https://paypal.me/GDavis6899)

### Thanks

Thanks to Raziel7893 for the Smallworld Plugin which I used for guidance.