title: html5图文结构
date: 2015-12-03 23:07:31
tags: html5 前端
categories: 学习笔记
---
## 图上文下结构

### 方式一
``` bash
<div id="got-gridbox">
  <figure>
    <img src="1.png" alt="...">
    <figcaption>Daenerys Targaryen</figcaption>
  </figure>
  <figure>
  <img src="2.png" alt="...">
  <figcaption>Tyrion Lannister</figcaption>
  </figure>
  …
</div>     
```

### 方式二
``` bash
<section>
  <article>
    <img src="1.jpg" alt>
    <h1>Washington D.C. Attacked By Flying Saucers</h1>
    <h2>Dateline Washington D.C.</h2>
    <h3>Frank Bragg reporting</h3>
    <p>The country was brought to a standstill today when flying saucers appeared over the nation’s capital.
  </article>
  <article>
  …
</section>          
```