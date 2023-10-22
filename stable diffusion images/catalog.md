### `Stable Diffusion WebUI`附录
* [Stable Diffusion WebUI](/stable%20diffusion%20web%20ui.md).md [[github.com]](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/dev)
* `Models`
  * `Rabbit` [[civitai.com]](https://civitai.com/models/121696)
  * `Flat-2D Animerge` [[civitai.com]](https://civitai.com/models/35960)
  * `MeinaHentai` [[civitai.com]](https://civitai.com/models/12606)
* `通用起手式`
  ```
  nsfw, pantyhose,
  (masterpiece:1.2), (best quality:1.3), (ultra-detailed:1.2), (illustration:1.2), (disheveled hair:1.2),
  <lora:add_detail:2>,

  # 反例
  negative_hand-neg, verybadimagenegative_v1.3, EasyNegativeV2,
  long body, lowres, bad anatomy, bad hands, missing finger, extra digits, fewer digits, cropped, worst quality, low quality,
  ```
* `元素魔法目录`
  * `水魔法`
    ```
    (frills:1.2), (1girl), (solo), dynamic angle, big top sleeves, floating, beautiful detailed sky, on beautiful detailed water, beautiful detailed eyes, overexposure, (fist), expressionless, blunt side bangs, hair between eyes, ribbon, bowtie, buttons, bare shoulders, (small breasts:1.3), detailed wet clothes, blank stare, pleated skirt, flower,
    # 反向提示词
    text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry, missing arms, long neck, humpbacked,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `30`
    * `提示词引导系数` `5.5`
    * `生成`
      * `MeinaHentai`
        ![](grid-0100.png)
      * `Flat-2D Animerge`
        ![](grid-0101.png)
  * `空间法`
    ```
    (floating hair:1.2), (chromatic aberration:1.2), (caustic:1.2), lens flare, (portrait:1.2), (1girl), (solo:1.2), cute face, (hidden hands:1.2), asymmetrical bangs, (beautiful detailed eyes), eyeshadow, (huge clocks:1.2), (glass strip:1.2), (floating glass fragments), (colorful refraction:1.2), (beautiful detailed sky), (dark intense shadows:1.2), (cinematic lighting:1.2), (overexposure:1.2), (expressionless), blank stare, big top sleeves, (frills:1.2), hair ornament, ribbon, bowtie, buttons, (small breasts:1.3), pleated skirt, (sharp focus:1.2), (extremely detailed:1.2), colorful, hdr,
    # 反向提示词
    text, error, standard quality, jpeg artifacts, signature, watermark, username, blurry,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `28`
    * `提示词引导系数` `4.5`
    * `生成`
      * `MeinaHentai`
        ![](grid-0102.png)
      * `Flat-2D Animerge`
        ![](grid-0103.png)
  * `冰魔法`
    ```
    (beautifuldetailed girl), beautiful detailed glow, detailed ice, beautiful detailed water, (beautiful detailed eyes), expressionless, (floating palace), azure hair, long bangs, hair between eyes, (sky blue dress), black ribbon, white bowtie, midriff, (half-closed eyes), big forehead, blank stare, flower, large top sleeves,
    # 反向提示词
    text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry, missing arms, large breasts,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `27`
    * `提示词引导系数` `7`
    * `生成`
      * `MeinaHentai`
        ![](grid-0104.png)
      * `Flat-2D Animerge`
        ![](grid-0105.png)
  * `核爆法`
    ```
    (beautiful detailed girl), beautiful detailed glow, (flames of war:1.2), (nuclear explosion behide:1.3), rain, detailed lighting, detailed water, (beautiful detailed eyes), expressionless, palace, azure hair, disheveled hair, long bangs, hair between eyes, (white grey dress), black ribbon, white bowtie, midriff, big forehead, blank stare, flower, long sleeves,
    # 反向提示词
    text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry, missing arms, large breasts,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `28`
    * `提示词引导系数` `7`
    * `生成`
      * `MeinaHentai`
        ![](grid-0106.png)
      * `Flat-2D Animerge`
        ![](grid-0107.png)
  * `风魔法`
    ```
    (1girl), (solo), (an extremely delicate and beautiful:1.2), little girl, (beautiful detailed sky:1.2), beautiful detailed eyes, blunt side bangs, hair between eyes, ribbon, bowtie, buttons, bare shoulders, (small breasts), blank stare, pleated skirt, close to viewer, (breeze:1.2), flying splash, falling petals, wind,
    # 反向提示词
    text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry, missing arms, long neck, humpbacked, shadow,
    ```
    * `采样方法` `Euler`
    * `迭代步数` `50`
    * `提示词引导系数` `5.5`
    * `生成`
      * `MeinaHentai`
        ![](grid-0108.png)
      * `Flat-2D Animerge`
        ![](grid-0109.png)
  * `流沙法`
    ```
    cinematic lighting, (extremely detailed eyes and face:1.2), (ink:1.4), depth of field,(extremely detailed:1.2), (watercolor:1.2), (anime face:1.2), (dramatic angle:1.3), medium breast, (8k wallpaper), (bright eyes:1.2), (looking at viewer ), (an detailed  organdie dress), (very close to viewer:1.6), (sleepy:1.2), (surrounded by heavy floating sand flow and floating sharp stones:1.7), (messy long hair:1.6), (veil:1.4), focus on face, (upper body), (bare shoulders), (1girl:1.4), (golden bracelet), (long yarn), (sunset:1.2), lens flare, light leaks, (detailed beautiful desert with cactus:1.2), medium wind, (detailed beautiful sky),
    # 反向提示词
    text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name, bad feet, skeleton girl,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `27`
    * `提示词引导系数` `5.5`
    * `生成`
      * `MeinaHentai`
        ![](grid-0110.png)
      * `Flat-2D Animerge`
        ![](grid-0111.png)
  * `白骨法`
    ```
    cinematic lighting, (single human girl:1.2), (upper body:1.6), (extremely detailed eyes and face:1.2), (church:1.2), (annoyed:1.2), (ink:1.2), depth of field, (frown:1.2), (anime face:1.2), (skull on dress), (yokozuwari:1.3), (detailed skeleton church:1.2), (beautiful detailed black gothic empire waist dress:1.3), (dramatic angle:1.3), medium breasts, (8k wallpaper), (bright eyes:1.2), (looking at viewer), (close to viewer:1.2),(messy_long_hair:1.6), (1girl:1.6), lens flare, light leaks,
    # 反向提示词
    text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name, bad feet, skeleton girl,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `27`
    * `提示词引导系数` `6.5`
    * `生成`
      * `MeinaHentai`
        ![](grid-0112.png)
      * `Flat-2D Animerge`
        ![](grid-0113.png)
  * `星空法`
    ```
    (disheveled hair:1.2), beautiful detailed eyes, (1girl:1.2), (solo), dynamic angle, dark magician girl, (black kneehighs), (starry tornado:1.4), starry nebula, (frills:1.2), beautiful detailed sky, beautiful detailed eyes, evil smile, expressionless, hair between eyes, white hair, pleated skirt,
    # 反向提示词
    normal quality, jpeg artifacts, signature, watermark, username, blurry, bad hands, missing arms,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `50`
    * `提示词引导系数` `6`
    * `生成`
      * `MeinaHentai`
        ![](grid-0114.png)
      * `Flat-2D Animerge`
        ![](grid-0115.png)
  * `机凯种`
    ```
    (flat chest best quality), (highres), solo, flat chest, a girl inside the church with white hair and blue pupil surrounded by (many) glowing (feathers) in cold face, detailed face, night with bright colorful lights with richly layered clouds and clouded moon in the detailed sky, (a lot of glowing particles), high ponytail, mecha clothes, robot girl, cool movement, silver bodysuit, (filigree), delicate and (intricate) hair, (silver:1.2)and (broken) body, blue streaked hair, full body, depth of field, sitting on a (blue star),
    # 反向提示词
    bad leg, bad hands, text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad feet, artist name, bad body, bad proportions, optical illusion,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `28`
    * `提示词引导系数` `12`
    * `生成`
      * `MeinaHentai`
        ![](grid-0116.png)
      * `Flat-2D Animerge`
        ![](grid-0117.png)
  * `森林冰`
    ```
    (ink:1.3), (watercolor:1.2), world masterpiece theater, depth of field, (1girl), anime face, medium breasts, floating, beautiful detailed sky, looking at viewer, an detailed organdie dress, very close to viewer, bare shoulders, golden bracelet, focus on face, messy long hair, veil, upper body, lens flare, light leaks, detailed beautiful snow forest with trees, spirit, grey hair, white clothes, (snowflakes:1.2), floating sand flow, navel, (beautiful detailed eyes), (8k wallpaper),
    # 反向提示词
    text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry, missing arms, long neck, humpbacked, glasses,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `30`
    * `提示词引导系数` `7`
    * `生成`
      * `MeinaHentai`
        ![](grid-0120.png)
      * `Flat-2D Animerge`
        ![](grid-0121.png)
  * `幻之时`
    ```
    (1girl), amazing, beautiful detailed eyes, finely detail, depth of field, extremely detailed cg, original, extremely detailed wallpaper, loli, white hair, magic circle, cat ears, long hair, yellow eyes, wand, pentagram, clock,
    # 反向提示词
    text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `20`
    * `提示词引导系数` `7`
    * `生成`
      * `MeinaHentai`
        ![](grid-0122.png)
      * `Flat-2D Animerge`
        ![](grid-0123.png)
  * `圣光法`
    ```
    (detailed light), (an extremely delicate and beautiful:1.2), (beautiful detailed eyes), (sunlight), (angel), solo, young girls, dynamic angle, floating, bare shoulders, looking at viewer, wings, arms up, halo, floating white silk, (holy light) ,just like silver stars imploding we absorb the light of day,
    # 反向提示词
    text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry,missing arms, large breasts,
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `36`
    * `提示词引导系数` `7`
    * `生成`
      * `MeinaHentai`
        ![](grid-0124.png)
  * `苇名法`
    ```
    dramatic shadow, ray tracing, (beautiful detailed dark midnight sky:1.3), (yellow full moon:1.4), (holding wine gourd), (surrounded by floating sakura:1.6), dramatic angle, (leaning on huge stone), (bareshoulders:1.3), (very close to viewer:1.4), (tipsy:1.3), (sleepy:1.3), (far from viewer:1.2), (extremely beautiful detailed anime face and eyes:1.3),(1girl:1.7), (open hakama:1.4), (samurai:1.2), (ink), depth of field, (beautiful detailed pampas grass field:1.6), watercolor, (upper body:1.2), medium breasts, (bright eyes), (messy white long hair:1.2),
    # 反向提示词
    normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name, bad feet, more than 1 moon,
    ```
    * `采样方法` `DPM++ 2M Karras`
    * `迭代步数` `20`
    * `提示词引导系数` `7`
    * `生成`
      * `MeinaHentai`
        ![Alt text](grid-0125.png)
  * `自然法`
    ```
    (super fine illustration, beautiful and delicate water), (the finest grass:1.2), (beautiful eyes), very delicate light, perfect and delicate limbs, nature, painting, water spray,(fine luminescence, very fine 8k cg wallpaper), lavender eyes, pink pupils, whole body, white hair, bright eyes, (an extremely delicate and beautiful girl:1.2), (1girl:1.2), medium bust, dynamic angle, (white dress with gold decoration), (long hair flowing with the wind, beautiful hair ornaments, delicate wet skirt, breeze, long hair between eyes), wrinkled skirt, (staring blankly, lovely big eyes), messy hair, payot, lateral braid, (tulle lace white skirt), flowers and grass meadow, near the water edge, (sunset, starry sky in a circle), randomly distributed clouds, (river:1.3), splashing water, falling petals,
    # 反向提示词
    multiple breasts, (mutated hands and fingers:1.5), (long body:1.3), (mutation, poorly drawn:1.2), multi foot, (Multifold), Multi fingering, colored sclera, monster girl, black hands, greyscale, the background is incoherent, more than 2 thighs, huge thighs, huge calf, fused hand, missing hand, disappearing arms, disappearing thigh, disappearing calf, disappearing legs, fused fingers, one hand with more than 5 fingers, one hand with less than 5 fingers, bad asshole, fused asshole, missing asshole, bad anus, bad pussy, bad crotch, bad crotch seam, fused anus, fused pussy, (abnormal eye proportion), (abnormal hands), (abnormal legs), (abnormal feet abnormal fingers), (sharp face),
    ```
    * `采样方法` `Euler a`
    * `迭代步数` `30`
    * `提示词引导系数` `4`
    * `生成`
      * `MeinaHentai`
        ![](grid-0126.png)
  * `冰系改`
    ```
    (beautiful detailed girl), beautiful detailed glow, detailed ice, beautiful detailed water, (beautiful detailed eyes), expressionless, beautiful detailed white gloves, (floating palace:1.2), azure hair, disheveled hair, long bangs, hair between eyes, (sky blue dress), black ribbon, white bowtie, midriff, (half-closed eyes), big forehead, blank stare, flower, large top sleeves, (ice crystal texture wings:1.3), (iridescence and rainbow hair:1.7), (detailed cute anime face:1.6), (loli), (watercolor (medium):1.2),
    # 反向提示词
    (ugly), (duplicate), (morbid), (mutilated), (tranny), mutated hands, (poorly drawn hands), blurry, (bad proportions), extra limbs, cloned face, (disfigured), (more than 2 nipples), (missing arms:1.2), (extra legs), mutated hands, (fused fingers:1.2), (too many fingers:1.2), (unclear eyes), text, error, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad,
    ```
    * `采样方法` `DPM++ 2M Karras`
    * `迭代步数` `20`
    * `提示词引导系数` `7`
    * `生成`
      * `MeinaHentai`
        ![](grid-0128.png)