# Validate_CSS_color_codes_and_convert_them_to_RGB_and_convert_CMY_mode
This Java program is designed to convert RGB (Red, Green, Blue) values from various hexadecimal formats into CMY (Cyan, Magenta, Yellow) percentages. 
It supports multiple RGB formats and guides the user through a menu-driven interface to input their RGB values correctly and perform the conversion.

**Functionality:**

- **Interactive Menu:** The program presents a menu with different options for the RGB formats that can be entered (#rgb, #rgbc, #rrggbb, #rrggbbcc).
- **Input Validation:** It validates the user's input to ensure it matches the selected format. If the input does not match, it provides feedback and requests re-entry.
- **Color Conversion:** Converts hexadecimal RGB values to decimal, calculates the CMY values based on these decimal values, and displays the results in percentage format.

**Usage:**

1. **Run the Program:** Start the application to interact with the menu.
2. **Select Format:** Choose the RGB format from the menu options (1-4).
3. **Enter RGB Values:** Based on the chosen format, enter the RGB values in the correct hexadecimal syntax.
4. **View CMY Output:** After entering a valid RGB value, view the converted CMY percentages.

**Error Handling:**

- Robust error handling is implemented to manage invalid inputs such as incorrect hexadecimal values, wrong input lengths, and non-integer menu selections.
- User-friendly error messages guide the user through the correct input process after any invalid attempt.

**Example Workflow:**

- User selects option 3 for #rrggbb format.
- User inputs #FF5733.
- Program converts this input to CMY values and displays:
  ```
  C: 0.0%, M: 65.5%, Y: 80.0%
  ```
