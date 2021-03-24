# Specify Changelog

## 4.0.0

- Releasing as Adobe Exchange compatible extension.

## 3.2.2

- Updating artwork files and external URLs.

## 3.2.0

### Updates

- User-defined options, styles, and settings are now persistent after closing the application.

## 3.1.0

### Updates

- Changed custom scale dropdown to an editable text field to allow for a scales ranging from 1/1 to 1/999.

## 3.0.3

### Fixes

- Properly convert stroke width, gap, and head and tail units.

## 3.0.2

- Formatting - no script/extension changes.

## 3.0.1

- Revert back to CEP 9 - Adobe doesn't seem to know what they're doing with Illustrator updates and causing crashes

## 3.0.0

- Updated to [CEP 10](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_10.x/Documentation/CEP%2010.0%20HTML%20Extension%20Cookbook.md)

## 2.0.4

### Fixes

- Adjusting default stroke with to 1 unit (instead of 0.5)
- Updated internal build process

## 2.0.2

### New Features

- Completely updated the Specify dialog UI
- **New Dialog UI and Adobe Extension**: Added a version packaged as a [Free Creative Cloud Extension available via Adobe Exchange](https://exchange.adobe.com/creativecloud.details.106345.html) for Illustrator CC users.

## 1.3.1

### Fixes

- Automatically adds a leading zero to the font size field if user enters a value such as `.25` instead of `0.25`. For reference, font sizes require a leading zero on input.

## 1.3.0

### New Features

- **User-defined custom scale for dimensions and labels**: Allows the user to specify a working scale along with allowing for customizable unit labels. This release enables the user to specify a working scale along with allowing for customizable unit labels.

## 1.2.2

### Fixes

- Prevents the script from generating a dashed line when specifying the dimensions of an object with dashed paths.

## 1.2.1

### Fixes

- The font size input in the options panel now allows the user to specify the size of the label text in the same units as the document ruler.
- Fixes a bug with the help text that appears when hovering over an input field in the Specify dialog box. Help text was showing the current settings as Defaults rather than the script's default values.

## 1.2.0

### New Features

- Implemented environmental variables to persist settings (to persist options between running the script multiple times, even between multiple documents) until application is closed.
- Added a 'Restore Defaults' button to roll back to initial settings.

### Fixes

- Removed 'Advanced Options' toggle and section; moved all items into 'Options' panel.

## 1.1.0

### New Features

- Now possible to specify multiple objects simultaneously.
- Added 'Select All' option to easily select all dimensions to specify.
- Added 'Advanced Options' panel:
  - Easily change font size.
  - Easily change RGB color of dimension lines and labels.
  - Easily change number of decimal places for dimension labels.
- Added help tips (hover over options in dialog).

### Fixes

- Updated 'Specify' button and added 'Cancel' button.
- Improved error handling.
- Fixed issue with label spacing.
- Improved UI of dialog box and options.

## 1.0.0

Initial release.
