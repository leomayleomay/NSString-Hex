# NSString+Hex

This is a `NSString` category used to convert a string composed of hex to a decimal array.

## How to Use

[Download](https://github.com/leomayleomay/NSString+Hex/archive/master.zip) NSString+Hex, unzip and drag everything inside directory *src* into your Xcode project and you are all set.

## Examples

```objective-c
#import "NSString+Hex.h"

[@"000102030405060708090A0B0C0D0E0F" hexToDecimalArray]; // the output is [0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]

```