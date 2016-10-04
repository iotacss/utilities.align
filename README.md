# Align Utility #

The align utility contains helper classes for the CSS vertical align property.


### Installation ###

```
npm install --save iotacss-align
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)
* [Settings.Breakpoint](https://github.com/iotacss/settings.breakpoint)


### Options ###

```
$iota-align--res                : false !default;
$iota-align-top-namespace       : 'align-top' !default;
$iota-align-bottom-namespace    : 'align-bottom' !default;
$iota-align-middle-namespace    : 'align-middle' !default;
$iota-align-baseline-namespace  : 'align-baseline' !default;
```


### Classes ###

```
.u-align-top
.u-align-bottom
.u-align-middle
.u-align-baseline


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: .u-align-top@sm
```
