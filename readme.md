# lazyload-image

## About

Extended HTMLImageElement for lazy image loading as Web Components. Images will be loaded when they are shown.

## Usage

Load `lazyload-image.js` in your HTML.

```html
<script src='lazyload-image.js'></script>
```

Modify your `<img>` elements such as following.

```html
<img is='lazyload-image' src='path/to/your/image.jpg' width='100' height='100'>
```

## Option

### offset

You can specify load offset.

```html
<img is='lazyload-image' src='path/to/your/image.jpg' offset='200' width='100' height='100'>
```

## License

MIT