# Transfer Medical Images

DICOM is a standard used to transfer medical images from one host to another.
This project emulates a workflow, in which a device constructs an image
and sends it to a central server.
A Radiologist picks up the image for diagnosis.

This project implements a DICOM SCU 'sender' to send an image.
Use an off-the-shelf SCP 'receiver' to receive and store the image.
Implement a Python utility to send an email to the radiologist,
identifying the image to be diagnosed.

You can use [MergeCOM](http://estore.merge.com/mergecom3/download-thanks.aspx?productId=b1534ecc-1e57-480c-b5ca-5681b30e996f)

Hints:

- The zip file downloaded from the above link has the required libraries and information
- The user manual in mc3doc gives a good introduction to DICOM 
- mc3apps has the image storage in stor_scp and stor_scu. Build using Visual Studio.
- mc3bin has useful utilities
- Edit the mergecom.pro to include the license, adjust the paths as per your installation
