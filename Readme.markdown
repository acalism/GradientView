# Gradient View

Easily use gradients in UIKit. Gradient View is a simple UIView wrapper around CGGradient.

Gradient View is tested on iOS 8. Released under the [MIT license](LICENSE).


## Usage

``` swift
// Initialize a gradient view
let gradientView = GradientView(frame: CGRectMake(x: 20, y: 20, width: 280, height: 280))

// Set the gradient colors
gradientView.colors = [UIColor.greenColor(), UIColor.yellowColor()]

// Optionally set some locations
gradientView.locations = [0.8, 1.0]

// Optionally change the direction. The default is vertical.
gradientView.direction = .Horizontal

// Add some borders too if you want
gradientView.topBorderColor = UIColor.redColor()
gradientView.bottomBorderColor = UIColor.blueColor()

// Add it as a subview in all of its awesome
view.addSubview(gradientView)
```

See the [source](GradientView.swift) for full documentation.


## Example

![Screenshot](http://soff.me/WetB/Screenshot.png) ![Screenshot](http://soff.me/Wg7G/Screenshot2.png)

Open up the included Xcode project for an example app.


## Installation

Simply add the files in the <GradientView/GradientView.swift> to your project. Gradient View also supports installation with [Carthage](https://github.com/Carthage/Carthage).
