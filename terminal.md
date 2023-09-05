### `终端预览`食用指南
* 安装`终端预览` [[apps.microsoft.com]](https://apps.microsoft.com/store/detail/windows-terminal-preview/9N8G5RFZ9XK3)
* 安装`PowerShell` [[github.com]](https://github.com/PowerShell/PowerShell/releases)
* `PowerShell`执行策略
  ```
  # 获取所有执行策略
  get-executionpolicy -list
  # 设置执行策略
  set-executionpolicy bypass
  ```
* `PowerShell`安装`Scoop`
  ```
  # 下载脚本
  irm get.scoop.sh -outfile 'install.ps1'
  # 安装
  .\install.ps1 -runasadmin
  # 删除脚本
  rm install.ps1
  # 配置代理
  scoop config proxy localhost:7890
  # 安装 Git
  scoop install -k git
  # 配置 Git 用户名/邮箱
  git config --global user.name  "antidote02"
  git config --global user.email  "1729304580@qq.com"
  # 配置 Git 代理
  git config --global http.proxy http://localhost:7890
  git config --global https.proxy https://localhost:7890
  # 添加 Bucket
  scoop bucket known
  scoop bucket add extras
  scoop bucket add versions
  scoop bucket add nirsoft
  scoop bucket add sysinternals
  scoop bucket add php
  scoop bucket add nerd-fonts
  scoop bucket add nonportable
  scoop bucket add java
  scoop bucket add games
  scoop bucket add dorado https://github.com/chawyehsu/dorado
  # 升级
  scoop update -k *
  # 删除缓存
  scoop cache rm *
  ```
* 安装`Curl`
  ```
  # 安装
  scoop install -k curl
  # IPV4
  curl 4.ipw.cn
  # IPV6
  curl 6.ipw.cn
  ```
* 安装`AList`
  * 安装
    ```
    # 安装
    scoop install -k alist
    # 密码
    alist admin
    # 启动/重启
    alist restart
    # 关闭
    alist stop
    ```
  * 安装服务  
    * 新建`AList.txt`
      ```
      Dim ws
      Set ws = Wscript.CreateObject("Wscript.Shell")
      ws.run "alist restart",vbhide
      Wscript.quit
      ```
    * 重命名`AList.vbs`
    * 移动到`C:\Users\Administrator\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`
  * `AList` [[localhost:5244]](http://localhost:5244/)
* 安装`DDNS-Go` [[github.com]](https://github.com/jeessy2/ddns-go/releases)
  * 安装服务
    ```
    .\ddns-go.exe -s install
    ```
  * `DDNS-Go` [[localhost:9876]](http://localhost:9876/)
### 以上