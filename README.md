# old-stars
Brawl Stars v26.184 server emulator written in Python.
<h1 align="center">Welcome to Old-Brawl 👋</h1>

Open source Brawl Stars server emulator for version 26 of the game! Thanks PhoenixFire!

![com brawlstars v26](https://user-images.githubusercontent.com/85035681/143640243-740eda83-d03d-4dd4-82c7-44d8926201c0.png)

## What's working ?
- Battles
  - Trophies in offline battles
- Home
  - Unlimited resources
  - Brawlers from boxes (if all brawlers don't with all star power's and gadget's)
  - All skins unlocked
  - Gadgets and Star Powers
- Shop
  - Special offers (not all time)
  - Boxes (if all brawlers don't with all star power's and gadget's)
  - Gold and other resources 
- Club
  - Join
  - Leave
  - Chat
  - Update settings
  - Bot commands

...and much more!


## Prerequisites

- python 3.7
- tinydb



## Run Server
- On Windows:
    - Download Python 3.7 or newer version from official page.
    - Download the server and extract it.
    - In a terminal type: ```pip install tinydb```
    - Execute "main.py" file
- On Linux:
    - Open Terminal and install Python by executing following command:
    ```sudo apt-get update && sudo apt-get install python3 python3-pip```
    - Download the server and extract it.
    - In a terminal type: ```pip install tinydb```
    - Execute "main.py" file
- On Android:
    - Download and install PyDroid app from Google Play.
    - Open PyDroid and wait until Python installs.
    - Download the server and extract it.
    - In PyDroid go in the "pip" section, type ```tinydb```, then click install.
    - In PyDroid open and execute "main.py" file


## Configure client
To connect to your server, you need a custom client. Here the only solution is to use a [pre-made client](https://mega.nz/file/vSIDFKaT#pDdGFkevXwp_3LP1wW1wtj23Gj2aADZwzfXAAI8JEs8). Just replace the IP in the frida-gadget config with yours (```/lib/armeabi-v7a/libgg.config.so```) ```{"interaction":{"interaction":{"type":"script","path":"libscript.so","on_change":"reload","parameters":{"redirectHost":"YOUR_IP","relocate":true}}}```

## Configure client on pc
Open "main.py" and find "server = Server('0.0.0.0', 9339)", change "0.0.0.0" to your ip. Start and play!

## Authors

👤 **PhoenixFire** (main developer)

* Github: [@PhoenixFire6879](https://github.com/PhoenixFire6879)
* Discord: PhoenixFire#6879

👤 **NyanAlex**
* Github: [@NyanAlex](https://github.com/NyanAlex)
* Discord: Тюлень[NyanAlexYT]#0712

👤 **Crazor**

* Github: [@CrazorCLB](https://github.com/CrazorCLB)
* Discord: Crazor#7395

Special thanks to:
- [VitalikObject](https://github.com/VitalikObject)
- [Rostik](https://github.com/RostikDevv) and [Vorono4ka](https://github.com/Vorono4ka) for their [scdocs](https://github.com/RostikDevv/scdocs)


## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/NyanAlex/old-stars/issues).

## Show your support

Give a ⭐️ if this project helped you!
