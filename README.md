# CSS LINE HEIGHT

  Mobile-first classes for css-line-height.
  Set the desired css-line-height on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-line-height
```
or download the css on github and include in your project.

## File Size


## The Code
```
.lh       { line-height: 1; }
.lh-title { line-height: 1.3; }
.lh-copy  { line-height: 1.5; }
.lh-2     { line-height: 2; }
.lh-3     { line-height: 3; }

@media screen and (min-width: 48em) {
  .lh-ns       { line-height: 1; }
  .lh-title-ns { line-height: 1.3; }
  .lh-copy-ns  { line-height: 1.5; }
  .lh-2-ns     { line-height: 2; }
  .lh-3-ns     { line-height: 3; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .lh-m       { line-height: 1; }
  .lh-title-m { line-height: 1.3; }
  .lh-copy-m  { line-height: 1.5; }
  .lh-2-m     { line-height: 2; }
  .lh-3-m     { line-height: 3; }
}

@media screen and (min-width: 64em)  {
  .lh-l       { line-height: 1; }
  .lh-title-l { line-height: 1.3; }
  .lh-copy-l  { line-height: 1.5; }
  .lh-2-l     { line-height: 2; }
  .lh-3-l     { line-height: 3; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

