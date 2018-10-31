# Madeno

Madeno is Material Design Notification component for Material UI v1.

## Getting Started
```
npm install madeno
```

## Demo
Install and run the demo to see how Madeno looks. Spoiler alert: it looks nice.

## Changelog
### Madeno 0.3
* Major improvements to follow the official Material Design specifications
* ```appTitle``` has been added as a new variable to show in the notification to better match Material Design
* Colors cheveron in the ```accent``` color
* Implements showing the ```appTitle``` for brand identity, uses ```accent``` as font color
* Adds ```accent``` property with default color ```#8bc34a``` for brand identity
* ```raised``` has been replaced with ```elevation``` and expects a number between ```0``` and ```24```, with a default of ```2```
* The timestamp can no longer be disabled
* Kill of ```CardHeader``` in favor of ```CardContent```
* Clean-up for the files included in the build and package that can be downloaded from npm
* Put a div around avatars
* Revamped demo
* Remove misplaced ```moment``` package
* Use ```date-fns\format``` to get the default timestamp
* Timestamp is now by default of the format ```H:mm``` instead of ```H:mm A```
* Madeno is now about 20kB smaller
* Fixes an issue where the hover effect of buttons would be shown to far to the left
* We added this changelog, yay

### Madeno 0.2.2
* Minor update to used font weights

### Madeno 0.2.1
* Updates the drop shadow behind notifications

### Madeno 0.2
* Replace some branding and references to the original project
* Update a bunch of dependencies
* Move action buttons to the left
* Places notifications at the same distance from the bottom as from the right
* Use a more Material Design-like drop shadow

### Madeno 0.1.1
_Initial release_

* Don't show a divider between the header and the footer
* Use a background color for the footer