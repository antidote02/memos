### `Stable Diffusion WebUI` 附录 2
* [Stable Diffusion WebUI](/stable%20diffusion%20web%20ui.md).md [[github.com]](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/dev)
* `Models`
  * `Rabbit` [[civitai.com]](https://civitai.com/models/121696)
  * `Flat-2D Animerge` [[civitai.com]](https://civitai.com/models/35960)
  * `MeinaHentai` [[civitai.com]](https://civitai.com/models/12606)
* `通用起手式`
  ```
  (masterpiece:1.21), (best quality:1.33), (ultra detailed:1.21), (illustration:1.21), (disheveled hair:1.21), <lora:add_detail:2>, nsfw, pantyhose,
  # 反例
  negative_hand-neg, verybadimagenegative_v1.3, EasyNegativeV2, (worst quality, low quality:1.4), monochrome, (zombie), (interlocked fingers:1.2), extra monochrome, (sketch, comic), signature, logo, long body, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digits, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet,
  ```
* `元素魔法目录 - 续`
  * `辉煌阳光法`
    ```
    {1girl}, amazing, beautiful detailed eyes, solo, fine details, depth of field, extremely detailed cg, original, extremely detailed wallpaper, {{highly detailed skin}}, {{messy hair}}, {small breasts}, {longuette}, {grassland}, {yellow eyes}, full body, incredibly absurdres, {gold hair}, lace, floating hair, a large number of environments, medieval, grace, a girl leans her hand on the fence, birds, altocumulus, 8k wallpaper, hair hoop, long hair, gem necklace, hair ornament, prospect, water eyes, wind, breeze, god ray, lawn, mountains and lake in the distance, the skirt swaying in the wind, sunlight through the trees, vast grassland, fence, blue sky, bloom, smile, glow, grass swaying in the wind,
    # 反向
    {{{{{{{{{bad hands}}}}}}}}}, small hands, multiple limbs, bad feet, long nails, {{{{interlocked fingers}}}}, milk, ugly, duplicate, morbid, mutilated, tranny, trans, transsexual, mutation, deformed, long neck, bad proportions, extra arms, extra legs, disfigured, more than 2 nipples, malformed, mutated, hermaphrodite, out of frame, extra drawn, long body, multiple breasts, cloned face, gross proportions, mutated hands, bad feet, long neck, missing limb, malformed limbs, malformed hands fused fingers, too many fingers, extra fingers, missing fingers, text font ui, futa, yaoi,
    ```
    * `采样方法` `Euler`
    * `迭代步数` `40`
    * `提示词引导系数` `7`
    * `生成`
      * `MeinaHentai`
![](2023-10-25/grid-0076.png)
  * `百溺法`
    ```
    (watercolor), (extremely detailed cg unity 8k wallpaper:1.21), (game cg), (1girl), (solo), (best illustration), (extremely detailed illustration), (beautiful detailed lighting:1.21), (from above), (extremely delicate and beautiful:1.21), cinematic lighting, dynamic angle, detailed wet clothes, blank stare, overexposure, floating, (beautiful detailed eyes), side blunt bangs, small breasts, black long straight, red eyes, aqua eyes, gradient eyes, black hair, very long hair, blunt bangs, (blood:1.21), white dress, frills, bowtie, (expressionless:1.21), extremely beautiful and detail water, (lying on the lake:1.21), (hairs curled in water:1.21), (blood red water:1.5), (red background:1.3), swirl,
    # 反向
    long face, extra legs, extra arms, fused arms, fused legs, extra feet, fused feet, abnormal legs, abnormal shoulders, poorly drawn shoulders, misplaced arms, misplaced legs, misplaced hands, abnormal hands, multiple heads, abnormal face, twisted head,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `20`
    * `提示词引导系数` `4.5`~`5.5`
    * `生成`
      * `MeinaHentai`
        * `提示词引导系数`
          * `5.5`
![](2023-10-25/grid-0072.png)
          * `4.5`
![](2023-10-25/grid-0073.png)
  * `沉入星海`
    ```
    {detailed light}, {extremely delicate and beautiful}, 1girl, {beautiful detailed eyes}, stars in the eyes, messy floating hair, colored inner hair, starry sky adorns hair, depth of field,
    # 反向
    missing arms,
    ```
    * `采样方法` `DDIM`
    * `迭代步数` `25`
    * `提示词引导系数` `5`
    * `生成`
      * `MeinaHentai`
![](2023-10-25/grid-0050.png)
  * `星之彩`
    ```
    (detailed light), (extremely delicate and beautiful), 1girl, cute face, upper body, two legs, long dress, (beautiful detailed eyes), stars in the eyes, messy floating hair, colored inner hair, starry sky adorns hair, (lots of big colorful bubbles), (pearl:0.9), (galaxy:0.9), depth of field,
    # 反向
    bad face, missing arms, missing legs, more than two legs, (small bubbles:0.72),
    ```
    * `采样方法` `DDIM`
    * `迭代步数` `25`
    * `提示词引导系数` `5`
    * `生成`
      * `MeinaHentai`
![](2023-10-25/grid-0048.png)
  * `花火法基础`
    ```
    (extremely detailed cg unity 8k wallpaper：1.21), (best illustration), (best shadow), (extremely delicate and beautiful), (1girl:1.46), floating, fine details, (bloom), (shine), glinting stars, (best detailed fireworks:1.46), (depth of field:1.33), (hanabi:1.33), beautiful detailed girl, (backlight:1.33), extremely delicate and beautiful girl, (summer long skirt:1.21), (solo:1.33), best details hair, (beautiful detailed water:1.21), night sky, (small breasts:1.33), beautiful detailed sky, beautiful detailed eyes, (arms behind back:1.33), long hair, (dynamic angle:1.33), long skirt,
    # 反向
    inverted mountain, low quality, flowers, grass, distorted mountain, distorted light, low quality light, low quality mountain, low quality illustration, low quality background, polar, bad body, bad proportions, gross proportions,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `50`
    * `提示词引导系数` `4.5`
    * `生成`
      * `MeinaHentai`
![](2023-10-25/grid-0044.png)
      * `Hassaku`
![](2023-10-25/grid-0046.png)
  * `暗鸦法`
    ```
    extremely detailed cg unity 8k, contour deepens for a beautifully detailed glow, (beautiful detailed eyes), (1girl:1.1), (bana:1.21), large top sleeves, floating black ash, beautiful and detailed black, red moon, (black cloud:1.21), (black Wings), black cloudy sky, burning, black dress, black expressionless face, beautiful and detailed white gloves, (crow), bat, (floating black clouds:1.5), white and black hair, long bangs, hair between eyes, black kneehighs, black ribbon, white bowtie, midriff, (half-closed eyes:1.15), (black fog:1.21), red eyes, (black smoke), complex patterns, (Black feathers float in the air:1.21), (arms behind back:1.33),
    # 反向
    (ugly:1.33), (duplicate:1.33), (morbid:1.21), (mutilated:1.21), (tranny:1.33), mutated hands, (poorly drawn hands:1.33), (bad proportions:1.33), extra limbs, cloned face, (disfigured:1.33), (more than 2 nipples:1.33), (missing arms:1.46), (extra legs:1.33), (fused fingers:1.61), (too many fingers:1.61), (unclear eyes:1.33), text font ui, malformed hands, missing limb, (mutated hands and finger:1.5), (mutation poorly drawn:1. 2), malformed mutated, multiple breasts, futa, yaoi, gross proportions, (malformed limbs), (missing legs:1.21), (extra arms:1.33), (fused fingers), (long neck:1.33),
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `50`
    * `提示词引导系数` `4.5`
    * `生成`
      * `MeinaHentai`
![](2023-10-25/grid-0043.png)
  * `万物熔炉`
    ```
    amazing, beautiful detailed eyes,(1girl:1.46), fine detail, depth of field, extremely detailed cg unity 8k wallpaper, (full body:1.61), (cute anime face:1.33), (a girl wearing a black and white taoist robe:1.33), (extremely gorgeous magic style:1.21), (gold and silver lace:1.46), (flowing lace:1.33), (flowing (black:1.21) and white background:1.33), (gorgeous and detailed eyes:1.61), (gorgeous detailed face:1.94), (floating hair:1.21), (pick and dye black hair white:1.33), (flowing transparent black:1.33), (flowing transparent white:1.33), (ink:1.61), (small breasts:1.46), (extremely detailed gorgeous tiara:1.33), (black and white hair:1.33), (black hair stick:1.21), (white hair ornament:1.21), (gold gorgeous necklace:1.21), (flowing hair:1.21), (picture fills canvas:1.33), (the character is in the center of the frame:1.21), (flowing:1.33), (bright pupils:1.21), (melt:1.46), (black and white melt:1.61),
    # 反向
    (ugly:1.33), (duplicate:1.33), (morbid:1.21), (mutilated:1.21), (tranny:1.33), mutated hands, (poorly drawn hands:1.33), (bad proportions:1.33), extra limbs, cloned face, (disfigured:1.33), (more than 2 nipples:1.33) ,(missing arms:1.46), (extra legs:1.33), (fused fingers:1.61), (too many fingers:1.61), (unclear eyes:1.33), text font ui, malformed hands, long neck, missing limb, (mutated hands and finger:1.5), (mutation poorly drawn:1.2), malformed mutated, multiple breasts, futa, yaoi,
    ```
    * `采样方法` `Euler`
    * `迭代步数` `39`
    * `提示词引导系数` `7`
    * `生成`
      * `MeinaMix`
![](2023-10-25/grid-0041.png)
