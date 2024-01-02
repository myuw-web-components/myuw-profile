# myuw-profile versions

## 1.6.9

* Remove references to Roboto and Arial fonts and replaced with Red Hat Display and Red Hat Text

## 1.6.8

* Remove references to Montserrat font
* Increase font-size to min 16px

## 1.6.7

### Updated

* Update handleLogin event, to hide user's name if both first and last names are missing

## 1.6.6

### Updated

* Update displayName variable to contain user's last name in addition to user's first name
* Update import url of myuw-app-styles

## 1.6.5

### Updated

* Update profile button to strengthen the contrast between the background and foreground on hover effect

## 1.6.4

### Updated

* Update README with releasing information and import path usage recommendation

## 1.6.3

### Changed

* Remove the media query style rule
* Change the width of #myuw-profile-nav from 320px to 230px

### Fixed

* Prevent body from scrolling when the menu modal is open

## 1.6.2

### Fixed

* Decrease the width of profile menu on smaller screens

## 1.6.1

### Added

* Add invisible backdrop behind active profile menu

## 1.6.0

### Fixed

* Ensure focus state is visible
* Improve navigating through profile menu items

## 1.5.0

### Fixed

* Updates to background-color attribute weren't working; now they are.
* Event handlers get cleaned up on disconnect, preventing duplicates, memory leaks, etc.

### Added

* Escape key dismisses the menu.

### Changed

* Elements are hidden with the semantically-appropriate `hidden` attribute.
* Example page uses more modern idioms.
* Simplify/flatten component structure by extracting event handler methods and removing unnecessary property binding logic.
* Whitespace & style changes

## 1.3.2

### Fixed

* Check for valid references before messing with DOM elements/variables

## 1.3.0

### Added

* Component listens for a CustomEvent called "myuw-login" and sets up its appearance accordingly. See the README usage guide.

## 1.2.2

### Added

* Polyfills included in demo page

### Fixed

* Fixed appearance in Firefox

## 1.2.1

### Changed

* Set standard top-bar button margin on containing element
* Removed left-only margin to better support usage outside of myuw-app-bar
* Add use of a CSS variable for menu link color (myuw-menu-color)
* Adjust circle button appearance to be centered better
* Add font weight CSS variable
