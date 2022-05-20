# image_local_activity
The method calculates the difference between the value of a single pixel, and the surrounding area - across an entire image. The goal of the investigation is to find an image activity feature that will correlate with a successfull decoding of embedded data.

The method takes a CMYK image and extracts its K channel. Then, it 'walks' through the image and calculates pixel values within the kernel. The output is a Pandas DataFrame that contains all the differences between the value of the center pixel of the kernel, and the mean of all pixel values within the kernel.

Further reading:

https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4021136

https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8076800
