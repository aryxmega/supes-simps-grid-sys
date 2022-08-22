# Supes Simps Grid Sys

Supes Simps Grid Sys (aka SSGS) is a a super simple grid system that's mad easy to customize to fit your millennial needs. It currently supports Chrome, Firefox, Safari, Opera, IE and major mobile devices.

## Installation

-   Clone: https://github.com/aryxmega/supes-simps-grid-sys.git
-   Download latest .zip file: https://github.com/aryxmega/supes-simps-grid-sys/archive/refs/heads/master.zip


## Getting Started
Getting started is supes simps:

#### First you need to link the stylesheet
```html
<link rel="stylesheet" type="text/css" href="style/sheet.css">
```

#### Structuring your layouts
```html
<div class="wrap">
    <div class="block-3">Content here</div>
    <div class="block-3">Content here</div>
    <div class="block-3">Content here</div>
</div>
```
Creating a three-column layout is supes simps (this will scale each column down to 100% width on mobile). Wrap the .block's in a .wrap class to clear the left floats.

#### Customizing your grid
Maybe you want to kick-it old school and create a two-column layout — it's mad simps. All you need to know is basic math (as long as the .block- classes equal 100%, it will be fire).
```html
<div class="wrap">
    <div class="block-75">Some rad content here</div>
    <div class="block-25">Some informational content here</div>
</div>
```
Creating the css is also simps:
```css
.block-75 { width: 75%; }
.block-25 { width: 25%; }
```

### License
```
(C) Copyright 2019 Ary Mega

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
