---
layout: page
title:  "Tests for the translator"
date:   2000-01-01 00:00:00
categories: jekyll update
excerpt: this is just some tests to see if I can get the translator to work better
---
# Tests for the translator!

This is a paragraph, it's surrounded by whitespace. Next up are some headers, they're heavily influenced by GitHub's markdown style.
# Header 1 (Reserved for post/page titles)
## Header 2

### Header 3

#### Header 4
 
A link to [homepage](https://b311a01.github.io/). A big literal link <https://b311a01.github.io/>
  
An image, located within /images

![Image]({{ site.baseurl }}/assets/images/lol.gif){:width="50%"}

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
 
Syntax highlighting can be used by wrapping your code in a liquid tag like so:

{{ "{% highlight javascript " }}%}  
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{{ "{% endhighlight " }}%}  

creates...

{% highlight javascript %}
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{% endhighlight %}
 
Use two trailing spaces  
on the right  
to create linebreak tags  
 
Finally, horizontal lines
 
----
****