# html_beautification
This is a tutorial repository for HTML page beautification. You can learn HTML beautification techniques here.

**Since the tutorial was only written in XiaotongCode, it was too rushed and stressful. So if there is something that is not available, please let us know!**
## Text beautification
You can modify the color and background color of the text, for example:

```html
<p><font color="blue">text</font></p>
```

The`<font>`tag is the label that changes the text, of course, you can add the decimal 16 color code after `color=`.

Of course, you need to add the `background-color` to the text, that is, the background-color property, you can use CSS:

```css
p {
  background-color="blue";
}
```

It's very simple, and of course, you can learn deeper beautifications, such as the strokes we'll talk about below.
### Stroke
You need to write the following code in the body part of the CSS:

```css
body {
  text-shadow:-1px 0 #333,
    0 -1px #333,
    1px 0 #fff,
    0 1px #fff;
}
```

**Different lines represent different directions**, you can try it yourself!

_Update line, subsequent content is being prepared!_
