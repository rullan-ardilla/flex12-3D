# 🐿️flex12-3D
1 version
**Flex12-3D** is a modern, minimalistic and flexible 12-column CSS FLEX grid, designed for fast and easy development of responsive web interfaces. ✅The feature is that it takes into account the real distance between columns, and does not emulate the distance through padding.
![Flex12](/deposit/images-flex12-v1.png)

---

## Main advantages Flex12-3D:

- 🔹 **Ease of use:** Intuitive class-based approach for quick grid creation.
- 🔹 **12 columns:** Classic grid, optimal for any type of layout — from simple pages to complex applications.
- 🔹 **Flexibility:** Easily combined with other CSS technologies and adapted to any screen size.
- 🔹 **Real distance between columns:** The feature is that it takes into account the real distance between columns, and does not emulate the distance through padding.
- 🔹 **3D effects:** Since version 2.0, a unique feature — support for easy 3D transformations for modern UI/UX solutions.

---

## Sample for identical columns
![example of an adaptive grid](/deposit/col-3-3-3-3.png)
```html
<section class="row col-3-3-3-3">
  <div class="c-3">c-3</div>
  <div class="c-3">c-3</div>
  <div class="c-3">c-3</div>
  <div class="c-3">c-3</div>
</section>
<style>
.col-3-3-3-3 > .c-3{width: calc(var(--col-3) - var(--gap-3));}
</style> 
```

## Sample code for different columns
![example of an adaptive grid](/deposit/col-2-6-4.png)
```html
<section class="row col-2-6-4">
  <div class="c-2">c-2</div>
  <div class="c-6">c-6</div>
  <div class="c-4">c-4</div>
</section>
<style>
.col-2-6-4  > .c-2{width: calc(var(--col-2) - var(--gap-2));}
.col-2-6-4  > .c-6{width: calc(var(--col-6) - var(--gap-2));}
.col-2-6-4  > .c-4{width: calc(var(--col-4) - var(--gap-2));}
</style> 
```



## Color scheme WEB-HUD/:
![example of an adaptive grid](/deposit/color-palets.png)

## How to use?

Just plug in the CSS (flex-12_v1.css), you are ready to create responsive grids + with 3D effects (from version 2.0).

---

Join, make your code better with **Flex12-3D**! 🚀
```


