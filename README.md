# Legend Eternal (Shanda Games) - Official Public HC Source

[Latest Build](https://github.com/damianday/Conquer/tree/main/Release)

[Discord](https://discord.gg/R8BgxJ7H)
  
---

## How to start

### Client & Launcher Configuration

First, a compatible client will need to be downloaded, for example:
* LATEST  [Client](https://mirfiles.com/resources/mir2/users/Jev/Mir%203DEMU/Clients/HC%20-%201.0.4.24.rar)

* If you wish to use the Chinese Pak Files you can download these [here](https://mirfiles.com/resources/mir2/users/Jev/Mir%203DEMU/Clients/HC%20-%201.0.4.24%20CN%20Paks.rar)

Latest version still compatible with this files **[v1.72 - 192912)]**

Once downloaded, you will need to copy the compiled binaries of the launcher to the root of the folder.

In launcher there is a configuration file called "!Settings.txt". In this file we must put our WAN IP and the AccountServer port (by default 7000), eg:

If it is locally: `127.0.0.1:`
If it is WAN: `<public_ip>`
  
---

### Account Server Configuration

We will have to create a file in the root of the account server called "!ServerInfo" in which we will include a list of the GS that we will have raised, by default we will only have one, so we will have something like the following:

<details>
  <summary>If it is locally:</summary>

[
  {
  
    "ServerName": "LOMCN",
  
    "TicketAddressIP": "127.0.0.1",
    
    "TicketAddressPort": 6678,
    
    "PublicAddressIP": "127.0.0.1",
    
    "PublicAddressPort": 8701
  }
]

  </details>
  
  <details>
  <summary>If it is WAN:</summary>

[
  {
    
    "ServerName": "LOMCN",
    
    "TicketAddressIP": "127.0.0.1",
    
    "TicketAddressPort": 6678,
    
    "PublicAddressIP": "public_ip",
    
    "PublicAddressPort": 8701
  }
]

  </details>
  
---

### Game Server Configuration

We must copy a valid system database in the "Database/System" folder.

It does not require changing the default config.

To publish on the internet, you must open ports 7000 and 8701 on your router

### Network Communication Diagram

![mir-network](https://github.com/user-attachments/assets/044113df-f8c5-402e-9271-c36db0f28cfd)
  
---

# Useful Links:

[Help](https://www.lomcn.net/forum/forums/mir-3d-bug-reports.813/) //
[Tutorials](https://www.lomcn.net/forum/forums/mir-3d-tutorials.852/)

---

# Special Thanks

* [DontReallyMind](https://www.lomcn.net/forum/members/dontreallymind.4351/)
* [CraZyEriK](https://www.lomcn.net/forum/members/crazyerik.9944/)
* [Wincha](https://github.com/Wincha)
* [Lilcooldoode](https://www.lomcn.net/forum/members/lilcooldoode.940/)
* [Far](https://www.lomcn.net/forum/members/far.1046/)
* [Armifer (ElAmO)](https://www.lomcn.net/forum/members/elamo.10165/)
* [Damian (CodePwr)](https://www.lomcn.net/forum/members/damian.1126/)
* [Jev](https://www.lomcn.net/forum/members/jev.29880/)
* [mir2pion](https://www.lomcn.net/forum/members/mir2pion.19657/)

---

# Other Projects:

- <img src="https://github.com/JevLOMCN/mir4/blob/main/Tools/icons/mir1.png" alt="Mir1" width="20"/> [Mir 1](https://github.com/JevLOMCN/mir1/) | [Database](https://github.com/Suprcode/Carbon.Database) - Remake of ActozSoft's 1997 _The Legend Of Mir 1_
- <img src="https://github.com/JevLOMCN/mir4/blob/main/Tools/icons/mir2.png" alt="Mir2" width="20"/> [Mir 2](https://github.com/Suprcode/Crystal) | [Database](https://github.com/Suprcode/Crystal.Database) | [Map Editor](https://github.com/Suprcode/Crystal.MapEditor) - Remake of ActozSoft/Wemade Entertainment's 1999 _The Legend Of Mir 2_
- <img src="https://github.com/JevLOMCN/mir4/blob/main/Tools/icons/mir3.png" alt="Mir3" width="20"/> [Mir 3](https://github.com/Suprcode/Zircon) - Remake of Wemade Entertainment's 2003 _The Legend Of Mir 3_
- <img src="https://github.com/JevLOMCN/mir4/blob/main/Tools/icons/woool.png" alt="WoOOL" width="20"/> [WoOOL](https://www.lomcn.net/forum/forums/woool-development-project-onyx.857/) - Remake of Shanda Games' (now Shengqu Games) 2003 _The World Of Legend_
- <img src="https://github.com/JevLOMCN/mir4/blob/main/Tools/icons/mir3d.png" alt="Mir3D" width="20"/> [Mir 3D (Moon Spirit)](https://github.com/mir-ethernity/mir-eternal) | [Mir 3D (Holy Cow)](https://github.com/JevLOMCN/Legend-Eternal-Mir3D) - Remake of Shanda Games' (now Shengqu Games) 2016 _Legend Eternal_
- <img src="https://github.com/JevLOMCN/mir4/blob/main/Tools/icons/mir4.png" alt="Mir4" width="20"/> [Mir 4](https://github.com/JevLOMCN/mir4) - Remake of Wemade Entertainment's 2021 _The Legend Of Mir 4_
