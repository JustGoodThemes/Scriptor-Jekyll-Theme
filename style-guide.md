---
layout: page
title: Style Guide
description: This is a style guide of the BlogInn Jekyll theme
---

This is a pragraph. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enim in turpis pulvinar facilisis. Ut felis.

# This is an H1

<mark>Quisque facilisis erat a dui</mark>. Nam malesuada ornare dolor. Cras gravida, diam sit amet rhoncus ornare, erat elit consectetuer erat, id egestas pede nibh eget odio. Proin tincidunt, velit vel porta elementum, magna diam molestie sapien, non aliquet massa pede eu diam. Aliquam iaculis. Fusce et ipsum et nulla tristique facilisis.

## This is an H2

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero.

### This is an H3

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero.

#### This is an H4

Quisque facilisis erat a dui. Nam malesuada ornare dolor. Cras gravida, diam sit amet rhoncus ornare, erat elit consectetuer erat, id egestas pede nibh eget odio. Proin tincidunt, velit vel porta elementum, magna diam molestie sapien, non aliquet massa pede eu diam. Aliquam iaculis.

### Quoting

>“Creativity is allowing yourself to make mistakes. Design is knowing which ones to keep.” <cite>― Scott Adams</cite>

Lorem ipsum dolor sit amet, `consectetuer adipiscing` elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero.

<hr />

### Syntax Highlighter

{% highlight css %}

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

{% endhighlight %}

{% highlight javascript %}

// Simple map
var map;
function initMap() {
    map = new google.maps.Map(document.getElementById('map'), {
        center: {lat: -34.397, lng: 150.644},
        zoom: 8
    });
}

{% endhighlight %}

### Videos

<iframe src="https://player.vimeo.com/video/153339497?byline=0" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p><a href="https://vimeo.com/153339497">Terraforming</a> from <a href="https://vimeo.com/studioswine">Studio Swine</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

### Full Width Image

Images work too! Already know the URL of the image you want to include in your article? Simply paste it in like this to make it show up:

{% include image_full.html imageurl="/assets/images/posts/2019/Apple-Watch-In-Car.jpg" title="Apple" caption="This is caption" %}

Lorem ipsum dolor sit amet, `consectetuer adipiscing` elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero.

### Regular Image

{% include image_caption.html imageurl="/assets/images/posts/2019/Apple-Watch-In-Car.jpg" title="Apple Super" caption="supertest" %}

Lorem ipsum dolor sit amet, `consectetuer adipiscing` elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero. Lorem ipsum dolor sit amet, `consectetuer adipiscing` elit. Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Suspendisse id velit vitae ligula volutpat condimentum. Aliquam erat volutpat. Sed quis velit. Nulla facilisi. Nulla libero.

### Unordered Lists

+ Donec non tortor in arcu mollis feugiat
+ Lorem ipsum dolor sit amet, consectetuer adipiscing elit
+ Donec id eros eget quam aliquam gravida
+ Vivamus convallis urna id felis
+ Nulla porta tempus sapien

### Ordered Lists

1. Donec non tortor in arcu mollis feugiat
2. Lorem ipsum dolor sit amet, consectetuer adipiscing elit
3. Donec id eros eget quam aliquam gravida
4. Vivamus convallis urna id felis
5. Nulla porta tempus sapien

### Tables

<table>
    <caption>Table Demo</caption>
    <thead>
        <tr>
            <th>Content categories</th>
            <th>Flow content</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Permitted content</td>
            <td>
                In this order:
                <ul>
                    <li>an optional <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/caption"><code>&lt;caption&gt;</code></a> element,</li>
                    <li>zero or more <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/colgroup"><code>&lt;colgroup&gt;</code></a> elements,</li>
                    <li>an optional <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/thead"><code>&lt;thead&gt;</code></a> element,</li>
                    <li>one of the two alternatives:
                        <ul>
                            <li>one <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tfoot"><code>&lt;tfoot&gt;</code></a> element, followed by:
                                <ul>
                                    <li>zero or more <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tbody"><code>&lt;tbody&gt;</code></a> elements,</li>
                                    <li>or one or more <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tr"><code>&lt;tr&gt;</code></a> elements,</li>
                                </ul>
                            </li>
                            <li>a second alternative followed by an optional <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tfoot"><code>&lt;tfoot&gt;</code></a> element:
                                <ul>
                                    <li>either zero or more <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tbody"><code>&lt;tbody&gt;</code></a> elements,</li>
                                    <li>or one or more <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tr"><code>&lt;tr&gt;</code></a> elements</li>
                                </ul>
                            </li>
                        </ul>
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Tag omission</td>
            <td>None, both the <span title="syntax-start-tag">start tag</span> and the <span title="syntax-end-tag">end tag</span> are mandatory</td>
        </tr>
        <tr>
            <td>Permitted parent elements</td>
            <td>Any element that accepts flow content</td>
        </tr>
        <tr>
            <td>Normative document</td>
            <td>HTML5, section 4.9.1 (HTML4.01, section 11.2.1)</td>
        </tr>
    </tbody>
</table>
