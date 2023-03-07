# Battery Level Indicator
This project displays the battery percentage of the device the webpage is being viewed on. It also displays a liquid battery level that changes color based on the battery percentage. Additionally, it shows a message indicating whether the battery is low, charging, or full.

## Technologies Used
* HTML
* CSS
* JavaScript

## Dependencies

This project uses the `remixicon` font for the battery icons. It is included as a link in the HTML file.

## Instructions

To view the battery percentage, simply open the HTML file on a device with a battery. The battery percentage, liquid battery level, and battery status message will update in real-time.

## Implementation Details

The battery percentage is obtained using the `navigator.getBattery()` function in JavaScript. The liquid battery level is updated and colored based on the percentage obtained. The battery status message is updated depending on the battery percentage and whether it is charging or not.

The CSS file includes various responsive styles, as well as variables for colors and fonts. The `@media` queries include breakpoints for small, medium, and large devices.

## Acknowledgments
This project was created with the guidance of [Bedimcode](https://www.youtube.com/watch?v=0gV3kmnLir0) in his YouTube tutorial.
