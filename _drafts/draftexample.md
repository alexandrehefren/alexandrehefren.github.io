---
title: "My draft test"
---

Note that it does not require the standard file format name.

 {% capture mynotice %}

**Extended notice box**:

- You can include lists

* and even fenced code blocks:::

```html   %% should be ``` %%

<html>

<body>Some body.<body>

</html>
```
{% endcapture %}

<div class="notice--info">{{ mynotice | markdownify }}</div>
