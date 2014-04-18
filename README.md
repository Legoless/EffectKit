# DesignKit

Innovative iOS framework that attempts to bridge the gap between designs created in Adobe Photoshop Tool. It's main mission is to enable developers to quickly create a living design out from PSD's provided by a designer.

DesignKit is tightly coupled together with DesignKit Photoshop CC extension to enable more advanced functionalities.

## Features

DesignKit offers many features that aid in transferring Photoshop designs into a working application. Some of them are described below in detail.

There are also options to open .PSD file created in Photoshop and use shape and bitmap assets directly in code.

### Colors

Working with colors has been made easy with DesignKit. Just use UIColorFromKey macro and it will automatically figure out what color you mean, whether you asked for a color by name, hex-decimal value or RGB values. We have added hundreds of prebuilt colors which can be used in the application. They include company slogan colors and flat color library.

### Filters

Effect kit also includes Photoshop filters which can be done on all UIImage layers. Otherwise you must call rasterize method on UIView to convert it into an image.

- Blur
- Edge Detection

### Effects

The following effects from Photoshop's blending options are currently implemented / or in progress.

- Stroke (outside, inside)
- Color overlay
- Gradient overlay
- Drop shadow
- Inner glow
- Outer glow

### Icons

DesignKit provides many vector icons out of the box, used for social icons and most common tasks.

# Technique

The effects are rendered each on a separate UIViews that are placed above the target layer in the view hierarchy. This allows for setting the opacity of each effect separately, including the layer itself.

Compatibility
========

The framework requires iOS 7 or Mac OS X 10.9.

Contributions
======

The following projects were a great help in creating the **DesignKit**.

- https://github.com/bengotow/PSDWriter
- https://github.com/layervault/psd.rb

Contact
======

Dal Rupnik

- [legoless](https://github.com/legoless) on **GitHub**
- [@thelegoless](https://twitter.com/thelegoless) on **Twitter**
- [legoless@arvystate.net](mailto:legoless@arvystate.net)

License
======

Completely free. See [LICENSE](https://github.com/Legoless/DesignKit/blob/master/LICENSE) file for more information.
