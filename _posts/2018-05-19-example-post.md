---
title: Example Post
# Route to this page
# Use ":<param>" to place the property's value in the route.
# Ex: /post/:year/:month/:day/title --> /post/2018/05/20/example-post
# Default is: #/:categories/:year/:month/:day/:title:output_ext
permalink: /post/:title
# Template for this page
# Layouts may be nested (ex: the post layout inherits the default layout).
layout: post
# These properties are user-defined and we can reference them in the layout.
# ----------
# Post thumbnail (an image we can reference this post by on the main page)
# Don't need the whole absolute path; this is taken care of in the post layout.
thumbnail: "images/sample-image.jpg"
# Author (see _data/authors.yml for author properties)
author: john_doe
# Place tags in array
tags: [tutorial, example]
---

<!-- "Capture" the content between these tags and assign it to a "lead_content"
variable. We can place it in the desired location inside the post template by
referencing "lead_content." -->
{% capture lead_content %}
### This is an example post for SlapdashLogic running on Jekyll.

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.
{% endcapture %}

# Here's a title

## Here's a smaller title

> Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote. Here is a block quote.

*This is a pretty good quote, isn't it?*

### A smaller section

Here's why I like that quote:
1. It's mine.
2. I wrote it.
3. It's mine (really)

How about a link to [Google](http://www.google.com)

**And a picture?**

![Image](/images/thumbs/liberty.jpg)
