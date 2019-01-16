# [Smart Carousel Element](https://www.htmlelements.com) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Get%20over%2020%20free%20custom%20elements%20based%20on%20SmartHTMLElements%20&url=https://www.htmlelements.com/&via=htmlelements&hashtags=bootstrap,design,templates,blocks,developers,webcomponents,customelements,polymer,material)

[![Slack](https://smarthtmlelements-slack.herokuapp.com/badge.svg)](https://smarthtmlelements.slack.com/)
[![Price](https://img.shields.io/badge/price-FREE-0098f7.svg)](https://github.com/HTMLElements/smart-carousel/blob/master/LICENSE)
[![npm](https://img.shields.io/npm/v/froala-design-blocks.svg?colorB=brightgreen)](https://www.npmjs.com/package/@smarthtmlelements/smart-carousel)
[![GitHub package version](https://img.shields.io/github/package-json/v/HTMLElements/smart-carousel.svg)](https://github.com/HTMLElements/smart-carousel)
[![License: APACHE](https://img.shields.io/badge/license-APACHE-blue.svg)](https://github.com/HTMLElements/smart-carousel/blob/master/LICENSE)
[![](https://img.shields.io/website-up-down-green-red/https/shields.io.svg?label=www.htmlelements.com)](https://www.htmlelements.com)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/htmlelements/smart-carousel)

# &lt;smart-carousel&gt;

[Live Demo ↗](https://htmlelements.com/demos/carousel/)
|
[Documentation ↗](https://www.htmlelements.com/docs/)
|
[Installation ↗](https://www.npmjs.com/package/@smarthtmlelements/smarthtmlelements-core)

[&lt;smart-carousel&gt;](https://htmlelements.com/demos/carousel/) is a Custom HTML Element providing slide show/banner rotator](https://htmlelements.com/).

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="../smart-core/source/smart.core.js"></script>
    <link rel="stylesheet" href="../smart-core/source/styles/smart.default.css" type="text/css" />
 <script>
   window.onload = function () {
    var basePath = '/images/',
        carouselSquare = document.getElementById('carouselSquare');
 
    carouselSquare.dataSource = generateDataSource(7);
 
    function generateDataSource(items) {
        let dataSource = Array(items).fill({});

        dataSource.forEach((element, index) => dataSource[index] = { image: `${basePath}carousel-square-${index + 1}.jpg` });
        return dataSource;
    }
}
   </script>
     <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<smart-carousel id="carouselSquare" auto-play slide-show loop hide-indicators keyboard display-mode="3d" interval="10000"></smart-carousel>
```

[<img src="https://raw.githubusercontent.com/htmlelements/smart-carousel/master/smart-carousel.png" alt="Screenshot of smart-carousel">](https://htmlelements.com/demos/carousel)

## Getting Started

Smart HTML Elements components documentation includes getting started, customization and api documentation topics.

[Getting Started Documentation](https://www.htmlelements.com/docs/)


## The file structure for Smart HTML Elements

- `source/`

  Javascript files.

- `source/styles/`

  Component CSS Files.

- `demos/`

  Demo files

## Running demos in browser

1. Fork the `Smart-HTML-Elements-Core` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `Smart-HTML-Elements-Core` directory, run `npm install` and then `bower install` to install dependencies.

1. Run a localhost or upload the demo on a web server. Then run:

  - /demos/smart-carousel/smart-carousel-overview.htm


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. 

## Creating a pull request

  - Make sure your code is compliant with ESLint
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of our team members


## License

Apache License 2.0
