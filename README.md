## Tech icons set

![Icon set preview](http://i.cubeupload.com/HnFzZG.png)

> A collection of SVG icons representing programming languages, frameworks, technologies and skills, ready-built as a web font

View the full set [here](http://workshape.github.io/tech-icons/index.html)

#### Download

You can use the ready-built webfont by copying the build in the `dist` folder over to your project and importing `icons.css` into your HTML.

#### Use

To create an icon in your markup, create an `i` tag with classname `icon-tech-[ icon_name ]`

For example:

```html
<i class='icon-tech-python'></i>
```

#### Build

You can add or modify SVG icons to the projects by copying them in the `icons` directory - Note: SVGS must be single-color and sized 48x48px.

You can rebuild the codebase by running

```
npm run build
```

The `dist` directory gets built using [icon-font-generator](https://github.com/Workshape/icon-font-generator)

#### Contribute

We'd love to add more icons to the set - pull requests are welcome!
