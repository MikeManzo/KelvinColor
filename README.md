# KelvinColor

[![Language](https://img.shields.io/badge/Swift-5-orange.svg?style=flat)](https://swift.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

_Black body temperature to color in swift._

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
