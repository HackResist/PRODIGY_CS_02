# Pixel Manipulation for Image Encryption Tool
> If you like this repository, don't forget to give it a ⭐!
## Overview

This project is a graphical user interface (GUI) application built using Python's Tkinter library. The tool allows users to load, encrypt, and decrypt images using a simple XOR encryption method. The UI is designed to be visually appealing and user-friendly.

## Features
  - **Load Image:** Load any image in PNG or JPEG format for encryption.
  - **Choose Encrypted Image:** Load an already encrypted image for decryption.
  - **Enter Encryption Key:** Input an integer key to encrypt or decrypt the image.
  - **Encrypt Image:** Encrypt the loaded image using the entered key.
  - **Decrypt Image:** Decrypt the loaded encrypted image using the entered key.
  - **Save Encrypted Image:** Save the encrypted image to your local storage.
  - **Save Decrypted Image:** Save the decrypted image to your local storage.
  - **Attractive UI:** The application features an indigo-themed background with color-coded buttons for a better user experience.

## Installation
  1.Clone the Repository or download this Repository.
  2.**Install Dependencies**:Ensure you have Python 3.x installed. Then, install the required libraries. Run this command `pip install pillow numpy`.

## How It Works
  - **Encryption:** The tool uses a bitwise XOR operation to encrypt the image with the provided key. The encryption is reversible, meaning the same key can be used to decrypt the image.
  - **Decryption:** The decryption process also uses XOR, so inputting the same key used during encryption will retrieve the original image.
