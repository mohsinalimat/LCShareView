# LCShareView

![License MIT](https://img.shields.io/dub/l/vibe-d.svg)
![Pod version](http://img.shields.io/cocoapods/v/LCShareView.svg?style=flat)
![Platform info](http://img.shields.io/cocoapods/p/LCShareView.svg?style=flat)

Custom Share View

![1](demo.gif)

##Installation

Cocoapods:
```
pod 'LCShareView'
```

##Example Usage
```
#import <LCShareView.h>
```
```
 [LCShareView showShareViewInVC:self.navigationController buttonImages:images buttonPress:^(UIButton *button) {
        // do something
    } dissmisBlock:^{
        // do something
    }];
```

##Requirements
* iOS 7 or higher
* ARC

##License
```
The MIT License (MIT)

Copyright (c) 2015 Bawn

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```