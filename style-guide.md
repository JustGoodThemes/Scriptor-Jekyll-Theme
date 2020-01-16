---
layout: page
title: Style Guide
description: This is a style guide of the Scriptor Jekyll theme
---

This is a pragraph. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enim in turpis pulvinar facilisis. Ut felis.

# Heading 1

**Quisque facilisis erat a dui**. Nam malesuada ornare dolor. Cras gravida, diam sit amet rhoncus ornare, erat elit consectetuer erat, id egestas pede nibh eget odio. Proin tincidunt, velit vel porta elementum, magna diam molestie sapien, non aliquet massa pede eu diam. Aliquam iaculis. Fusce et ipsum et nulla tristique facilisis.

## Heading 2

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero.

### Heading 3

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero.

#### Heading 4

Quisque facilisis erat a dui. Nam malesuada ornare dolor. Cras gravida, diam sit amet rhoncus ornare, erat elit consectetuer erat, id egestas pede nibh eget odio. Proin tincidunt, velit vel porta elementum, magna diam molestie sapien, non aliquet massa pede eu diam. Aliquam iaculis.

##### Heading 5

Curabitur pellentesque facilisis orci, ut rhoncus nulla scelerisque ac. Integer in magna vel justo venenatis ornare vitae vel sem.

###### Heading 6

Nulla tempus tortor nec nunc volutpat commodo. Vivamus efficitur imperdiet velit sagittis pellentesque. In fringilla dui nec dolor sollicitudin, et scelerisque elit pellentesque. Integer vestibulum viverra sem, vel ornare nibh. Proin lobortis elit nunc, ut consequat elit vulputate sit amet.

## Emphasis

**This is bold text**

*This is italic text*

~~Strikethrough~~

## Links

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

## Quoting

>“Creativity is allowing yourself to make mistakes. Design is knowing which ones to keep.”

Lorem ipsum dolor sit amet, `consectetuer adipiscing` elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero.

***

## Code Blocks

```css
#header h1 { 
  color: #fff;
  margin-bottom: 1.5em; 
}

.author-avatar {
  border-radius: 5px;
  display: block;
  height: 60px;   
  margin-right: 30px;
  width: 60px;
}
```

```javascript
// Simple map
var map;
function initMap() {
  map = new google.maps.Map(document.getElementById('map'), {
    center: {lat: -34.397, lng: 150.644},
    zoom: 8
  });
}
```

```json
{"menu": {
  "id": "file",
  "value": "File",
  "popup": {
    "menuitem": [
      {"value": "New", "onclick": "CreateNewDoc()"},
      {"value": "Open", "onclick": "OpenDoc()"},
      {"value": "Close", "onclick": "CloseDoc()"}
    ]
  }
}}
```

```yml
sass:
  input_file: sass/main.scss.njk
  output_file: assets/css/main.css
  indentWidth: 4
  outputStyle: nested
  precision: 10
```

```
No language indicated, so no syntax highlighting. 
```

Inline `code` has `back-ticks around` it.

## Videos

<iframe src="https://player.vimeo.com/video/153339497?byline=0" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

[Terraforming](https://vimeo.com/153339497) from [Studio Swine](https://vimeo.com/studioswine) on [Vimeo](https://vimeo.com)

## Full Width Image

Images work too! Already know the URL of the image you want to include in your article? Simply paste it in like this to make it show up:

{% include image_full.html imageurl="/images/apple-watch-in-car.jpg" title="Apple" caption="This is the caption" %}

Lorem ipsum dolor sit amet, `consectetuer adipiscing` elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero.

## Regular Image

{% include image_caption.html imageurl="/images/apple-watch-in-car.jpg" title="Apple Super" caption="This is the caption" %}

Lorem ipsum dolor sit amet, `consectetuer adipiscing` elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero. Lorem ipsum dolor sit amet, `consectetuer adipiscing` elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero.

## Lists

Here is an unordered list of items, typically rendered as a bulleted list:

+ Donec non tortor in arcu mollis feugiat
+ Lorem ipsum dolor sit amet, consectetuer adipiscing elit
+ Donec id eros eget quam aliquam gravida
+ Vivamus convallis urna id felis
+ Nulla porta tempus sapien

Here is an ordered list of items, typically rendered as a numbered list:

1. Donec non tortor in arcu mollis feugiat
2. Lorem ipsum dolor sit amet, consectetuer adipiscing elit
3. Donec id eros eget quam aliquam gravida
4. Vivamus convallis urna id felis
5. Nulla porta tempus sapien

### Tables

| Title | Title |
| ------| ----- |
| Text  | Text  |
| Text  | Text  |
| Text  | Text  |