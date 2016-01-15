# css-line-height 0.0.6

Css module of single purpose classes for line height

#### Stats

212 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-line-height
```

#### With Git

```
git clone https://github.com/tachyons-css/css-line-height
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-line-height";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-line-height">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   LINE HEIGHT
*/
.lh { line-height: 1; }
.lh-title { line-height: 1.3; }
.lh-copy { line-height: 1.5; }
.lh-2 { line-height: 2; }
.lh-3 { line-height: 3; }
@media screen and (min-width: 48em) {
 .lh-ns { line-height: 1; }
 .lh-title-ns { line-height: 1.3; }
 .lh-copy-ns { line-height: 1.5; }
 .lh-2-ns { line-height: 2; }
 .lh-3-ns { line-height: 3; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .lh-m { line-height: 1; }
 .lh-title-m { line-height: 1.3; }
 .lh-copy-m { line-height: 1.5; }
 .lh-2-m { line-height: 2; }
 .lh-3-m { line-height: 3; }
}
@media screen and (min-width: 64em) {
 .lh-l { line-height: 1; }
 .lh-title-l { line-height: 1.3; }
 .lh-copy-l { line-height: 1.5; }
 .lh-2-l { line-height: 2; }
 .lh-3-l { line-height: 3; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

