
## Basic image placement

This is the bare bones html image tag that will place an image on your page

```html
<img src="img/foo.jpg">
```

Bootstrap has a bunch of tools for handling images in particaulr use cases. Please consult the [website](https://getbootstrap.com/docs/4.1/content/images/)

In most cases if you are placing an image inside a column the `img-fluid` class will atimaticall scale the image.

```html
<img src="img/foo.jpg" class="img-fluid">
```

Images can be floated using the float class, eg `float-left` and `float-right`

Styling with css will usually be required:

```css
#img-foo{
  padding: 10px;
  height: 400px;
}
```

**Caution!** mixing Bootstrapp css and custom css can lead to unpredictable result.

## Useful links

* [SVG image in CSS](https://css-tricks.com/using-svg/)
* [Dummy image generator](https://dummyimage.com/)