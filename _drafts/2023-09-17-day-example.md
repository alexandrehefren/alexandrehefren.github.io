---
permalink:
layout: single
title: An Obsidian example
toc: true
toc_label: "Content"
# toc_icon: "cog"
toc_sticky: true 

excerpt: "Is that a first test"
header:
  teaser: /images/photos/AHVJ5357.jpg
#     og_image:  
#     overlay_image: /images/photos/AHVJ5357-2.jpg
#     overlay_filter: 0.5 # same as add an opacity of 0.5 to a black background.rgba: rgba(255, 0, 0, 0.5)
#   # overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
#     caption: ""
#     overlay_color: "#333"
#     actions:                        #Can use multiple action button links
#       - label: "More Info"
#         url: "https://unsplash.com"

# classes: wide
category: dailynotes
date: 17/09/2023
last_modified_at: 18/09/2023
tags:
  - test
  - jekyll
search: true  
author_profile: true
read_time: true
comments: true
---


![]()
_This is Part of my test._
{: .notice--primary}
&nbsp;
&nbsp;

_This is Part of my test._
{: .notice--warning}

_This is Part of my test._
{: .notice--danger}

_This is Part of my test._
{: .notice--focus}

_This is Part of my test._
{: .notice--history}

_This is Part of my test._
{: .notice--hint}

_This is Part of my test._
{: .notice--success}
_This is Part of my test._
{: .notice--info}
_This is Part of my test._
{: .notice--example}









THIS `test` for markdown ".md".

The `highlight color` is not dark enough.

`This is one backtick` and this is normal text without backticks.

``These are two backticks ``

``` These are three backticks```

<code>Lorem ipsum</code>


Yesterday: [[16-09-2023]]  - Tomorrow: [[18-09-2023]]
____
> [!quote] 
> What I cannot **create**, I do not understand
---
# Morning
[[Mathematical Induction]]



[Mathematical induction](https://en.wikipedia.org/wiki/Mathematical_induction)



## Comments

```python
def funct(x,a)
  return x + a
```

# Note
Note: This is a callout. {: .notice--info} {: .text-justify}

<i class="far fa-sticky-note"></i> **Tip:**  This is a callout.
{: .notice--info}
{: .text-justify}


See: **This week** 
[[W37-2023]]

## Today's links already created:
```dataview
LIST 
from outgoing([[]])
where length(file.tags) !=0
```

Today's links to be created:
```dataview
LIST 
from outgoing([[]])
where !file.tags
```

> [!info] Files modified **today**
> ```dataview
table problem, topic, file.mday
from "/"
WHERE file.mday = date("2023-09-17")
sort file.mtime desc
limit 11

# This month so far...

```dataview
table rating, feeling, urgency
from "Calendar Notes"
where contains(date, "09/2023")
sort rating desc
```
>Note: try to implement sum(rating)/1length(rating) AS "average"

ere length(file.tags) !=0


# This month so far...

``` python
dataview
table rating, feeling, urgency
from "Calendar Notes"
where contains(date, "09/2023")
sort rating desc
```
