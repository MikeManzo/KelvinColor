# KelvinColor

[![Status](https://travis-ci.org/MikeManzo/Ansi.svg?branch=master)](https://travis-ci.org/MikeManzo/KelvinColor)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/mikemanzo/KelvinColor.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/MikeManzo/KelvinColor.svg)
![GitHub All Releases](https://img.shields.io/github/downloads/MikeManzo/KelvinColor/total.svg)
![Swift](https://img.shields.io/badge/%20in-swift%205.1-orange.svg)


_Black body temperature to color in swift.  
Updated for Swift 5.0.  Please find Sihao Lu's original version [here](https://github.com/DJBen/KelvinColor)_

## Installation

### Carthage

Add the following in your Swift 5.x project's  [Cartfile](https://github.com/Carthage/Carthage/blob/master/Documentation/Artifacts.md):

    github "MikeManzo/KelvinColor"

## Usage

Temperature to color and color to temperature methods are extensions of `UIColor` class. No other classes are required!

1. Kelvin to `UIColor`

```swift
UIColor.init(temperature: 6500)
// (255, 249, 253)
```
2. UIColor to Kelvin

```swift
color.temperature
```
