# Happy Birthday MikroTik Beep Script

This repository contains a MikroTik script designed to play the "Happy Birthday" melody using the router's beep command. This script is intended for use in the MikroTik RouterOS environment.

## Prerequisites

Before you begin, ensure you have:

- A MikroTik router running RouterOS.
- Basic familiarity with MikroTik RouterOS and its WebFig or WinBox interfaces.

## Installation

### Step 1: Download the Script

First, download the `happy_birthday.rsc` script from this repository.

### Step 2: Upload to Your Router

Upload the script to your MikroTik router. This can be done through the WebFig or WinBox interface.

- For WebFig: Go to **Files** and drag and drop the `.rsc` file into the file list.
- For WinBox: Open **Files** and drag the `.rsc` file into the WinBox window.

### Step 3: Adding the Script to System/Scripts

1. Access your router using WebFig or WinBox.
2. Navigate to **System** > **Scripts**.
3. Click on **Add New** or the `+` icon.
4. Give the script a name, e.g., `HappyBirthday`.
5. In the **Source** field, either:
   - Paste the contents of the `happy_birthday.rsc` file directly, or
   - Use the command `/import file-name=happy_birthday.rsc` to load the script from the file you uploaded.

For more detailed information about MikroTik scripts, visit the [MikroTik Scripting Manual](https://wiki.mikrotik.com/wiki/Manual:Scripting).

## Running the Script

To run the script:

1. Navigate to **System** > **Scripts** in WebFig or WinBox.
2. Select the `HappyBirthday` script from the list.
3. Click on **Run Script** or the `Start` button.

## Script Details and Customization

The script uses specific frequencies to play the "Happy Birthday" melody. You can customize the melody, tempo, and duration as per your requirements. Frequencies used in this script are based on a simplified scale. For a detailed reference on musical note frequencies, visit [Musical Note Frequencies](https://newt.phys.unsw.edu.au/jw/notes.html).

## Contributing

Your contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## License

This script is released under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to the MikroTik community for their valuable resources and support.
- This script was inspired by the versatility of MikroTik RouterOS scripting capabilities.
