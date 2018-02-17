# How to Use Markdown
****
Heading
========
# Heading1
## Heading 2
### Heading3
#### Heading4
##### Heading5
###### Heading6

***
**Bold** and *Italic*
===============
**Bold**
*Italic*
***

List
===
### Disordered
- list1
	- list1.1
		- list 1.1.1
* list2
+ list3
### Ordered
1. l1
2. l2
1. l3
***

Website
===
[Baidu](http://www.google.com)

[http://wowubuntu.com/markdown/#overview](http://wowubuntu.com/markdown/#overview)
***
Image
===
![](http://www.legobatman.com/assets/media/global/header/batwink-loop.gif)

![Batman](https://lc-www-live-s.legocdn.com/r/www/r/catalogs/-/media/catalogs/characters/dimensions/mugshot%20december%202016/71200_71170-71174_1to1_mf_mugshot_batman_336.png?l.r2=-1434101541)

![][id]

[id]: https://www.latex-project.org/img/latex-project-logo.svg


***
Video Link with Cover
===
[![](http://is1.mzstatic.com/image/thumb/Purple128/v4/b5/60/47/b56047ac-ced2-0691-6d11-b0e903ce1ea9/source/1200x630bb.jpg)](https://www.youtube.com/watch?v=MYSnza2zcGg)

***
Citation
===
> Markdown 的目标是实现「易读易写」。
可读性，无论如何，都是最重要的。一份使用 Markdown 格式撰写的文件应该可以直接以纯文本发布，并且看起来不会像是由许多标签或是格式指令所构成。Markdown 语法受到一些既有 text-to-HTML 格式的影响，包括 [Setext](http://docutils.sourceforge.net/mirror/setext.html)、[atx](http://www.aaronsw.com/2002/atx/)、[Textile](http://textism.com/tools/textile/)、[reStructuredText](http://docutils.sourceforge.net/rst.html)、[Grutatext](http://www.triptico.com/software/grutatxt.html) 和 [EtText](http://ettext.taint.org/doc/)，而最大灵感来源其实是纯文本电子邮件的格式。

>在芸芸众生的人海里
>你敢否与世隔绝
>独善其身 
>任周围的人们闹腾
>你却漠不关心
>冷落
>孤寂
>像一朵花在荒凉的沙漠里
>不愿向着微风吐馨


***

Code
===
`printf("Hello World!\n");`

```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(-np.pi*2,np.pi*2,1000)
y = np.sin(x)+np.tan(x)*np.cos(x)
plt.plot(x,y,'k-')
plt.show()
```
***
Table
===
|Voltage [v] | Current [A] | Power [w] |
| ---------- | :--------: | ------:|
| 1 | 1 | 1|
|2|2|4|
| default left aligned|centered|right-aligned|




