### `Windows`食用指南
* 安装`FirPE`[[firpe.cn]](https://firpe.cn/page-247)
  * 安装`Windows` [[msdn.sjjzm.com]](https://msdn.sjjzm.com/win11.html)
  * `控制中心`设置`防火墙`/`电源选项`/`鼠标`
  * 设置
    * `系统`
      * `屏幕` `显示卡`
        * `窗口化游戏优化` `关`
        * `高级图形设置` `硬件加速 GPU 计划` `关`
      * `远程桌面` `开`
        * `要求设备使用网络级别身份验证连接` `关`
    * `游戏`
      `游戏模式` `关`
    * `隐私和安全性`
      * `Windows 安全中心`
        * 下载`WDControl` [[landiannews.com]](https://www.landiannews.com/download/93513.html)
  * `Windows 更新`/`Microsoft Store`
    * 安装`Clash for Windows` [[github.com]](https://github.com/Fndroid/clash_for_windows_pkg/releases)
      * 安装`Clash Chinese Path` [[github.com]](https://github.com/BoyceLig/Clash_Chinese_Patch/releases)
      * 启动`UWP应用网络回环`
      * 安装`服务模式`
      * 开启`TUN模式`/`系统代理`/`开机启动`
    * 更新`Windows更新`/`Microsoft Store`
      * 安装[终端预览](./terminal.md)
      * 安装`AV1 Video Extension` [[apps.microsoft.com]](https://apps.microsoft.com/store/detail/av1-video-extension/9MVZQVXJBQ9V)
    * 关闭`Clash for Windows` `系统代理`
* 安装浏览器
  * 下载`Bye Bye Edge` [[github.com]](https://github.com/ShadowWhisperer/Remove-MS-Edge)
  * 浏览器
    * `Chrome Canary` [[www.google.cn]](https://www.google.cn/intl/zh-CN/chrome/canary/)
      * 实验
        * `chrome://flags/#enable-parallel-downloading`
        * `chrome://flags/#chrome-refresh-2023`
    * `Edge Canary` [[microsoft.com]](https://www.microsoft.com/zh-cn/edge/download/insider?form=MA13FJ)
      * 实验 `edge://flags/#enable-parallel-downloading`
  * `Neat Download Manager` [[neatdownloadmanager.com]](http://www.neatdownloadmanager.com/index.php/en/)
  * `qBittorrent Enhanced Edition` [[github.com]](https://github.com/c0re100/qBittorrent-Enhanced-Edition/releases)
    * 设置`Trackers` [[trackerslist.com]](https://trackerslist.com/#/zh)
  * 安装扩展 [[crxdl.com]](https://crxdl.com/)
    * `Adblock Plus` [[chromewebstore.google.com]](https://chromewebstore.google.com/detail/adblock-plus-%E5%85%8D%E8%B4%B9%E7%9A%84%E5%B9%BF%E5%91%8A%E6%8B%A6%E6%88%AA%E5%99%A8/cfhdojbkjhnklbpkdaibdccddilifddb)
    * `篡改猴测试版` [[chromewebstore.google.com]](https://chromewebstore.google.com/detail/%E7%AF%A1%E6%94%B9%E7%8C%B4%E6%B5%8B%E8%AF%95%E7%89%88/gcalenpjmijncebpfijmoaglllgpjagf)
      * `GitHub增强` [[greasyfork.org]](https://greasyfork.org/zh-CN/scripts/412245-github-%E5%A2%9E%E5%BC%BA-%E9%AB%98%E9%80%9F%E4%B8%8B%E8%BD%BD)
      * `网盘直链下载助手` [[greasyfork.org]](https://greasyfork.org/zh-CN/scripts/436446-%E7%BD%91%E7%9B%98%E7%9B%B4%E9%93%BE%E4%B8%8B%E8%BD%BD%E5%8A%A9%E6%89%8B)
      * `全网VIP视频免费破解` [[greasyfork.org]](https://greasyfork.org/zh-CN/scripts/438657-%E5%85%A8%E7%BD%91vip%E8%A7%86%E9%A2%91%E5%85%8D%E8%B4%B9%E7%A0%B4%E8%A7%A3-%E4%B8%93%E6%B3%A8%E4%B8%80%E4%B8%AA%E8%84%9A%E6%9C%AC%E5%8F%AA%E5%81%9A%E4%B8%80%E4%BB%B6%E4%BA%8B%E4%BB%B6)
    * `Proxy SwitchyOmega` [[chromewebstore.google.com]](https://chromewebstore.google.com/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif)
      * `选项`
      * `情景模式`
        * `auto switch`
          * `编辑源代码`
            ```
            [SwitchyOmega Conditions]
            @with result

            *.asus.com.cn +direct
            *.baidu.com +direct
            *.ipw.cn +direct
            *.oracle.com +direct
            *.penguin-stats.cn +direct
            *.speedtest.cn +direct
            *.yhmgo.com +direct

            * +proxy
            ```
    * `NeatDownloadManager Extension` [[chromewebstore.google.com]](https://chromewebstore.google.com/detail/neatdownloadmanager-exten/cpcifbdmkopohnnofedkjghjiclmhdah)
    * `猫抓` [[chromewebstore.google.com]](https://chromewebstore.google.com/detail/%E7%8C%AB%E6%8A%93/jfedfbgedapdagkghmgibemcoggfppbb)
    * `M3U8 Downloader` [[chromewebstore.google.com]](https://chromewebstore.google.com/detail/m3u8-downloader/pibnhedpldjakfpnfkabbnifhmokakfb)
    * `BewlyBewly` [[chromewebstore.google.com]](https://chromewebstore.google.com/detail/bewlybewly/bbbiejemhfihiooipfcjmjmbfdmobobp)
    * `ACG助手` [[chromewebstore.google.com]](https://chromewebstore.google.com/detail/acg%E5%8A%A9%E6%89%8B%EF%BC%9Abilibili-%E7%BB%BC%E5%90%88%E8%BE%85%E5%8A%A9%E6%89%A9%E5%B1%95/kpbnombpnpcffllnianjibmpadjolanh)
      * 登录
    * `B站下载助手` [[csser.top]](https://csser.top/)
    * `购物党自动比价助手` [[chromewebstore.google.com]](https://chromewebstore.google.com/detail/%E8%B4%AD%E7%89%A9%E5%85%9A%E8%87%AA%E5%8A%A8%E6%AF%94%E4%BB%B7%E5%B7%A5%E5%85%B7/jgphnjokjhjlcnnajmfjlacjnjkhleah)
    * `SteamDB` [[chromewebstore.google.com]](https://chromewebstore.google.com/detail/steamdb/kdbmhfkmnlmbkgbabkdealhhbfhlmmon)
* 安装`Bandizip` [[bandisoft.com]](http://www.bandisoft.com/bandizip/dl/)
* 下载`Geek` [[geekuninstaller.com]](https://geekuninstaller.com/)
* 安装`搜狗输入法` [[shurufa.sogou.com]](https://shurufa.sogou.com/)
* 安装驱动
  * `英特尔驱动程序和支持助理` [[intel.cn]](https://www.intel.cn/content/www/cn/zh/support/intel-driver-support-assistant.html)
  * `Intel XTU`
  * `GFE` [[nvidia.cn]](https://www.nvidia.cn/geforce/geforce-experience/)
    * `Nvidia 控制面板`
      * `桌面` `启用开发者设置`
        * `开发者` `允许所有用户访问 GPU 性能计数器`
        * `通过预览调整图像设置` `使用“高级 3D 图像”设置`
        * `管理 3D 设置`
          * `全局设置`
            功能|设置
            :-|:-
            OpenGL GDI 兼容性|优先性能
            OpenGL 渲染 GPU|
            Vulkan/OpenGL 现行方法|优先本机
            低延时模式|开
            垂直同步|关
            平滑处理 - 模式|关
            平滑处理 - 灰度纠正|关
            电源管理模式|最高性能优先
            着色器缓存大小|无限制
            纹理过滤 - 三线性优化|关
            纹理过滤 - 负 LOD 偏移|锁定
            纹理过滤 - 质量|高质量
            线程优化|开
            首选刷新率|最高可用
          * `程序设置` `C:\Windows\explorer.exe`
            功能|设置
            :-|:-
            电源管理模式|使用全局设置
        * `配置 Surround、PhysX`
  * `Afterburner` [[tw.msi.com]](https://tw.msi.com/Landing/afterburner/graphics-cards)
  * `DDU` [[wagnardsoft.com]](https://www.wagnardsoft.com/display-driver-uninstaller-DDU)
  * `Armoury Crate` [[apps.microsoft.com]](https://apps.microsoft.com/store/detail/armoury-crate/9PM9DFQRDH3F)
    * 安装/更新驱动
  * `360驱动大师` [[dm.weishi.360.cn]](https://dm.weishi.360.cn/home.html)
  * `OpenRGB` [[openrgb.org]](https://openrgb.org/)
  * `FL Esports` [[flesports.com]](http://www.flesports.com/down/)
    * 
* 替换`记事本`
  * 安装`Notepad3` [[rizonesoft.com]](https://www.rizonesoft.com/downloads/notepad3/)
  * 安装`VS Code Insiders` [[code.visualstudio.com]](https://code.visualstudio.com/)
* 替换`电影和电视`
  * 安装`PotPlayer` [[potplayer.daum.net]](https://potplayer.daum.net/?lang=zh_CN)
* 下载`Office Tools Plus` [[github.com]](https://github.com/YerongAI/Office-Tool/releases/)
  * 安装`.Net 6` [[dotnet.microsoft.com]](https://dotnet.microsoft.com/zh-cn/download/dotnet/6.0)
  * 安装`Office 365`
* 下载`HEU KMS Activator` [[github.com]](https://github.com/zbezj/HEU_KMS_Activator/releases)
* 下载`TrafficMonitor` [[github.com]](https://github.com/zhongyang219/TrafficMonitor/actions)
* [程序](./program%20files.md)
  * 安装[AList](./alist.md)
  * 安装[DDNS_Go](./ddns-go.md)
* [游戏](./games.md)