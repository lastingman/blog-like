---
title: CSS Grid Justification 与 Alignment
description: ' '
date: 2019-04-09 12:13:17
categories:
  - notes
tags:
  - css
  - grid
---

## 案例模板

<p class="codepen" data-height="409" data-theme-id="0" data-default-tab="css,result" data-user="Lastingman" data-slug-hash="pBNQeo" style="height: 409px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid black; margin: 1em 0; padding: 1em;" data-pen-title="grid sample">
  <span>See the Pen <a href="https://codepen.io/Lastingman/pen/pBNQeo/">
  grid sample</a> by Like Zheng (<a href="https://codepen.io/Lastingman">@Lastingman</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

### justify-items

`justify-items: start/end/center`

```css
.container {
  /* ... */
  justify-items: center;
}
```

![justify-items: center](https://i.imgur.com/wG0Am9j.png)

### align-items

`align-items: start/end/center`

```css
.container {
  /* ... */
  align-items: center;
}
```

![align-items: center](https://i.imgur.com/LLGuCjP.png)

### justify-self

```html
<div class="container">
  <div class="item" style="justify-self: center;"></div>
  <div class="item"></div>
  <div class="item"></div>
  <div class="item" style="justify-self: end;"></div>
  <div class="item"></div>
  <div class="item"></div>
</div>
```

![justify-self](https://i.imgur.com/8LQiWmM.png)

### align-self

```html
<div class="container">
  <div class="item" style="align-self: center;"></div>
  <div class="item" style="align-self: end;"></div>
  <div class="item"></div>
  <div class="item"></div>
  <div class="item"></div>
  <div class="item"></div>
</div>
```

![align-self](https://i.imgur.com/LiL8uw2.png)

## 案例模板 2

`justify-content`和`align-content`用以下模板来展示。

<p class="codepen" data-height="424" data-theme-id="0" data-default-tab="css,result" data-user="Lastingman" data-slug-hash="XQNopZ" style="height: 424px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid black; margin: 1em 0; padding: 1em;" data-pen-title="grid sample 2">
  <span>See the Pen <a href="https://codepen.io/Lastingman/pen/XQNopZ/">
  grid sample 2</a> by Like Zheng (<a href="https://codepen.io/Lastingman">@Lastingman</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

### justify-content

`justify-content: start/end/center/space-around/space-between/space-evenly`

```css
.container {
  /* ... */
  justify-content: center;
}
```

![justify-content: center](https://i.imgur.com/GqSpqmv.png)

### align-content

```css
.container {
  /* ... */
  align-content: center;
}
```

![align-content: center](https://i.imgur.com/PyZiaF1.png)

## Change log

- 2019-4-9 create
