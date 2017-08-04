# adwaita-icon

[![Build Status](https://travis-ci.org/shgysk8zer0/adwaita-icons.svg?branch=master)](https://travis-ci.org/shgysk8zer0/adwaita-icons)

A copy of [adwaita-icon-theme](https://github.com/GNOME/adwaita-icon-theme) as seen in the Gnome Project

![Sample of icons](https://i.imgur.com/c1hLkNj.png)

This contains optimized SVG icons contained in [`Adwaita/scalable`](https://github.com/GNOME/adwaita-icon-theme/tree/master/Adwaita/scalable),
and is primarily intended to be used in `<symbol>`s.

## Helpful links
- [Original Adwaita icons](https://github.com/GNOME/adwaita-icon-theme)
- [Issues](https://shgysk8zer0/adwaita-icons/issues)
- About [`<symbol>`s & `<use>`](https://css-tricks.com/svg-sprites-use-better-icon-fonts/)
- [Contributing guidelines](./docs/CONTRIBUTING.md)
- [Inkscape](https://inkscape.org/)

## Example usage
<table>
<caption>Contents of <code>icons.csv</code></caption>
<thead>
<tr><th>ID</th><th>Path</th></tr>
</thead>
<tbody>
<tr><td>user-home</td><td>places/user-home.svg</td></tr>
<tr><td>send-to</td><td>places/send-to.svg</td></tr>
<tr><td>...</td><td>...</td></tr>
</tbody>
</table>

```html
<a href="/home">
    <svg width="32" height="32"><use xlink:href="/img/icons.svg#user-home" /></svg>
</a>
```

## Inkscape output settings
- ![Output format: "Optimized SVG (*.svg)"](http://i.imgur.com/SC5VDpi.png)
- ![Options tab](http://i.imgur.com/NcpY8GZ.png)
- ![SVG Output tab](http://i.imgur.com/sjyi8iQ.png)
- ![IDs tab](http://i.imgur.com/Lk9VTr4.png)
