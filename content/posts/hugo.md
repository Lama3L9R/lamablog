---
title: "关于如何在我的博客上添加文章的简单教程"
date: 2024-10-25T10:48:42-07:00
draft: false
tags: ["tutorial"]
---

是的没错，我忘了如何给我的博客添加文章...

主要还是平时写东西太随缘了，其实有很多想写的，就是平时太忙了，想不起来写出来

~~（我才不会告诉你我是沉迷 `DotA` 无法自拔所以才不写的）~~

```
# New post from template (archetypes/default.md)
$ hugo new content/posts/xxx.md

# Dev Server
$ hugo serve

# Build
$ hugo
```

启用的插件以及其预览：

KaTex $\LaTeX$ 
---

Inline Tex: $\vec{F}=\mu mgcos(\theta)\$
```
Inline Tex: $\vec{F}=\mu mgcos(\theta)\$
```

Full size Tex:
$$
\huge{\int uv^{\prime} \mathop{dx} = uv - \int u^{\prime}v \mathop{dx}}
$$

```
$$
\huge{\int uv^{\prime} \mathop{dx} = uv - \int u^{\prime}v \mathop{dx}}
$$
```

Hugo Markdown
---
Hover text (`<abbr>` tag):

<abbr title="GNU is not UNIX">GNU</abbr> is not Unix
```
<abbr title="GNU is not UNIX">GNU</abbr> is not Unix
```

Highlight (`mark` tag):

<mark>GNU</mark> is not Unix
```
<mark>GNU</mark> is not Unix
```

Embedded Youtube player:
{{< youtube hi87-ewkY-w >}}

```
{{</* youtube hi87-ewkY-w */>}}
```

Raw HTML: 
<button onclick="alert('you just clicked me')"> Click me</button>

```
<button onclick="alert('you just clicked me')"> Click me</button>
```