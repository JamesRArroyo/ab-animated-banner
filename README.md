# \<ab-animated-banner\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/JamesRArroyo/ab-animated-banner)


A Polymer web component.

The `ab-animated-banner` is a polymer element which displays a simple banner that cycles through an array of strings.

![](https://user-images.githubusercontent.com/11878947/32638046-7787664e-c57a-11e7-8321-01bd177e79db.gif)

## Installation

```sh
$ bower install -S ab-animated-banner
```

## Getting Started

Include the [webcomponents.js](http://webcomponents.org/polyfills/) "lite" polyfill (for browsers who don't natively support web components), then import `ab-animated-banner.html`:


```html
<script src="../bower_components/webcomponentsjs/webcomponents-lite.js"></script>
<link rel="import" href="/bower_components/ab-animated-banner/ab-animated-banner.html">
```

Add the element using .

```html
<ab-animated-banner> </ab-animated-banner>
```

Customize the element by using the 'banner-options' attribute. ([Customizable properties](https://github.com/JamesRArroyo/ab-animated-banner#customizable-properties) are listed below.)

```
<ab-animated-banner banner-options='{"headerTitle": "Followers", "bodyArray": ["Jimmy Arroyo", "John Doe"]}'> </ab-animated-banner>
```
## Customizable Properties

ab-animated-banner allows for the following properties to be customized or configured.

Property           | Type | Description
-------------------        | --------- | --------------------|
headerTitle | String | The banner's title that is displayed in the header of the banner.
bodyArray | Array<String> | The set of strings the banner cycles through in the body.
This element is still in its early stages.. more customizations to come!! Feel free to request a feature by creating an [issue](https://github.com/JamesRArroyo/ab-animated-banner/issues) and labeling it as a 'feature' or feel free to [contribute](https://github.com/JamesRArroyo/ab-animated-banner#contributing).



## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

The MIT License (MIT)

Copyright (c) 2017 Jimmy Arroyo

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
