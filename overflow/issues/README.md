# Issues

## HTML & CSS

1. Не отрабатыват правило color

В файле `owerflow/baseCss/index.html` не отрабатыват правило `color` для элемента `p.text` 

```html
<div class="box_text">

    <!-- ... -->

    <p id="text">Text 2</p>
    
    <!-- ...  -->

</div>
```

```css
.text {
    border: 30px solid #aaa;
    padding: 30px 10px 5px 0;
    margin: 30px;
    float: right;
    color:red;
}
```

> У `<p>` указан `id="text"`, а ты обрашаешься к классу `.text`

---

2. 
