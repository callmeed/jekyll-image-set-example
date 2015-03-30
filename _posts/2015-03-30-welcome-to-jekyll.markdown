---
layout: post
title:  "Welcome to Jekyll Image Set"
date:   2015-03-30 15:09:00
categories: jekyll update
---
[This plugin][jekyll-is] takes a dir (generally a subdirectory of your images folder), gets all the images from it, and creates HTML image and container tags.

Useful for creating an image gallery and the like.

Example
---

{% image_set images/example-gallery %}

Usage
---

* Create a directory (or sub-directory) and place your images there. You need a unique sub-directory for each gallery. 
* Insert the following tag to show your directory (changing it to your dir name of course): 

{% raw %}
<code>{% image_set images/example-gallery %}</code>
{% endraw %}

* See the comments of image_set.rb for additional options such as specifying the HTML wrap tags. 
* Style your gallery however you'd like. There are some example styles in _sass/_gallery-styles.scss


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
[jekyll-is]: https://github.com/callmeed/jekyll-image-set