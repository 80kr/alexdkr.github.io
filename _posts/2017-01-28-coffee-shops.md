---
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true

<!--  -->
<!-- tags: data science -->
published: true
---

## Coffee Shops

We've just come across the opportunity to open a coffee shop in NYC!

How can we provide suggestions for locations to place a new coffee shop?

This post details the selection of prime locations for coffee shops in NYC.

## Data

Our team used the following data to produce a list of prime locations for new coffee shops:  

  * MTA turnstile data
  * US census data
  * Google Maps
  * Yelp

![an image alt text]({{ site.baseurl }}/images/1_coffee/0_times_for_coffee.png "Coffee Traffic During the Day")

The following Python Tools  
  * google maps  
  * yelp  

methodology included averages of input demgraphics like high-earners, post-graduate degree holders, and singles


![an image alt text]({{ site.baseurl }}/images/jekyll-logo.png "an image title")






Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.


Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.


This is a demo of all styled elements in Jekyll Now.

[View the markdown used to create this post](https://raw.githubusercontent.com/barryclark/www.jekyllnow.com/gh-pages/_posts/2014-6-19-Markdown-Style-Guide.md).
This is a paragraph, it's surrounded by whitespace. Next up are some headers, they're heavily influenced by GitHub's markdown style.



### Header 3

#### Header 4

A link to [Jekyll Now](http://github.com/barryclark/jekyll-now/). A big ass literal link <http://github.com/barryclark/jekyll-now/>

An image, located within /images

![an image alt text]({{ site.baseurl }}/images/jekyll-logo.png "an image title")

* A bulletted list
- alternative syntax 1
+ alternative syntax 2
  - an indented list item

1. An
2. ordered
3. list

Inline markup styles:

- _italics_
- **bold**
- `code()`

> Blockquote
>> Nested Blockquote

Syntax highlighting can be used with triple backticks, like so:

```javascript
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
```

Use two trailing spaces  
on the right  
to create linebreak tags  

Finally, horizontal lines

----
****

