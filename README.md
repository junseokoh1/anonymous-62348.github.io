## OUR-GAN demo

### Abstract
We propose OUR-GAN, the first one-shot ultra-high-resolution (UHR) image synthesis framework that generates non-repetitive images with 4K or higher resolution from a single training image. OUR-GAN generates a visually coherent image at low resolution and then gradually increases the resolution by super-resolution. Since OUR-GAN learns from a real UHR image, it can synthesize large-scale shapes with fine details while maintaining long-range coherence, which is difficult with conventional generative models that generate large images based on the patch distribution learned from relatively small images. OUR-GAN applies seamless subregion-wise super-resolution that synthesizes 4k or higher UHR images with limited memory preventing discontinuity at the boundary. Additionally, OUR-GAN improves diversity and visual coherence by adding vertical positional embeddings to the feature maps. In experiments on the ST4K and RAISE datasets, OUR-GAN exhibited improved fidelity, visual coherency, and diversity compared with existing methods. The synthesized images are presented at https://anonymous-62348.github.io.
<br>
<br>

### 8K image synthesized by OUR-GAN
[![8K](/assets/images/8k_stonehenge.jpg)](/assets/images/8k_stonehenge.jpg)
<br>
<br>

### 16K image synthesized by OUR-GAN
Note that we train OUR-GAN on the 4K resolution image.
OUR-GAN can synthesize Ultra-high-resolution images larger than training images.
We upscaled the synthesized 4K image to a 16K image using OUR-GAN trained on a 4k image.
![16K](/assets/images/16k_stonehenge.jpg)
<br>
<br>

### 4K scenery images synthesized by OUR-GAN
OUR-GAN successfully synthesized high-quality non-repetitive images with visually coherent shapes with fine details.

| ![4K_scenery_0_0](/assets/images/4K/11000_0.png) | ![4K_scenery_0_1](/assets/images/4K/11000_17.png) |
|---|---|
| ![4K_scenery_1_0](/assets/images/4K/11015_17.png) | ![4K_scenery_1_1](/assets/images/4K/11015_28.png) |
| ![4K_scenery_2_0](/assets/images/4K/11021_0.png) | ![4K_scenery_2_1](/assets/images/4K/11021_18.png) |
| ![4K_scenery_3_0](/assets/images/4K/11013_44.png) | ![4K_scenery_3_1](/assets/images/4K/11013_46.png) |

<br>

### 4K texture images synthesized by OUR-GAN
OUR-GAN successfully synthesized high-quality texture images with diverse patterns.

| ![4K_texture_0_0](/assets/images/4K/21000_52.png) | ![4K_texture_0_1](/assets/images/4K/21000_66.png) |
|---|---|
| ![4K_texture_1_0](/assets/images/4K/21022_52.png) | ![4K_texture_1_1](/assets/images/4K/21022_83.png) |

<!-- You can use the [editor on GitHub](https://github.com/anonymous-62348/anonymous-62348.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/anonymous-62348/anonymous-62348.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
 -->
