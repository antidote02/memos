### `Stable Diffusion web UI`
* `元素法典` `生成`
  * [[Catalog 2]](stable%20diffusion%20images/catalog%202.md)
  * [[Catalog]](stable%20diffusion%20images/catalog.md)
* 安装`Python 3.10`
  ```
  scoop install -k python310
  ```
* 下载`Stable Diffusion Web UI` [[github.com]](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/dev)  
* 下载`Models`  
  * 新建文件夹`models\Stable-diffusion`
    `C:\Program Files\stable-diffusion-webui-dev\models\Stable-diffusion`
  * 下载`Models`
    `C:\Program Files\stable-diffusion-webui-dev\models\Stable-diffusion`
    * `Rabbit` [[civitai.com]](https://civitai.com/models/121696)
    * `Flat-2D Animerge` [[civitai.com]](https://civitai.com/models/35960)
    * `MeinaHentai` [[civitai.com]](https://civitai.com/models/12606)
      * `MeinaMix` [[civitai.com]](https://civitai.com/models/7240)
    * `国风3` [[civitai.com]](https://civitai.com/models/10415)
    * `Hassaku` [[civitai.com]](https://civitai.com/models/2583)
* 安装`webui-user.bat`  
  `C:\Program Files\stable-diffusion-webui-dev\webui-user.bat`
  * `Clash for Windows`开启`系统代理`
  * 安装/升级`PIP`
    ```
    cd "C:\Program Files\stable-diffusion-webui-dev\venv\Scripts"
    .\python -m pip install --upgrade pip
    ```
  * 编辑`webui-user.bat`  
    `C:\Program Files\stable-diffusion-webui-dev\webui-user.bat`
    ```
    set COMMANDLINE_ARGS=--xformers --listen
    ```
* 创建`webui-user.bat`快捷方式并运行  
  `C:\Program Files\stable-diffusion-webui-dev\webui-user.bat`
* 安装`Extensions`
  * `Stable Diffusion` [[127.0.0.1:7860]](http://127.0.0.1:7860/)
    * `Extensions`
      * `Install from URL`
        * `URL for extiension's git respository`
          * `zh_Hans Localization` [[github.com]](https://github.com/hanamizuki-ai/stable-diffusion-webui-localization-zh_Hans)
          * `Booru tag autocompletion` [[github.com]](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete)
            * [[space.bilibili.com]](https://space.bilibili.com/10090250/video)  
              * `zh_cn.csv`  
                `C:\Program Files\stable-diffusion-webui-dev\extensions\a1111-sd-webui-tagcomplete\tags\zh_cn.csv`  
              * `zh_cn_tr.csv`  
                `C:\Program Files\stable-diffusion-webui-dev\extensions\a1111-sd-webui-tagcomplete\tags\zh_cn_tr.csv`
          * `Easy Prompt Selector` [[github.com]](https://github.com/blue-pen5805/sdweb-easy-prompt-selector)
            * `汉化` [[zhuanlan.zhihu.com]](https://zhuanlan.zhihu.com/p/632547344)  
              `C:\Program Files\stable-diffusion-webui-dev\extensions\sdweb-easy-prompt-selector\tags`
          * `Image browser` [[github.com]](https://github.com/AlUlkesh/stable-diffusion-webui-images-browser)
          * `Dynamic Thresholding` [[github.com]](https://github.com/mcmonkeyprojects/sd-dynamic-thresholding)
          * `Cutoff` [[github.com]](https://github.com/hnmr293/sd-webui-cutoff)
          * `Ultimate SD Upscale` [[github.com]](https://github.com/Coyote-A/ultimate-upscale-for-automatic1111)
          * `Civitai` [[github.com]](https://github.com/civitai/sd_civitai_extension)
            * `Socketio`
              ```
              cd "C:\Program Files\stable-diffusion-webui-dev\extensions\sd_civitai_extension"
              python install.py
              ```
      * `Installed`
* 下载`Embeddings`  
  `C:\Program Files\stable-diffusion-webui-dev\embeddings`
  * `negative_hand Negative` [[civitai.com]](https://civitai.com/models/56519)
  * `veryBadImageNegative` [[civitai.com]](https://civitai.com/models/11772/verybadimagenegative)
  * `EasyNegativeV2` [[huggingface.co]](https://huggingface.co/gsdf/Counterfeit-V3.0/tree/main)
* 下载`LYCORIS`
  * 新建`LyCORIS`文件夹  
    `C:\Program Files\stable-diffusion-webui-dev\models\LyCORIS`
  * 下载
* 下载`Lora`  
  `C:\Program Files\stable-diffusion-webui-dev\models\Lora`
  * `Character`
    * `Viper (Valorant)` [[civitai.com]](https://civitai.com/models/73643)
      ```
      <lora:viper-nvwls-v2:0.8>, valorantviper, green eyes,
      bodysuit, gloves, belt, thigh boots, respirator,
      ```
    * `Arknights-Hoolheyak` [[civitai.com]](https://civitai.com/models/48645)
      ```
      <lora:Hoolheyakv2-pynoiseloha:0.8>, large breasts,
      fingerless gloves, white dress, black pantyhose, open coat,
      ```
    * `Rebecca / Cyberpunk Edgerunners` [[civitai.com]](https://civitai.com/models/37539)
      ```
      <lora:rebecca_v1:1>, twintails, black hairband, mechanical eye, colored sclera, red sclera, colored skin, white skin, leg tattoo, neck tattoo, green hair, small breasts, red pupils, skin fang, red eyes,
      black bra, thong, black jacket,
      ```
    * `Valorant Jett` [[civitai.com]](https://civitai.com/models/10964)
      ```
      <lora:ValorantJett:0.75>, jett,
      ```
    * `Lucy (Cyberpunk Edgerunners)` [[civitai.com]](https://civitai.com/models/5477)
      ```
      <lora:lucy_offset:1>, (robot joints:0.5), mechanical parts,
      jackets, shorts,
      ```
  * `Poses`
    * `Pleasure in triplets is better` [[civitai.com]](https://civitai.com/models/138712)
      ```
      <lora:1654435350039971448:1>, (1girl), purple hair, red eyes, large breats, nude, sex, (vaginal), cum, sweat, (gangbang), multiple boys,
      ```
    * `cowgirl with hands on knees` [[civitai.com]](https://civitai.com/models/128170)
      ```
      <lora:cowgirl_with_hands_on_knees_v1.0:1>, pov, astride,
      ```
    * `Ass On Glass` [[civitai.com]](https://civitai.com/models/19295)
      ```
      <lora:Ass On Glass:0.8>, ass on glass,
      ```
    * `Murky's - Cum on Tongue` [[civitai.com]](https://civitai.com/models/16775)
      ```
      <lora:Cumontongue:1>, open mouth, cum in mouth, cum on tongue, tongue out, cum,
      cum on hands, cupping hands, own hands together,
      ```
    * `Bukkake` [[civitai.com]](https://civitai.com/models/16722)
      ```
      <lora:Bukkake:0.75>, bukkake,
      ```
    * `POV Squatting Cowgirl` [[civitai.com]](https://civitai.com/models/8877)
      ```
      <lora:pscowgirl:1>, 1boy, squatting cowgirl position, vaginal, pov,
      ```
    * `Bondage Suspension` [[civitai.com]](https://civitai.com/models/8762)
      ```
      <lora:suspension:1>, suspension, spread legs, rope, shibari,
      ```
    * `POV Doggystyle` [[civitai.com]](https://civitai.com/models/8723)
      ```
      <lora:POVDoggy:1>, 1boy, penis, doggystyle, from behind,
      pov hands, ass grab, deep skin,
      facing away, nude, implied sex,
      pov hands, spread anus, spread ass, deep skin, hands on ass,
      ```
    * `Grabbing own Ass` [[civitai.com]](https://civitai.com/models/8179)
      ```
      <lora:GrabOwnAss:1>, (grabbing own ass), (hands on own ass), ass stretch, ass spread,
      ```
  * `Concept`
    * `细节调整` [[civitai.com]](https://civitai.com/models/58390)
      ```
      <lora:add_detail:2>
      ```
  * `Style`
    * `像素人人` [[civitai.com]](https://civitai.com/models/44960)
      ```
      <lora:pixel_f2:0.5>, pixel,
      ```
    * `Helltaker` [[civitai.com]](https://civitai.com/models/8429)
      ```
      <lora:Helltaker:0.6>,
      ```
* 食用
  * `Settings`
    * `User interface`
      * `Localization` **<font color="red">`zh-Hans (Testing)`</font>**
    * `Apply settings`
    * `Reload UI`
  * `设置`
    * `用户界面`
      * `快捷设置列表` 
        * **<font color="red">`sd_model_checkpoint`</font>**
        * **<font color="red">`CLIP_stop_at_last_layers`</font>**
    * `标签自动补全`
      * `翻译文件名` **<font color="red">`zh_cn_tr.csv`</font>**
    * `实时过程预览`
      * `显示当前生成图像的实时预览`
      * `实时预览显示周期` **<font color="red">`1`</font>**
      * `实时预览模式` **<font color="red">`Approx NN`</font>**
      * `允许在 lowvram/medvram 设置下使用完整实时预览`
      * `进度条/预览图更新周期` **<font color="red">`1`</font>**
      * `当生成过程中断时，通过所选的实时预览模式提供结果图像`
    * `保存设置`
    * `重载 UI`
  * `Stable Diffusion 模型`
  * `CLIP 终止层数` **<font color="red">`1`</font>**
  * `文生图`
    * `正向提示词`
      ```
      ((masterpiece)), (((best quality))), ((ultra detailed)), ((illustration)), ((disheveled hair)), <lora:add_detail:1>, nsfw, pantyhose,
      ```
    * `反向提示词`
      ```
      negative_hand-neg, verybadimagenegative_v1.3, EasyNegativeV2, (worst quality, low quality:1.4), monochrome, (zombie), (interlocked fingers:1.2), extra monochrome, (sketch, comic), signature, logo, long body, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digits, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,
      ```
    * `生成`
      <table>
      <tbody>
      <tr>
      <td style="text-align: center;">Model</td>
      <td style="text-align: center;">CLIP 终止层数</td>
      <td style="text-align: center;">采样方法</td>
      <td style="text-align: center;">迭代步数</td>
      <td style="text-align: center;">放大算法</td>
      <td style="text-align: center;">高分迭代步数</td>
      <td style="text-align: center;">重绘幅度</td>
      <td style="text-align: center;">提示词引导系数</td>
      </tr>
      <tr style="text-align: center;">
      <td>Flat-2D Animerge</td>
      <td>&nbsp;</td>
      <td>&nbsp;</td>
      <td>&nbsp;</td>
      <td>R-ESRGAN 4x+ Anime6B</td>
      <td>&nbsp;</td>
      <td>0.45</td>
      <td>10</td>
      </tr>
      <tr style="text-align: center;">
      <td rowspan="2">MeinaHentai</td>
      <td rowspan="2">2</td>
      <td>Euler a</td>
      <td>20～40</td>
      <td rowspan="2">R-ESRGAN 4x+ Anime6B</td>
      <td rowspan="2">10～15</td>
      <td rowspan="2">0.2～0.4</td>
      <td rowspan="2">7</td>
      </tr>
      <tr style="text-align: center;">
      <td>DPM++ SDE Karras</td>
      <td>20～30</td>
      </tr>
<tr style="text-align: center;">
<td rowspan="3">MeinaMix</td>
<td rowspan="3">2</td>
<td>Euler a</td>
<td>40～60</td>
<td rowspan="3">R-ESRGAN 4x+ Anime6B</td>
<td rowspan="3">10</td>
<td rowspan="3">0.3～0.6</td>
<td rowspan="3">４～11</td>
</tr>
<tr style="text-align: center;">
<td>DPM++ SDE Karras</td>
<td>20～30</td>
</tr>
<tr style="text-align: center;">
<td>DPM++ 2M Karras</td>
<td>20～60</td>
</tr>
<tr style="text-align: center;">
<td rowspan="2">Hassaku</td>
<td rowspan="2">2</td>
<td>DPM++ SDE Karras</td>
<td>&nbsp;</td>
<td>R-ESRGAN 4x+ Anime6B</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr style="text-align: center;">
<td>DDIM</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr style="text-align: center;">
<td>国风3</td>
<td>2</td>
<td>DPM++ SDE Karras</td>
<td>30～50</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>