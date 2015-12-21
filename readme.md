# tachyons-display
2.1.0

Performance based css module.

## Install
```
npm install --save-dev tachyons-display
```

or download the css on github and include in your project:

```
git clone git@github.com:mrmrs/tachyons-display
```

## The Code
```
/*

   DISPLAY

   Base:
    d = display

   Modifiers:
    n     = none
    b     = block
    ib    = inline-block
    it    = inline-table
    t     = table
    tc    = table-cell
    tr    = table-row
    tcol  = table-column
    tcolg = table-column-group

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large

*/

.dn {     display: none; }
.di {     display: inline; }
.db {     display: block; }
.dib {    display: inline-block; }
.dit {    display: inline-table; }
.dt {     display: table; }
.dtc {    display: table-cell; }
.dtcol {  display: table-column; }
.dtcolg { display: table-column-group; }

@media screen and (min-width: 48em) {
  .dn-ns {     display: none; }
  .di-ns {     display: inline; }
  .db-ns {     display: block; }
  .dib-ns {    display: inline-block; }
  .dit-ns {    display: inline-table; }
  .dt-ns {     display: table; }
  .dtc-ns {    display: table-cell; }
  .dtcol-ns {  display: table-column; }
  .dtcolg-ns { display: table-column-group; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .dn-m {     display: none; }
  .di-m {     display: inline; }
  .db-m {     display: block; }
  .dib-m {    display: inline-block; }
  .dit-m {    display: inline-table; }
  .dt-m {     display: table; }
  .dtc-m {    display: table-cell; }
  .dtcol-m {  display: table-column; }
  .dtcolg-m { display: table-column-group; }
}

@media screen and (min-width: 64em) {
  .dn-l {     display: none; }
  .di-l {     display: inline; }
  .db-l {     display: block; }
  .dib-l {    display: inline-block; }
  .dit-l {    display: inline-table; }
  .dt-l {     display: table; }
  .dtc-l {    display: table-cell; }
  .dtcol-l {  display: table-column; }
  .dtcolg-l { display: table-column-group; }
}


```

## Author

[mrmrs](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

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

