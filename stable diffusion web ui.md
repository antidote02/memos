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
* 安装`webui-user.bat`  
  `C:\Program Files\stable-diffusion-webui-master\webui-user.bat`
  * `Clash for Windows`开启`系统代理`
  * 安装/升级`PIP`
    ```
    cd "C:\Program Files\stable-diffusion-webui-master\venv\Scripts"
    .\python -m pip install --upgrade pip
    ```
  * 编辑`webui-user.bat`  
    `C:\Program Files\stable-diffusion-webui-master\webui-user.bat`
    ```
    set COMMANDLINE_ARGS=--opt-sdp-attention --opt-sdp-no-mem-attention --opt-channelslast
    ```
* 创建`webui-user.bat`快捷方式并运行  
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
          * `LoCon` [[github.com]](https://github.com/KohakuBlueleaf/a1111-sd-webui-locon)
          * `Ultimate SD Upscale` [[github.com]](https://github.com/Coyote-A/ultimate-upscale-for-automatic1111)
          * `Image browser` [[github.com]](https://github.com/AlUlkesh/stable-diffusion-webui-images-browser)
          * `Dynamic Thresholding` [[github.com]](https://github.com/mcmonkeyprojects/sd-dynamic-thresholding)
          * `Cutoff` [[github.com]](https://github.com/hnmr293/sd-webui-cutoff)
      * `Installed`
* 下载`Models`  
  `C:\Program Files\stable-diffusion-webui-master\models\Stable-diffusion`
  * `Rabbit` [[civitai.com]](https://civitai.com/models/121696)
  * `Flat-2D Animerge` [[civitai.com]](https://civitai.com/models/35960)
* 下载`Embeddings`  
  `C:\Program Files\stable-diffusion-webui-master\embeddings`
  * `veryBadImageNegative` [[civitai.com]](https://civitai.com/models/11772/verybadimagenegative)
  * `EasyNegativeV2` [[huggingface.co]](https://huggingface.co/gsdf/Counterfeit-V3.0/tree/main)
* 下载`LYCORIS`
  * 新建`LyCORIS`文件夹  
    `C:\Program Files\stable-diffusion-webui-master\models\LyCORIS`
  * 下载
    * `EnvyBetterHands` [[civitai.com]](https://civitai.com/models/47085)
      ```
      # 正向提示词
      <lora:GoodHands-beta2:1>, nice hands, perfect hands,
      # 反向提示词
      <lora:GoodHands-beta2:1>, extra fingers, deformed hands, polydactyl:1.5,
      ```
* 下载`Lora`  
  `C:\Program Files\stable-diffusion-webui-master\models\Lora`
  * `Viper (Valorant)` [[civitai.com]](https://civitai.com/models/73643)
    ```
    <lora:viper-nvwls-v2:1>, green eyes, bodysuit, gloves, belt, thigh boots, respirator,
    ```
  * `Arknights-Hoolheyak` [[civitai.com]](https://civitai.com/models/48645)
    ```
    <lora:Hoolheyakv2-pynoiseloha:1>, original outfit, fingerless gloves, white dress, black pantyhose, large breasts, open coat,
    ```
  * `Rebecca / Cyberpunk Edgerunners` [[civitai.com]](https://civitai.com/models/37539)
    ```
    1girl, rebecca \(cyberpunk\), solo, twintails, black hairband mechanical eye, colored sclera, red sclera, colored skin, white skin, leg tattoo, neck tattoo, green hair, small breasts, black bra, thong, red pupils, skin fang, red eyes, black jacket,
    ```
  * `real spread pussy(experimental)` [[civitai.com]](https://civitai.com/models/19669)
    ```
    <lora:spp_spreadpussy-W-V1:0.4>, uncensored, realspreadpussy,
    ```
  * `Ass On Glass` [[civitai.com]](https://civitai.com/models/19295)
    ```
    <lora:Ass On Glass:0.8>, ass on glass,
    ```
  * `Bukkake` [[civitai.com]](https://civitai.com/models/16722)
    ```
    <lora:Bukkake:0.75>, bukkake,
    ```
  * `POV Squatting Cowgirl` [[civitai.com]](https://civitai.com/models/8877)
    ```
    <lora:pscowgirl:1>, 1boy, squatting cowgirl position, vaginal, pov,
    ```
  * `Helltaker` [[civitai.com]](https://civitai.com/models/8429)
    ```
    <lora:Helltaker:0.6>,
    ```
  * `Lucy (Cyberpunk Edgerunners)` [[civitai.com]](https://civitai.com/models/5477)
* 食用
  * `Settings`
    * `User interface`
      * `Localization` **<font color="red">`zh-Hans (Testing)`</font>**
    * `Apply settings`
    * `Reload UI`
  * `设置`
    * `翻译文件名` **<font color="red">`zh_cn_tr.csv`</font>**
  * `Stable Diffusion 模型`
  * `文生图`
    * `正向提示词`
      ```
      (best-quality:0.8), perfect anime illustration,
      <lora:GoodHands-beta2:1>, nice hands, perfect hands,
      ```
    * `反向提示词`
      ```
      (worst quality:0.8), (surreal:0.8), (modernism:0.8), (art deco:0.8), (art nouveau:0.8),
      extra fingers, deformed hands, (polydactyly:1.5),
      verybadimagenegative_v1.3,
      EasyNegativeV2,
      ```
    * `生成`
      * `采样方法` **<font color="red">`DPM2 Karras`</font>**
      * `迭代步数`
      * `高分辨率修复`
        * `放大算法` **<font color="red">`R-ESRGAN 4x+ Anime6B`</font>**
        * `高分迭代步数`
        * `重绘幅度` **<font color="red">`0.45`</font>**
      * `宽度` **<font color="red">`768-`</font>**
      * `高度` **<font color="red">`768-`</font>**
      * `提示词引导系数` **<font color="red">`10`</font>**
      * `Dynamic Thresholding`
        * `模拟提示词相关性` **<font color="red">`7`</font>**