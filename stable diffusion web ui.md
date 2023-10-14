### `Stable Diffusion web UI`
* 安装`Python 3.10`
  ```
  scoop install -k python310
  ```
* 下载`Stable Diffusion Web UI`  
  `C:\Program Files\stable-diffusion-webui-master`
  ```
  cd C:\Program Files
  md stable-diffusion-webui-master
  cd C:\Program Files\stable-diffusion-webui-master
  git clone https://gitclone.com/github.com/AUTOMATIC1111/stable-diffusion-webui.git
  ```
* 运行`webui-user.bat`  
  `C:\Program Files\stable-diffusion-webui-master\webui-user.bat`
* `Clash for Windows`开启`系统代理`
* 安装`PIP`
  ```
  cd "C:\Program Files\stable-diffusion-webui-master\venv\Scripts"
  .\python -m pip install --upgrade pip
  ```
* 运行`webui-user.bat`  
  `C:\Program Files\stable-diffusion-webui-master\webui-user.bat`
* 安装`Extensions`
  * `Stable Diffusion` [[127.0.0.1:7860]](http://127.0.0.1:7860/)
    * `Extensions`
      * `Install from URL`
        * `URL for extiension's git respository`
          * `zh_Hans Localization` [[github.com]](https://github.com/hanamizuki-ai/stable-diffusion-webui-localization-zh_Hans)
          * `Booru tag autocompletion` [[github.com]](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete)
            * [[space.bilibili.com]](https://space.bilibili.com/10090250/video)  
              * `zh_cn.csv`  
                `C:\Program Files\stable-diffusion-webui-master\extensions\a1111-sd-webui-tagcomplete\tags\zh_cn.csv`  
              * `zh_cn_tr.csv`  
                `C:\Program Files\stable-diffusion-webui-master\extensions\a1111-sd-webui-tagcomplete\tags\zh_cn_tr.csv`
              * 
          * `Image browser` [[github.com]](https://github.com/AlUlkesh/stable-diffusion-webui-images-browser)
          * `Dynamic Thresholding` [[github.com]](https://github.com/mcmonkeyprojects/sd-dynamic-thresholding)
      * `Installed`
* 下载`Models`  
  `C:\Program Files\stable-diffusion-webui-master\models\Stable-diffusion`
  * `Flat-2D Animerge` [[civitai.com]](https://civitai.com/models/35960)
* 下载`Embeddings`  
  `C:\Program Files\stable-diffusion-webui-master\embeddings`
  * `veryBadImageNegative` [[civitai.com]](https://civitai.com/models/11772/verybadimagenegative)
  * `EasyNegative` [[civitai.com]](https://civitai.com/models/7808/easynegative)
* 食用
  * `Settings`
    * `User interface`
      * `Localization` **<font color="red">`zh-Hans (Testing)`</font>**
    * `Apply settings`
    * `Reload UI`
  * `设置`
    * `标签自动补全` **<font color="red">`zh_cn.csv`</font>**
    * `翻译文件名` **<font color="red">`zh_cn_tr.csv`</font>**
  * `Stable Diffusion 模型`
  * `文生图`
    * `正向提示词`
      ```
      (best-quality:0.8), perfect anime illustration,
      ```
    * `反向提示词`
      ```
      (worst quality:0.8), (surreal:0.8), (modernism:0.8), (art deco:0.8), (art nouveau:0.8), verybadimagenegative_v1.3, easynegative,
      ```
    * `生成`
      * `采样方法` **<font color="red">`DPM++ 2M Karras`</font>**
      * `迭代步数` **<font color="red">`30`</font>**
      * `高分辨率修复`
        * `放大算法` **<font color="red">`R-ESRGAN 4x+ Anime6B`</font>**
        * `重绘幅度` **<font color="red">`0.45`</font>**
      * `宽度` **<font color="red">`512`</font>**
      * `高度` **<font color="red">`512`</font>**
      * `提示词引导系数` **<font color="red">`10`</font>**
      * `Dynamic Thresholding`
        * `模拟提示词相关性` **<font color="red">`7`</font>**