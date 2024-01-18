# Color Palette Generator

This JavaScript-based Color Palette Generator is designed to dynamically create and display a set of colors with their corresponding hex codes. The palette is generated based on a primary color, and users can interact with the generated colors by copying the hex code to their clipboard.

# Key Features:
1. ##Color Class:
   - The generator uses a `Color` class to represent and manipulate colors. This class includes properties and methods for setting the hue, saturation, lightness, and changing these values within specified limits.

2. ##User Interaction:
   - Users can influence the color palette by adjusting the rotation input. This rotation value determines the variation in hue for the generated colors.

3. ##Dynamic Color Generation:
   - The color palette is not generated using random hex values but instead relies on the `Color` class for a more controlled and aesthetically pleasing color scheme.

4. ##Light Background Adjustment:
   - The generator considers the background, adjusting the lightness values for a more harmonious color palette. The `lightBackground` variable controls whether a light background is in use.

5. ##Palette Display:
   - The color palette is displayed as a set of color boxes, each containing a rectangular color representation and its corresponding hex code.

6. ##Clipboard Copy:
   - Users can click on any color box to copy its hex code to the clipboard. A brief "Copied" message appears, providing feedback to the user.

7. ##Responsive Design:
   - The generator is designed to display a fixed number of colors (default: 5) in a clean and organized layout.

##How to Use:
1. ##Rotation Input:
   - Adjust the rotation input slider to change the variation in hue for the generated colors. This influences the overall color harmony.

2. ##Copy Color Code:
   - Click on any color box to copy its hex code to the clipboard. A confirmation message will appear briefly.

3. ##Refresh Palette:
   - Click the "Refresh" button to generate a new color palette based on the adjusted rotation and background settings.

##Implementation Details:
   - The code utilizes modern JavaScript features and follows best practices for readability and maintainability.
   - It includes comments to explain each section of the code, making it easy for developers to understand and modify.
   - The structure allows for further expansion and customization, making it a versatile tool for different color palette requirements.

Feel free to explore, use, and contribute to this Color Palette Generator on GitHub to enhance its features and adapt it to specific needs.
