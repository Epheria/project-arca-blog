---
layout: post
title:  "Project Arca"
description: 
date: 2024-07-15 09:29:20 +0700
tag: "project"
categories: project
project_id: proj_01
usemathjax: true
img: "/posts/images/project/arcathumb.png"
---

<figure>
    <img class="title-image" src="{{site.image_location}}/project/projectarcathumbnail.png" alt="title img">
</figure>

Below is an example of maths using mathjax. 

Any page needing maths should start with the frontmatter:
{% highlight markdown %}
usemathjax: true
{% endhighlight %}

$$ 
\begin{align*}
y = y(x,t) &= A e^{i\theta} \\
&= A (\cos \theta + i \sin \theta) \\
&= A (\cos(kx - \omega t) + i \sin(kx - \omega t)) \\
&= A\cos(kx - \omega t) + i A\sin(kx - \omega t)  \\
&= A\cos \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big) + i A\sin \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big)  \\
&= A\cos \frac{2\pi}{\lambda} (x - v t) + i A\sin \frac{2\pi}{\lambda} (x - v t)
\end{align*}
$$

Inline maths can be written with the `\\(` and `\\)` characters, producing inline maths
such as \\(\delta(t) \xrightarrow{\mathscr{F}} 1\\).

The above is accomplished with thanks to [Alan Duan](https://alanduan.me/random/mathjax/) and [Zichen Vincent Zhang](https://webdocs.cs.ualberta.ca/~zichen2/blog/coding/setup/2019/02/17/how-to-add-mathjax-support-to-jekyll.html.).
