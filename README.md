# Steganography using LSB Method
STEGANOGRAPHY comes from the Greek Words: STEGANOS – “Covered”, GRAPHIE – “Writing”. [3]
Generally the sender writes an innocuous message and then conceals a secret message on the same piece of paper.
The main goal of steganography is to communicate securely in a completely undetectable manner and to avoid
drawing suspicion to the transmission of a hidden data. It is not to keep others from knowing the hidden information,
but it is to keep others from thinking that the information even exists. The data can be hidden in basic formats like:
Audio, Video, Text and Images etc. The various types of steganography include:
a. Image Steganography: The image steganography is the process in which we hide the data within an image
so that there will not be any perceived visible change in the original image. The conventional image
steganography algorithm is LSB embedding algorithm.
b. Audio Steganography: Steganography can be applied to audio files i.e., we can hide information in an
audio file, it can be called Audio Steganography. The audio file should be undetectable.
c. Video Steganography: Steganography can be applied to video files also. If we hide information in a video
file, it can be called Video Steganography. The video file should be undetectable by attacker.
LSB Method in image stegnography 

![image](https://user-images.githubusercontent.com/88429482/230294303-51036307-9478-47c8-adc3-de9baeb742b3.png)

In image steganography using the LSB (Least Significant Bit) algorithm, secret information is hidden in the least significant bits of the pixels in an image.

The LSB algorithm works by replacing the least significant bit of each pixel with a bit from the secret message. Since the least significant bit of a pixel has the least impact on the overall image quality, changing it does not significantly alter the appearance of the image to the human eye.

The process of hiding the secret message in an image using the LSB algorithm involves the following steps:

Convert the secret message into binary form.
Choose a cover image that will be used to hide the secret message.
Divide the cover image into small blocks of pixels.
For each block of pixels, replace the least significant bit of each pixel with a bit from the secret message.
Repeat step 4 until all bits of the secret message have been hidden in the cover image.
Save the stego image, which is the cover image with the hidden secret message.
To extract the secret message from the stego image, the LSB algorithm is reversed by extracting the least significant bit of each pixel in the stego image to obtain the binary message.
