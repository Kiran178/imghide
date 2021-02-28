# IMGHIDE

![enter image description here](https://i.ibb.co/PQDHMVP/imghide-1.png)

Hide secret texts/messages inside an image. You can optionally encrypt your texts with a password using AES-256 before encoding into the image.

Inspired from this [Medium post](https://medium.com/better-programming/image-steganography-using-python-2250896e48b9)


## Installation
You can install the all requirements from **requirements.txt** by using pip.

    pip install -r requirements.txt


## Usage

    python imghide.py

**Encode**

 - Choose *Encode* in the options menu
 ![enter image description here](https://i.ibb.co/DLvS9qj/imghide-2-png.png)
 
 - Enter the image path (with extension)
 ![enter image description here](https://i.ibb.co/ZKkzWWr/imghide-3.png)
 - Enter the message to be hidden
 ![enter image description here](https://i.ibb.co/wrG4Qvy/imghide-4.png)
 - Choose a password to encrypt with AES-256 (optional)
 ![enter image description here](https://i.ibb.co/mCF3VkL/imghide-5.png)

The image is encoded and saved as a ***PNG*** file.

**Decode**

 - Choose *Decode* from the menu
![enter image description here](https://i.ibb.co/tmh9Y5S/imghide-6.png)

 - Enter the path of the encoded image (with extension) and type in the password to decrypt (leave empty if no password was used)
![enter image description here](https://i.ibb.co/bd7qWgx/imghide-7.png)

The decoded text will be displayed on the terminal.
