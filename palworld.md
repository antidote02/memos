### 幻兽帕鲁专用服务器
#### 服务端（Windows）
* 下载`SteamCMD` [[developer.valvesoftware.com]](https://developer.valvesoftware.com/wiki/SteamCMD)  
  `D:\steamcmd`
* 新建`steamcmd.bat`，运行  
  `D:\steamcmd\steamcmd.txt`
  ```
  steamcmd +login anonymous +app_update 2394010 validate +quit
  ```
* 新建`palserver.bat`，运行  
  `C:\steamcmd\steamapps\common\PalServer\palserver.bat`
  ```
  palserver.exe port=8211
  ```
* 复制`DefaultPalWorldSettings.ini`  
  `C:\steamcmd\steamapps\common\PalServer\DefaultPalWorldSettings.ini`
  ```
  ; This configuration file is a sample of the default server settings.
  ; Changes to this file will NOT be reflected on the server.
  ; To change the server settings, modify Pal/Saved/Config/WindowsServer/PalWorldSettings.ini.
  [/Script/Pal.PalGameWorldSettings]
  OptionSettings=(Difficulty=None,DayTimeSpeedRate=1.000000,NightTimeSpeedRate=1.000000,ExpRate=1.000000,PalCaptureRate=1.000000,PalSpawnNumRate=1.000000,PalDamageRateAttack=1.000000,PalDamageRateDefense=1.000000,PlayerDamageRateAttack=1.000000,PlayerDamageRateDefense=1.000000,PlayerStomachDecreaceRate=1.000000,PlayerStaminaDecreaceRate=1.000000,PlayerAutoHPRegeneRate=1.000000,PlayerAutoHpRegeneRateInSleep=1.000000,PalStomachDecreaceRate=1.000000,PalStaminaDecreaceRate=1.000000,PalAutoHPRegeneRate=1.000000,PalAutoHpRegeneRateInSleep=1.000000,BuildObjectDamageRate=1.000000,BuildObjectDeteriorationDamageRate=1.000000,CollectionDropRate=1.000000,CollectionObjectHpRate=1.000000,CollectionObjectRespawnSpeedRate=1.000000,EnemyDropItemRate=1.000000,DeathPenalty=All,bEnablePlayerToPlayerDamage=False,bEnableFriendlyFire=False,bEnableInvaderEnemy=True,bActiveUNKO=False,bEnableAimAssistPad=True,bEnableAimAssistKeyboard=False,DropItemMaxNum=3000,DropItemMaxNum_UNKO=100,BaseCampMaxNum=128,BaseCampWorkerMaxNum=15,DropItemAliveMaxHours=1.000000,bAutoResetGuildNoOnlinePlayers=False,AutoResetGuildTimeNoOnlinePlayers=72.000000,GuildPlayerMaxNum=20,PalEggDefaultHatchingTime=72.000000,WorkSpeedRate=1.000000,bIsMultiplay=False,bIsPvP=False,bCanPickupOtherGuildDeathPenaltyDrop=False,bEnableNonLoginPenalty=True,bEnableFastTravel=True,bIsStartLocationSelectByMap=True,bExistPlayerAfterLogout=False,bEnableDefenseOtherGuildPlayer=False,CoopPlayerMaxNum=4,ServerPlayerMaxNum=32,ServerName="Default Palworld Server",ServerDescription="",AdminPassword="",ServerPassword="",PublicPort=8211,PublicIP="",RCONEnabled=False,RCONPort=25575,Region="",bUseAuth=True,BanListURL="https://api.palworldgame.com/api/banlist.txt")
  ```
* `PalWorldSettings.ini`  
  `C:\steamcmd\steamapps\common\PalServer\Pal\Saved\Config\WindowsServer\PalWorldSettings.ini`
  * `Configuration parameters` [[tech.palworldgame.com]](https://tech.palworldgame.com/optimize-game-balance)
  * 粘贴
  * 编辑
    ```
    DayTimeSpeedRate=2.000000,
    NightTimeSpeedRate=2.000000,
    ExpRate=2.000000,
    PalCaptureRate=2.000000,
    PalSpawnNumRate=2.000000,
    PlayerStaminaDecreaceRate=0.500000,
    PlayerAutoHPRegeneRate=2.000000,
    PlayerAutoHpRegeneRateInSleep=2.000000,
    PalAutoHPRegeneRate=2.000000,
    PalAutoHpRegeneRateInSleep=2.000000,
    DeathPenalty=None,
    PalEggDefaultHatchingTime=0.000000,
    ServerName="",
    AdminPassword="",
    ServerPassword="",
    ```
* 下载`FRP` [[github.com]](https://github.com/fatedier/frp/releases)  
  `C:\frp_0.53.2_windows_amd64`
  * 编辑`frps.toml`
    `C:\frp_0.53.2_windows_amd64\frps.toml`
    ```
    bindPort = 6739
    auth.token = "FXOoDpHY6ec8XaJmZHxZwSkrJOhvxL9b8A4SnNFBxcyGqzdXMukO3kudzpnlYfOjdimVJGhT9t05zw9nqH5HjIurqalPWPmw"

    allowPorts = [
      { single = 8211 }
    ]
    ```
    * `bindPort`  
      `随机数生成器` [[jyshare.com]](https://www.jyshare.com/front-end/6680/)
      数字为1~65535之间
    * `auth.token`  
      `密码生成` [[pals.pages.dev]](https://pals.pages.dev/server-tutorial/)
  * 新建`frps.cmd`  
    `C:\frp_0.53.2_windows_amd64\frps.cmd`
    ```
    .\frps.exe -c frps.toml
    ```
  * 编辑`frpc.toml`  
    `C:\frp_0.53.2_windows_amd64\frpc.toml`
    ```
    serverAddr = "80.73.11.31"
    serverPort = 6739

    [[proxies]]
    name = "test-tcp"
    type = "udp"
    localIP = "127.0.0.1"
    localPort = 8211
    remotePort = 8211
    ```
    * `serverAddr`  
      IP地址（公）
  * 新建`frpc.cmd`  
    `C:\frp_0.53.2_windows_amd64\frpc.cmd`
    ```
    .\frpc.exe -c frpc.toml
    ```
  * 运行`frpc.cmd`  
    `C:\frp_0.53.2_windows_amd64\frpc.cmd`
#### 服务器
* 复制`FRP`到服务器
  `C:\Users\Administrator\Desktop\frp_0.53.2_windows_amd64`
* 运行`frps.cmd`
  `C:\Users\Administrator\Desktop\frp_0.53.2_windows_amd64\frps.cmd`

* 运行`幻兽帕鲁`
  * `Commands`
    * Show information on all connected players.
      ```
      /ShowPlayers
      ```
    * Show server information.
      ```
      /Info
      ```
    * Save the world data.
      ```
      /Save
      ```