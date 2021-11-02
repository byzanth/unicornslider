# unicornslider 1.0.1
http://unicornslider.sagaverse.com/ - Copyright (c) 2016 Nils Kreutzer
- view [Demo](https://byzanth.github.io/UnicornSlider/demo)

## Features
- an awesome, fully adaptive jQuery slider plugin perfectly suited for sliding menus
- 5 predefined styles
- powered by unicorns

## Requirements
- UnicornSlider requires jQuery 1.7 or higher to work
- Works with IE 9+, Chrome, Firefox, Opera

## Releases
The `master` branch of this repository is always the latest development version of UnicornSlider. Please view the [Releases](https://github.com/byzanth/UnicornSlider/releases) section for a list of official UnicornSlider builds.

## Updates
** Version 1.0 **
- Initial Release

## General Notes
UnicornSlider is open source under the [MIT License](https://github.com/byzanth/UnicornSlider/blob/master/LICENSE)

## Examples
- [Basic Slider](http://unicornslider.sagaverse.com/index.html)
- [Vertical Slider](http://unicornslider.sagaverse.com/basic-slider-vertical.html)
- [Documentation](http://unicornslider.sagaverse.com/documentation.html)

## Properties
### debug:
`debug` mode displays infos to the console, values true or false

### wrapAround
Show arrows across borders, values true or false

### leanWrapper
Shrink wrapper to minmal size, values true or false

### orientation
Select the animation direction, values "horizontal" or "vertical"

### namespace
Prefix string attached to the class of every element generated by the plugin

### easing
Determines the easing method used in jQuery transitions. jQuery easing plugin is supported!

### prevText
The `prevText` will be inserted in prev tag

### nextText
The `nextText` will be inserted in next tag

### style
Additional class for style in parent element. There are 5 predefined styles ("pinkelephant", "earlgrey", "lattemacchiato", "gargleblaster" and a fallback), allthough you can of course define your own.

### centerActive
Select if active element is centered, values "off", "mobile", "desktop" or "on"

### buttonHeight
Height of button element in px

### buttonWidth
Width of button element in px

### visibleItems
The maximal number of items visible (the displayed number of items can be lower corresponding to screensize)

### speed
Animation speed in Milliseconds

### startFrom
The item active on init

### init
Callback function that fires on init done

### button
Callback function that fires on button "prev" or "next" before button click is processed

### animationStart
Callback function that fires on animation started

### animationEnd
Callback function that fires on animation ended

### destroyed
Callback function that fires on slider destroyed

## tipps:
To destroy an active slider at runtime, use $(".unicornslider").data("unicornslider").unicornslider("destroy")
