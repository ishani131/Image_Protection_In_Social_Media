# Image_Protection_In_Social_Media

<h3>Watermarking and Encryption</h3>
This repository provides a set of tools and algorithms to watermark and encrypt images, ensuring their protection and integrity. The goal is to embed a unique watermark into each image and encrypt the watermarked image to secure it from unauthorized access. Only with the appropriate key can the original image be decrypted and downloaded.

<h4>Functionality</h4>
Embedding Watermark: The embed.py script allows you to embed a unique watermark onto an original image. Each image is watermarked with a distinct watermark, ensuring uniqueness and traceability.

Encryption: The e_d.py script encrypts the watermarked image using the AES algorithm. A unique encryption key is used for each image, enhancing the security of the encrypted content.

Watermark Detection: The fulldetection.py script implements the "Template Matching" algorithm to detect the presence of a watermark in a watermarked image. By calculating the coefficient correlation between the watermark and the image, it identifies the highest value based on a threshold, indicating the presence of the watermark.

Watermark Attack: The attack.py script simulates potential attacks on the watermark by resizing and altering the lighting of the watermark image. This helps evaluate the resilience of the watermarking technique against such attacks.

<h4>Usage</h4>
To access the functionalities mentioned above, use the main.py script. It provides a convenient interface to interact with the watermarking, encryption, detection, and attack processes.

<h4>Requirements</h4>
The following dependencies are required to run the scripts successfully:

Python 3.x
Libraries: Pillow, cryptography, OpenCV
Make sure to install the necessary dependencies before running the scripts.

Please refer to the individual script files for more detailed instructions on usage and additional information.

Feel free to explore, contribute, and adapt the provided functionalities according to your specific requirements. Protect your images with watermarks and encryption to ensure their security and integrity.
