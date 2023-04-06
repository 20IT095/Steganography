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

In a gray scale image each pixel is represented in 8 bits. The last bit in a pixel is called as Least Significant bit as its
value will affect the pixel value only by “1”. So, this property is used to hide the data in the image. If anyone have
considered last two bits as LSB bits as they will affect the pixel value only by “3”. This helps in storing extra data.
The Least Significant Bit (LSB) steganography is one such technique in which least significant bit of the image is
replaced with data bit. As this method is vulnerable to steganalysis so as to make it more secure we encrypt the raw
data before embedding it in the image. Though the encryption process increases the time complexity, but at the same
time provides higher security also. This approach is very simple. In this method the least significant bits of some or
all of the bytes inside an image is replaced with a bits of the secret message. The LSB embedding approach has
become the basis of many techniques that hide messages within multimedia carrier data. LSB embedding may even
be applied in particular data domains – for example, embedding a hidden message into the color values of RGB
bitmap data, or into the frequency coefficients of a JPEG image. LSB embedding can also be applied to a variety of
data formats and types. Therefore, LSB embedding is one of the most important steganography techniques in use
today. 
