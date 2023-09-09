### `AList`食用指南
* 安装`AList`
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