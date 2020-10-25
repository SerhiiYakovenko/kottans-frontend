
---
# Responsive wed design
---
##### Responsive Patterns
- [Column drop](https://codepen.io/jesslee0124/pen/YWNVeP)
- [Mostly fluid](https://codepen.io/Fenici/pen/QNPRRw)
- [Layout shifter](https://codepen.io/Fenici/pen/pyBmXg)
- [Off canvas](https://codepen.io/rbardtke/pen/nfkdb)

##### Usefull info

- Setting the viewport
`<meta name="viewport" content="width=device-width, initial-scale=1">`  
[MDN web docs](https://developer.mozilla.org/en-US/docs/Mozilla/Mobile/Viewport_meta_tag)
- Max-width on elements:
```
img, embed,
object, video {
    max-width:100%; 
}
```
- Tap targets:
``` 
nav a, button{ 
    min-height: 48px; min-width: 48px; 
}
```
- Basic media query
`<link rel="stylesheet" media="screen and (min-width: 300px)" href="patterns.css">`
```
@media and (min-width: 301px) and (max-width: 600px) {
  /* styles */
}
```
- Responsive Tables:
  - Hidden column
  - No more columns
  - Contained scrolling
- Fonts - big enough to read, ideal 65 characters per line
