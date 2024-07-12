# Image_Steganography_Python
## Overview
This project demonstrates how to hide (or encode) and extract (or decode) hidden messages in images using Python. The process of hiding information within an image is known as steganography. This project uses Python 3 and libraries like Pillow, OS, and TKinter.

## Features
<ul style="list-style-type:disc;">
<li><B>Encode Messages:</B> Hide a secret message inside an image.</li>
<li><B>Decode Messages:</B> Extract the hidden message from an image.</li>
<li><B>Graphical User Interface (GUI):</B> Easy-to-use GUI for encoding and decoding messages using TKinter.</li>
<li><B>Image Handling:</B> Use the Pillow library to manage image operations.</li>
</ul>

## Technologies Used
<ul style="list-style-type:disc;">
<li>Python 3</li>
<li>Pillow: For image processing.</li>
<li>OS: For operating system related tasks.</li>
<li>TKinter: For creating the GUI.</li>
</ul>

## Getting Started
### Prerequisites
<ul style="list-style-type:disc;">
<li>Python 3.x</li>
<li>Pip (Python package installer)</li>
</ul>

### Installation
<ol style="list-style-type = 1">
<li>Clone the repository:

```bash
git clone https://github.com/shantam010/image-steganography-python.git
```
</li>
<li>Install the required libraries:

```bash
pip install Pillow
```
</li>

`TKinter` is included with standard Python installations, so no separate installation is required for it.

</ol>

### Usage
<ol style="list-style-type = 1">
<li> Run the application:

```bash
python GUIProvider.py
```
</li>
<li>Encode a message:
<ul style="list-style-type:disc;">
<li>Open the application.</li>
<li>Select the image you want to use.</li>
<li>Enter the message you want to hide.</li>
<li>Click the "Encode" button to hide the message in the image.</li>
<li>Save the new image with the hidden message.</li>
</ul></li>

<li>Decode a message:
<ul style="list-style-type:disc;">
<li>Open the application.</li>
<li>Select the image with the hidden message.</li>
<li>Click the "Decode" button to extract and display the hidden message.</li>
</ul></li>

</ol>

### Example
Here is a simple example to get you started:

<ol style="list-style-type = 1">
<li>Encode a message:
<ul style="list-style-type:disc;">
<li>Select an image (e.g., input_image.png).</li>
<li>Enter the message "Hello, World!".</li>
<li>Click "Encode" and save the resulting image (e.g., encoded_image.png).</li>
</ul></li>

<li>Decode a message:
<ul style="list-style-type:disc;">
<li>Select the encoded_image.png.</li>
<li>Click "Decode" to reveal the hidden message "Hello, World!".</li>
</ul></li>
</ol>

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.
