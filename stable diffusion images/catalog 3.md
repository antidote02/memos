### `Stable Diffusion WebUI` 附录 3
* [Stable Diffusion WebUI](/stable%20diffusion%20web%20ui.md).md [[github.com]](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/dev)
* `Models`
  * `Rabbit` [[civitai.com]](https://civitai.com/models/121696)
  * `Flat-2D Animerge` [[civitai.com]](https://civitai.com/models/35960)
  * `MeinaHentai` [[civitai.com]](https://civitai.com/models/12606)
* `通用起手式`
  ```
  ((masterpiece)), (((best quality))), ((ultra detailed)), ((illustration)), ((disheveled hair)), <lora:add_detail:1>, nsfw, pantyhose,
  # 反例
  negative_hand-neg, verybadimagenegative_v1.3, EasyNegativeV2, (worst quality, low quality:1.4), monochrome, (zombie), (interlocked fingers:1.2), extra monochrome, (sketch, comic), signature, logo, long body, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digits, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,
  ```
* `元素魔法目录 - 续`
  * `白虎志`
    ```
    original, extremely detailed wallpaper, (((beijing opera))), (sketch), (wash painting), ((splash of color)), ((splash ink)), ((((dyeing)))), ((chinese painting)), ((colorful)) (beautiful and delicate mountain), (fantasy creatures), ((chinese white tiger)), (solo:1.8), black markings, (white tiger), beautiful and delicate yellow eyes, huge claws, big and strong, diabolical, tyrannical,
    # 反向
    missing arms, large breasts,
    ```
    * `采样方法` `Euler`
    * `迭代步数` `40`
    * `提示词引导系数` `5.5`
    * `生成`
      * `MeinaHentai`
![](2023-10-27/grid-0025.png)