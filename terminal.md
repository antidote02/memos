### `终端预览`食用指南
* 下载`终端预览` [[apps.microsoft.com]](https://apps.microsoft.com/store/detail/windows-terminal-preview/9N8G5RFZ9XK3)
* 下载`PowerShell` [[github.com]](https://github.com/PowerShell/PowerShell/releases)
* 设置`PowerShell`执行策略
  ```
  # 获取所有执行策略
  get-executionpolicy -list
  # 更改执行策略
  set-executionpolicy bypass
  ```
* `PowerShell`安装`Scoop`
  ```
  # 下载脚本
  irm get.scoop.sh -outfile 'install.ps1'
  # 安装
  .\install.ps1 -runasadmin -ScoopDir 'C:\Program Files\Scoop' -ScoopGlobalDir 'C:\Program Files\Scoop\GlobalScoopApps'
  # 删除脚本
  rm install.ps1
  # 设置代理
  scoop config proxy localhost:7890
  # 安装 Git
  scoop install -k git
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