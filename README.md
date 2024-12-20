# Project-2: QR Code Generator

## Description
This project generates a QR code for a given URL using Python's `qrcode` library. The generated QR code is saved as an image file and can be shared or used as needed.

## Prerequisites
Before running this project, ensure the following module is installed:

- **qrcode**: You can install it using pip:

    ```bash
    pip install qrcode[pil]
    ```

## How to Run
1. Open a terminal or command prompt in the project directory.

2. Run the Python script:

    ```bash
    python project-2.py
    ```

3. The QR code will be saved as an image file named `url_qrcode.png` in the same directory as the script.

## Features
- **Customizable URL**: Modify the `input_URL` variable in the script to generate a QR code for any desired URL.
- **Image Output**: The QR code is saved as a high-quality PNG image.
- **Error Correction**: Supports basic error correction to ensure the QR code can be read even if partially damaged.

## Limitations
- Static URL: The URL must be updated manually in the script.
- No GUI or user input support.

## Future Enhancements
- Add a GUI for user-friendly interaction.
- Allow users to input the URL dynamically via command-line arguments or a text file.
- Add customization options for colors, size, and error correction levels.

## License
This project is licensed under the MIT License by DzarelDeveloper. Feel free to use, modify, and distribute it as you wish.

---
If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request on the [project repository](https://github.com/DzarelDeveloper).

