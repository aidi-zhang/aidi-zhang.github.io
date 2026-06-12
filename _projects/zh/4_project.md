---
layout: page
title: project 4
description: another without an image
img:
importance: 3
category: fun
---

<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width. -->

每个项目都有一个独立的展示页面，支持灵活的三栏图片布局，图片宽度可设为 1/3、2/3 或全宽。

如需为项目卡片设置封面图，只需在 front matter 中添加 img 字段，如下所示：

<!-- To give your project a background in the portfolio page, just add the img tag to the front matter like so: -->

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <!-- Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles. -->
    图片说明示例：左图为穿越隧道的公路，中图为艺术感十足的落叶特写，右图为抓握松针的伐木工人。
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <!-- This image can also have a caption. It's like magic. -->
    这张图片同样可以添加说明文字。
</div>

<!-- You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images. -->

图片行之间也可以插入正文段落，用于介绍项目背景、描述研究过程，再以下一组图片收尾，展示最终成果。


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <!-- You can also have artistically styled 2/3 + 1/3 images, like these. -->
    也可以使用 2/3 + 1/3 的非对称图片布局，如上图所示。
</div>


<!-- The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above: -->

代码非常简洁：将图片包裹在 `<div class="col-sm">` 中，再放入 `<div class="row">` 即可（参见 <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap 栅格系统</a>）。添加 `img-fluid` 使图片自适应，`rounded` 和 `z-depth-1` 分别为图片添加圆角和阴影。上方最后一行图片的代码如下：

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
