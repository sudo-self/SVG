# <a href="https://svg2.jessejesse.com">SVG scalable Vector Graphic</a>
## Create them with photo software or with SVG web tools  [](https://maketext.io)https://maketext.io
<img width="489" alt="Screenshot 2023-09-04 at 2 48 06 AM" src="https://github.com/sudo-self/SVG/assets/119916323/a7d996b2-bb42-4f0a-9ad1-3e90f628f68f"><br><br>

## Usage

### HTML Image
Using the ```<img />``` element directly in your HTML file.
```
<img src="path/to/icon.svg" alt="icon title" />
```

### Inline HTML 
You can paste the content of the icon file directly into your HTML code to display it on the page using the ```<svg> </svg>``` tag.
```
<body>
 // Add your SVG code here
</body>
```

### CSS 
Instead of using an HTML ```<img />``` element, you can use CSS instead and apply it as a background to any other element.
```
body {
  background-image: url(path/to/icon.svg);
}
```

### SVG as an object
You can also use the ```<object>``` tag to add the SVG to your page
```
<object data="path/to/icon.svg" width="24" height="24"> </object>
```

### Using <iframe>
Keep in mind that using iframe is not recommended, because its hard to maintain
```
<iframe src="path/to/icon.svg"> </iframe>
```

### SVG as embed
Most of the modern browsers have deprecated plugins, so this is not recommended.
```
<embed src="path/to/icon.svg" />
```
