# Pygame Widgets

![](https://img.shields.io/pypi/dm/pygame-widgets)

A helper module for common widgets that may be required in developing applications with Pygame. It supports fully
customisable buttons, collections of buttons, textboxes, sliders and many more! If there are any widgets that you would like to see
added, please create an issue!

## NEW FEATURES

* Combo Box: Select options from a list that appears when typing into a search bar
* Dropdown: Select options from a list that appears when hovered over
* Progress Bar: Shows a percentage of completeness, great for loading screens and health bars
* Toggle: Allows switching between two values, great for settings
* Animations: Create an animation that changes a widgets attributes over some time, running on a separate thread

## Prerequisites

* [Python 3](https://www.python.org/downloads) `>= 3.7`
* [Pygame](https://www.pygame.org/wiki/GettingStarted) `>= 2.0.0`

## Installation

Ensure that Python 3 and pip are installed and added to your environment PATH.

```python -m pip install pygame-widgets```

Open a Python console and run the following command.

```import pygame_widgets```

If you receive no errors, the installation was successful.

## Usage

For full documentation, see [pygamewidgets.readthedocs.io](https://pygamewidgets.readthedocs.io/en/latest/).

* [Common](widgets/common.md)
* [Button](widgets/button.md)
* [ButtonArray](widgets/buttonarray.md)
* [TextBox](widgets/textbox.md)
* [Slider](widgets/slider.md)
* [Toggle](widgets/toggle.md)
* [ProgressBar](widgets/progressbar.md)
* [Dropdown](widgets/dropdown.md)
* [ComboBox](widgets/combobox.md)
* [Animations](animations/animations.md)

## How to Contribute

Any contribution to this project would be greatly appreciated.
This can include:

* Finding errors or bugs and creating a new issue
* Addressing active issues
* Adding functionality
* Improving documentation

If applicable, you should make any changes in a forked repository and then create a pull
request once the changes are ***complete*** and preferably tested if possible.

_Note: If writing any code, please attempt to follow the [Code Style Guide](CONTRIBUTING.md)_