# CSS WIDTHS

  Mobile-first classes for css-widths.
  Set the desired css-widths on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-widths
```
or download the css on github and include in your project.

## File Size


## The Code
```
.wi-bb { width: border-box; }
.wi-cb { width: content-box; }
.wi-mx { width: max-content; }
.wi-mn { width: min-content; }
.wi-av { width: available; }
.wi-fc { width: fit-content; }
.wi-at { width: auto; }
.wi-i {  width: inherit; }

@media screen and (min-width: 48em) {
  .wi-bb-ns { width: border-box; }
  .wi-cb-ns { width: content-box; }
  .wi-mx-ns { width: max-content; }
  .wi-mn-ns { width: min-content; }
  .wi-av-ns { width: available; }
  .wi-fc-ns { width: fit-content; }
  .wi-at-ns { width: auto; }
  .wi-i-ns {  width: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .wi-bb-m {    width: border-box; }
  .wi-cb-m {    width: content-box; }
  .wi-mx-m {    width: max-content; }
  .wi-mn-m {    width: min-content; }
  .wi-av-m {    width: available; }
  .wi-fc-m {    width: fit-content; }
  .wi-at-m {    width: auto; }
  .wi-i-m {     width: inherit; }
}

@media screen and (min-width: 64em)  {
  .wi-bb-l {    width: border-box; }
  .wi-cb-l {    width: content-box; }
  .wi-mx-l {    width: max-content; }
  .wi-mn-l {    width: min-content; }
  .wi-av-l {    width: available; }
  .wi-fc-l {    width: fit-content; }
  .wi-at-l {    width: auto; }
  .wi-i-l {     width: inherit; }
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

